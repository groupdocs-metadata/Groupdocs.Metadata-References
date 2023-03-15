---
title: LyricsTag
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: Lyrics3 v2.00 मेटडेट क प्रतनधत्व करत है कृपय अधक जनकर प्रप्त करेंhttp//id3.org/Lyrics3v2 .
type: docs
weight: 570
url: /hi/net/groupdocs.metadata.formats.audio/lyricstag/
---
## LyricsTag class

Lyrics3 v2.00 मेटाडेटा का प्रतिनिधित्व करता है। कृपया अधिक जानकारी प्राप्त करेंhttp://id3.org/Lyrics3v2 .

```csharp
public sealed class LyricsTag : CustomPackage
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [LyricsTag](lyricstag)() | का एक नया उदाहरण प्रारंभ करता है[`LyricsTag`](../lyricstag) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [AdditionalInfo](../../groupdocs.metadata.formats.audio/lyricstag/additionalinfo) { get; set; } | अतिरिक्त जानकारी प्राप्त या सेट करता है। यह मान INF फ़ील्ड द्वारा दर्शाया गया है। |
| [Album](../../groupdocs.metadata.formats.audio/lyricstag/album) { get; set; } | एल्बम नाम प्राप्त या सेट करता है। यह मान EAL फ़ील्ड द्वारा दर्शाया गया है। |
| [Artist](../../groupdocs.metadata.formats.audio/lyricstag/artist) { get; set; } | कलाकार का नाम प्राप्त या सेट करता है। यह मान ईएआर फ़ील्ड द्वारा दर्शाया गया है। |
| [Author](../../groupdocs.metadata.formats.audio/lyricstag/author) { get; set; } | लेखक को प्राप्त या सेट करता है। यह मान AUT फ़ील्ड द्वारा दर्शाया गया है। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [Lyrics](../../groupdocs.metadata.formats.audio/lyricstag/lyrics) { get; set; } | गीत को प्राप्त या सेट करता है। यह मान LYR फ़ील्ड द्वारा दर्शाया गया है। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [Track](../../groupdocs.metadata.formats.audio/lyricstag/track) { get; set; } | ट्रैक शीर्षक प्राप्त या सेट करता है। यह मान ETT फ़ील्ड द्वारा दर्शाया गया है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को जोड़ता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | निर्धारित करता है कि पैकेज में निर्दिष्ट नाम के साथ मेटाडेटा गुण है या नहीं। |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को संतुष्ट करने वाले मेटाडेटा गुणों को ढूँढता है। खोज पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करती है। |
| [Get](../../groupdocs.metadata.formats.audio/lyricstag/get)(string) | निर्दिष्ट आईडी के साथ फ़ील्ड का मान प्राप्त करता है। |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृति करता है। |
| [Remove](../../groupdocs.metadata.formats.audio/lyricstag/remove)(string) | निर्दिष्ट आईडी के साथ फ़ील्ड को हटाता है। |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को पूरा करने वाले मेटाडेटा गुणों को हटाता है। |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | पैकेज से लिखने योग्य मेटाडेटा गुणों को हटाता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Set](../../groupdocs.metadata.formats.audio/lyricstag/set)(LyricsField) | निर्दिष्ट Lyrics3 फ़ील्ड को जोड़ता या बदलता है. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को सेट करता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। यह विधि एक संयोजन है[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) और[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) यदि कोई मौजूदा संपत्ति विधेय को संतुष्ट करती है तो उसका मान अपडेट किया जाता है। यदि पैकेज में कोई ज्ञात संपत्ति गायब है जो विधेय को संतुष्ट करती है तो इसे पैकेज में जोड़ा जाता है। |
| [ToList](../../groupdocs.metadata.formats.audio/lyricstag/tolist)() | पैकेज से एक सूची बनाता है। |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | अद्यतन ज्ञात मेटाडेटा गुण निर्दिष्ट विधेय को संतुष्ट करते हैं। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |

### टिप्पणियों

Lyrics3 v2.00 सूचना का प्रतिनिधित्व करने के लिए फ़ील्ड का उपयोग करता है। फ़ील्ड में डेटा में मानक के अनुसार 01 से 254 तक ASCII वर्ण शामिल हो सकते हैं। जैसा कि ASCII वर्ण मानचित्र केवल 00 से 128 ISO-8859 तक परिभाषित किया गया है- 1 माना जा सकता है। स्थान के आधार पर संख्यात्मक फ़ील्ड 5 या 6 वर्ण लंबे होते हैं, और शून्य के साथ गद्देदार होते हैं।

**और अधिक जानें**

* [गीत टैग को संभालना](https://docs.groupdocs.com/display/metadatanet/Handling+the+Lyrics+tag)

### उदाहरण

यह कोड नमूना दिखाता है कि एमपी3 फ़ाइल से लिरिक्स टैग को कैसे पढ़ा जाए।

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithLyrics))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.Lyrics3V2 != null)
    {
        Console.WriteLine(root.Lyrics3V2.Lyrics);
        Console.WriteLine(root.Lyrics3V2.Album);
        Console.WriteLine(root.Lyrics3V2.Artist);
        Console.WriteLine(root.Lyrics3V2.Track);

        // ...

        // वैकल्पिक रूप से, आप टैग फ़ील्ड की पूरी सूची के माध्यम से लूप कर सकते हैं
        foreach (var field in root.Lyrics3V2.ToList())
        {
            Console.WriteLine("{0} = {1}", field.ID, field.Data);
        }
    }
}
```

### यह सभी देखें

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
