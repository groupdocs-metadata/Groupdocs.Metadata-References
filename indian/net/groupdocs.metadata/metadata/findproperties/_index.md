---
title: FindProperties
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: नर्दष्ट वधेय क संतुष्ट करने वले मेटडेट गुणं क ढूँढत है खज पुनरवर्त है इसलए यह सभ नेस्टेड पैकेजं क भ प्रभवत करत है
type: docs
weight: 50
url: /hi/net/groupdocs.metadata/metadata/findproperties/
---
## Metadata.FindProperties method

निर्दिष्ट विधेय को संतुष्ट करने वाले मेटाडेटा गुणों को ढूँढता है। खोज पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करती है।

```csharp
public IEnumerable<MetadataProperty> FindProperties(Func<MetadataProperty, bool> predicate)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| predicate | Func`2 | किसी शर्त के लिए प्रत्येक मेटाडेटा गुण का परीक्षण करने के लिए एक फ़ंक्शन। |

### प्रतिलाभ की मात्रा

एकIEnumerable जिसमें शर्त को पूरा करने वाले पैकेज के गुण शामिल हैं।

### टिप्पणियों

**और अधिक जानें**

* इस पद्धति के उपयोगों को प्रदर्शित करने वाले और उदाहरण: [मेटाडेटा निकालना](https://docs.groupdocs.com/display/metadatanet/Extracting+metadata)

### उदाहरण

यह उदाहरण प्रदर्शित करता है कि टैग का उपयोग करके विशिष्ट मेटाडेटा गुणों की खोज कैसे करें।

```csharp
using (Metadata metadata = new Metadata(Constants.InputPptx))
{
    // विधेय को संतुष्ट करने वाले सभी गुण प्राप्त करें:
    // संपत्ति में अंतिम दस्तावेज़ संपादक का नाम या दस्तावेज़ को अंतिम बार संशोधित करने की तिथि / समय शामिल है
    var properties = metadata.FindProperties(p => p.Tags.Contains(Tags.Person.Editor) || p.Tags.Contains(Tags.Time.Modified));
    foreach (var property in properties)
    {
        Console.WriteLine("Property name: {0}, Property value: {1}", property.Name, property.Value);
    }
}
```

### यह सभी देखें

* class [MetadataProperty](../../../groupdocs.metadata.common/metadataproperty)
* delegate [Func&lt;T,TResult&gt;](../../../groupdocs.metadata.common/func-2)
* class [Metadata](../../metadata)
* नाम स्थान [GroupDocs.Metadata](../../metadata)
* सभा [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->