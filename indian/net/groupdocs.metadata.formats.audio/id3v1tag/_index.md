---
title: ID3V1Tag
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: एक ID3v1 टैग क प्रतनधत्व करत है कृपय अधक जनकर प्रप्त करेंhttps//en.wikipedia.org/wiki/ID3ID3v1https//en.wikipedia.org/wiki/ID3ID3v1 .
type: docs
weight: 410
url: /hi/net/groupdocs.metadata.formats.audio/id3v1tag/
---
## ID3V1Tag class

एक ID3v1 टैग का प्रतिनिधित्व करता है। कृपया अधिक जानकारी प्राप्त करें[https://en.wikipedia.org/wiki/ID3#ID3v1](https://en.wikipedia.org/wiki/ID3#ID3v1) .

```csharp
public sealed class ID3V1Tag : ID3Tag
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ID3V1Tag](id3v1tag)() | का एक नया उदाहरण प्रारंभ करता है[`ID3V1Tag`](../id3v1tag) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v1tag/album) { get; set; } | एल्बम प्राप्त या सेट करता है। अधिकतम लंबाई 30 वर्ण है. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v1tag/artist) { get; set; } | कलाकार को प्राप्त या सेट करता है। अधिकतम लंबाई 30 वर्ण है. |
| [Comment](../../groupdocs.metadata.formats.audio/id3v1tag/comment) { get; set; } | टिप्पणी प्राप्त या सेट करता है। अधिकतम लंबाई 30 वर्ण है. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [GenreValue](../../groupdocs.metadata.formats.audio/id3v1tag/genrevalue) { get; } | शैली पहचानकर्ता प्राप्त या सेट करता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [Title](../../groupdocs.metadata.formats.audio/id3v1tag/title) { get; set; } | शीर्षक प्राप्त या सेट करता है। |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v1tag/tracknumber) { get; set; } | ट्रैक नंबर प्राप्त या सेट करता है। केवल ID3v1.1 टैग में प्रस्तुत किया गया. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v1tag/version) { get; } | ID3 संस्करण प्राप्त करता है। यह ID3 या ID3v1.1 हो सकता है |
| [Year](../../groupdocs.metadata.formats.audio/id3v1tag/year) { get; set; } | वर्ष प्राप्त या सेट करता है। अधिकतम लंबाई 4 वर्ण है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को जोड़ता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | निर्धारित करता है कि पैकेज में निर्दिष्ट नाम के साथ मेटाडेटा गुण है या नहीं। |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को संतुष्ट करने वाले मेटाडेटा गुणों को ढूँढता है। खोज पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करती है। |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृति करता है। |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को पूरा करने वाले मेटाडेटा गुणों को हटाता है। |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | पैकेज से लिखने योग्य मेटाडेटा गुणों को हटाता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को सेट करता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। यह विधि एक संयोजन है[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) और[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) यदि कोई मौजूदा संपत्ति विधेय को संतुष्ट करती है तो उसका मान अपडेट किया जाता है। यदि पैकेज में कोई ज्ञात संपत्ति गायब है जो विधेय को संतुष्ट करती है तो इसे पैकेज में जोड़ा जाता है। |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | अद्यतन ज्ञात मेटाडेटा गुण निर्दिष्ट विधेय को संतुष्ट करते हैं। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |

### टिप्पणियों

ID3(v1) टैग MP3 के अंत में अतिरिक्त डेटा का एक छोटा सा हिस्सा है। कृपया अधिक जानकारी प्राप्त करें[http://id3.org/ID3v1](http://id3.org/ID3v1) .

**और अधिक जानें**

* [ID3v1 टैग को संभालना](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v1+tag)

### उदाहरण

यह कोड नमूना दिखाता है कि MP3 फ़ाइल में ID3v1 टैग को कैसे पढ़ा जाए।

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V1))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V1 != null)
    {
        Console.WriteLine(root.ID3V1.Album);
        Console.WriteLine(root.ID3V1.Artist);
        Console.WriteLine(root.ID3V1.Title);
        Console.WriteLine(root.ID3V1.Version);
        Console.WriteLine(root.ID3V1.Comment);

        // ...
    }
}
```

### यह सभी देखें

* class [ID3Tag](../id3tag)
* नाम स्थान [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
