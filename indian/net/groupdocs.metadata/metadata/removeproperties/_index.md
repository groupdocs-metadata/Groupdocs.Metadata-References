---
title: RemoveProperties
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: नर्दष्ट वधेय क पूर करने वले मेटडेट गुणं क हटत है
type: docs
weight: 90
url: /hi/net/groupdocs.metadata/metadata/removeproperties/
---
## Metadata.RemoveProperties method

निर्दिष्ट विधेय को पूरा करने वाले मेटाडेटा गुणों को हटाता है।

```csharp
public int RemoveProperties(Func<MetadataProperty, bool> predicate)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| predicate | Func`2 | किसी शर्त के लिए प्रत्येक मेटाडेटा गुण का परीक्षण करने के लिए एक फ़ंक्शन। |

### प्रतिलाभ की मात्रा

प्रभावित संपत्तियों की संख्या।

### टिप्पणियों

**और अधिक जानें**

* इस पद्धति के उपयोगों को प्रदर्शित करने वाले और उदाहरण: [मेटाडेटा निकाल रहा है](https://docs.groupdocs.com/display/metadatanet/Removing+metadata)

### उदाहरण

यह उदाहरण दर्शाता है कि विभिन्न मानदंडों का उपयोग करके विशिष्ट मेटाडेटा गुणों को कैसे हटाया जाए।

```csharp
using (Metadata metadata = new Metadata(Constants.InputDocx))
{
    // विधेय को संतुष्ट करने वाले सभी गुणों को हटा दें:
    // संपत्ति में दस्तावेज़ लेखक का नाम शामिल है या
    // यह अंतिम संपादक OR को संदर्भित करता है
    // गुण मान एक स्ट्रिंग है जिसमें सबस्ट्रिंग "जॉन" होता है (पहचाने गए मेटाडेटा से जॉन के किसी भी उल्लेख को हटाने के लिए)
    var affected = metadata.RemoveProperties(
            p => p.Tags.Contains(Tags.Person.Creator) ||
            p.Tags.Contains(Tags.Person.Editor) ||
            p.Value.Type == MetadataPropertyType.String && p.Value.ToString().Contains("John"));

    Console.WriteLine("Properties removed: {0}", affected);

    metadata.Save(Constants.OutputDocx);
}
```

### यह सभी देखें

* delegate [Func&lt;T,TResult&gt;](../../../groupdocs.metadata.common/func-2)
* class [MetadataProperty](../../../groupdocs.metadata.common/metadataproperty)
* class [Metadata](../../metadata)
* नाम स्थान [GroupDocs.Metadata](../../metadata)
* सभा [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->