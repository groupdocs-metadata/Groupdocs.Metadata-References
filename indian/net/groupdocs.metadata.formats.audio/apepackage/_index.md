---
title: ApePackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: एक APE v2 मेटडेट पैकेज क प्रतनधत्व करत है कृपय अधक जनकर प्रप्त करेंhttp//wiki.hydrogenaud.io/index.phptitleAPE_keyhttp//wiki.hydrogenaud.io/index.phptitleAPE_key .
type: docs
weight: 380
url: /hi/net/groupdocs.metadata.formats.audio/apepackage/
---
## ApePackage class

एक APE v2 मेटाडेटा पैकेज का प्रतिनिधित्व करता है। कृपया अधिक जानकारी प्राप्त करें[http://wiki.hydrogenaud.io/index.php?title=APE_key](http://wiki.hydrogenaud.io/index.php?title=APE_key) .

```csharp
public sealed class ApePackage : CustomPackage
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Abstract](../../groupdocs.metadata.formats.audio/apepackage/abstract) { get; } | सार लिंक प्राप्त करता है। |
| [Album](../../groupdocs.metadata.formats.audio/apepackage/album) { get; } | एल्बम प्राप्त करता है। |
| [Artist](../../groupdocs.metadata.formats.audio/apepackage/artist) { get; } | कलाकार प्राप्त करता है। |
| [Bibliography](../../groupdocs.metadata.formats.audio/apepackage/bibliography) { get; } | ग्रंथ सूची प्राप्त करता है। |
| [Comment](../../groupdocs.metadata.formats.audio/apepackage/comment) { get; } | टिप्पणी प्राप्त करता है। |
| [Composer](../../groupdocs.metadata.formats.audio/apepackage/composer) { get; } | संगीतकार मिलता है। |
| [Conductor](../../groupdocs.metadata.formats.audio/apepackage/conductor) { get; } | कंडक्टर हो जाता है। |
| [Copyright](../../groupdocs.metadata.formats.audio/apepackage/copyright) { get; } | कॉपीराइट प्राप्त करता है। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [DebutAlbum](../../groupdocs.metadata.formats.audio/apepackage/debutalbum) { get; } | को पहली एल्बम मिली. |
| [File](../../groupdocs.metadata.formats.audio/apepackage/file) { get; } | फ़ाइल प्राप्त करता है। |
| [Genre](../../groupdocs.metadata.formats.audio/apepackage/genre) { get; } | शैली प्राप्त करता है। |
| [Isbn](../../groupdocs.metadata.formats.audio/apepackage/isbn) { get; } | चेक अंक के साथ आईएसबीएन नंबर प्राप्त करता है। और देखें: https://en.wikipedia.org/wiki/International_Standard_Book_Number. |
| [Isrc](../../groupdocs.metadata.formats.audio/apepackage/isrc) { get; } | अंतर्राष्ट्रीय मानक रिकॉर्डिंग संख्या प्राप्त करता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [Language](../../groupdocs.metadata.formats.audio/apepackage/language) { get; } | भाषा प्राप्त करता है। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [PublicationRight](../../groupdocs.metadata.formats.audio/apepackage/publicationright) { get; } | प्रकाशन सही हो जाता है। |
| [Publisher](../../groupdocs.metadata.formats.audio/apepackage/publisher) { get; } | प्रकाशक प्राप्त करता है। |
| [RecordLocation](../../groupdocs.metadata.formats.audio/apepackage/recordlocation) { get; } | रिकॉर्ड स्थान प्राप्त करता है। |
| [Subtitle](../../groupdocs.metadata.formats.audio/apepackage/subtitle) { get; } | उपशीर्षक प्राप्त करता है। |
| [Title](../../groupdocs.metadata.formats.audio/apepackage/title) { get; } | शीर्षक प्राप्त करता है। |
| [Track](../../groupdocs.metadata.formats.audio/apepackage/track) { get; } | ट्रैक नंबर प्राप्त करता है। |

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

**और अधिक जानें**

* [APEv2 टैग को संभालना](https://docs.groupdocs.com/display/metadatanet/Handling+the+APEv2+tag)

### उदाहरण

यह उदाहरण दर्शाता है कि एमपी3 फ़ाइल में एपीईवी2 टैग को कैसे पढ़ा जाए।

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithApe))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ApeV2 != null)
    {
        Console.WriteLine(root.ApeV2.Album);
        Console.WriteLine(root.ApeV2.Title);
        Console.WriteLine(root.ApeV2.Artist);
        Console.WriteLine(root.ApeV2.Composer);
        Console.WriteLine(root.ApeV2.Copyright);
        Console.WriteLine(root.ApeV2.Genre);
        Console.WriteLine(root.ApeV2.Language);

        // ...
    }
}
```

### यह सभी देखें

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
