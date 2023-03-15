---
title: ID3V2Tag
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: एक ID3v2 टैग क प्रतनधत्व करत है कृपय अधक जनकर प्रप्त करेंhttps//en.wikipedia.org/wiki/ID3ID3v2https//en.wikipedia.org/wiki/ID3ID3v2 .
type: docs
weight: 490
url: /hi/net/groupdocs.metadata.formats.audio/id3v2tag/
---
## ID3V2Tag class

एक ID3v2 टैग का प्रतिनिधित्व करता है। कृपया अधिक जानकारी प्राप्त करें[https://en.wikipedia.org/wiki/ID3#ID3v2](https://en.wikipedia.org/wiki/ID3#ID3v2) .

```csharp
public sealed class ID3V2Tag : ID3Tag
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ID3V2Tag](id3v2tag)() | का एक नया उदाहरण प्रारंभ करता है[`ID3V2Tag`](../id3v2tag) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v2tag/album) { get; set; } | एल्बम/मूवी/शो शीर्षक प्राप्त या सेट करता है। यह मान टीएएलबी फ्रेम द्वारा दर्शाया गया है। |
| [Artist](../../groupdocs.metadata.formats.audio/id3v2tag/artist) { get; set; } | लीड आर्टिस्ट/लीड परफॉर्मर/सोलिस्ट/परफॉर्मिंग ग्रुप को प्राप्त या सेट करता है। यह मान TPE1 फ्रेम द्वारा दर्शाया गया है। |
| [AttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/attachedpictures) { get; set; } | संलग्न चित्रों को सीधे ऑडियो फ़ाइल से संबंधित करता है या सेट करता है। यह मान APIC फ्रेम द्वारा दर्शाया गया है। |
| [Band](../../groupdocs.metadata.formats.audio/id3v2tag/band) { get; set; } | बैंड/ऑर्केस्ट्रा/सहायक को प्राप्त या सेट करता है। यह मान TPE2 फ्रेम द्वारा दर्शाया गया है। |
| [BitsPerMinute](../../groupdocs.metadata.formats.audio/id3v2tag/bitsperminute) { get; set; } | ऑडियो के मुख्य भाग में प्रति मिनट बीट्स की संख्या प्राप्त या सेट करता है। यह मान TBPM फ्रेम द्वारा दर्शाया गया है। |
| [Comments](../../groupdocs.metadata.formats.audio/id3v2tag/comments) { get; set; } | उपयोगकर्ता टिप्पणियों को प्राप्त या सेट करता है। यह मान COMM फ्रेम द्वारा दर्शाया गया है। फ्रेम किसी भी प्रकार की पूर्ण पाठ जानकारी के लिए अभिप्रेत है जो किसी अन्य फ्रेम में फिट नहीं होती है। |
| [Composers](../../groupdocs.metadata.formats.audio/id3v2tag/composers) { get; set; } | संगीतकार को प्राप्त या सेट करता है। नाम "/" वर्ण से अलग किए गए हैं। यह मान TCOM फ्रेम द्वारा दर्शाया गया है। |
| [ContentType](../../groupdocs.metadata.formats.audio/id3v2tag/contenttype) { get; set; } | सामग्री प्रकार प्राप्त या सेट करता है। यह मान TCON फ्रेम द्वारा दर्शाया गया है। |
| [Copyright](../../groupdocs.metadata.formats.audio/id3v2tag/copyright) { get; set; } | कॉपीराइट संदेश प्राप्त या सेट करता है. यह मान TCOP फ़्रेम द्वारा दर्शाया जाता है. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [Date](../../groupdocs.metadata.formats.audio/id3v2tag/date) { get; set; } | डीडीएमएम प्रारूप में एक संख्यात्मक स्ट्रिंग प्राप्त या सेट करता है जिसमें रिकॉर्डिंग की तारीख होती है। यह फ़ील्ड हमेशा चार वर्णों की होती है। यह मान TDAT फ़्रेम द्वारा दर्शाया जाता है। |
| [EncodedBy](../../groupdocs.metadata.formats.audio/id3v2tag/encodedby) { get; set; } | ऑडियो फ़ाइल को एन्कोड करने वाले व्यक्ति या संगठन का नाम प्राप्त या सेट करता है। यह मान TENC फ्रेम द्वारा दर्शाया गया है। |
| [Isrc](../../groupdocs.metadata.formats.audio/id3v2tag/isrc) { get; set; } | अंतर्राष्ट्रीय मानक रिकॉर्डिंग कोड (ISRC) (12 अक्षर) प्राप्त या सेट करता है। यह मान TSRC फ्रेम द्वारा दर्शाया गया है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [LengthInMilliseconds](../../groupdocs.metadata.formats.audio/id3v2tag/lengthinmilliseconds) { get; set; } | मिलीसेकंड में ऑडियो फ़ाइल की लंबाई प्राप्त या सेट करता है, जिसे एक संख्यात्मक स्ट्रिंग के रूप में दर्शाया जाता है। यह मान TLEN फ्रेम द्वारा दर्शाया जाता है। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [MusicalKey](../../groupdocs.metadata.formats.audio/id3v2tag/musicalkey) { get; set; } | उस संगीत कुंजी को प्राप्त या सेट करता है जिसमें ध्वनि शुरू होती है। यह मान TKEY फ्रेम द्वारा दर्शाया गया है। |
| [OriginalAlbum](../../groupdocs.metadata.formats.audio/id3v2tag/originalalbum) { get; set; } | मूल एल्बम/मूवी/शो शीर्षक प्राप्त या सेट करता है। यह मान TOAL फ्रेम द्वारा दर्शाया गया है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [Publisher](../../groupdocs.metadata.formats.audio/id3v2tag/publisher) { get; set; } | लेबल या प्रकाशक का नाम प्राप्त या सेट करता है। यह मान TPUB फ्रेम द्वारा दर्शाया गया है। |
| [SizeInBytes](../../groupdocs.metadata.formats.audio/id3v2tag/sizeinbytes) { get; set; } | बाइट्स में ऑडियो फ़ाइल का आकार प्राप्त या सेट करता है, ID3v2 टैग को छोड़कर, एक संख्यात्मक स्ट्रिंग के रूप में दर्शाया गया है। यह मान TSIZ फ्रेम द्वारा दर्शाया गया है। |
| [SoftwareHardware](../../groupdocs.metadata.formats.audio/id3v2tag/softwarehardware) { get; set; } | उपयोग किए गए ऑडियो एनकोडर और इसकी सेटिंग्स को प्राप्त या सेट करता है जब फ़ाइल एन्कोडेड थी। यह मान TSSE फ्रेम द्वारा दर्शाया गया है। |
| [Subtitle](../../groupdocs.metadata.formats.audio/id3v2tag/subtitle) { get; set; } | उपशीर्षक/विवरण परिशोधन को प्राप्त या सेट करता है। यह मान TIT3 फ्रेम द्वारा दर्शाया गया है। |
| [TagSize](../../groupdocs.metadata.formats.audio/id3v2tag/tagsize) { get; } | टैग का आकार प्राप्त करता है। |
| [Time](../../groupdocs.metadata.formats.audio/id3v2tag/time) { get; set; } | एचएचएमएम प्रारूप में एक संख्यात्मक स्ट्रिंग प्राप्त या सेट करता है जिसमें रिकॉर्डिंग के लिए समय होता है। यह फ़ील्ड हमेशा चार वर्ण लंबा होता है। यह मान टाइम फ्रेम द्वारा दर्शाया जाता है। |
| [Title](../../groupdocs.metadata.formats.audio/id3v2tag/title) { get; set; } | शीर्षक/गीत का नाम/सामग्री विवरण प्राप्त या सेट करता है। यह मान TIT2 फ्रेम द्वारा दर्शाया गया है। |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v2tag/tracknumber) { get; set; } | अपनी मूल रिकॉर्डिंग पर ऑडियो-फ़ाइल की ऑर्डर संख्या वाली एक संख्यात्मक स्ट्रिंग प्राप्त या सेट करता है। यह मान TRCK फ़्रेम द्वारा दर्शाया गया है। |
| [TrackPlayCounter](../../groupdocs.metadata.formats.audio/id3v2tag/trackplaycounter) { get; } | फ़ाइल को चलाने की संख्या प्राप्त करता है। यह मान PCNT फ्रेम द्वारा दर्शाया गया है। |
| override [Version](../../groupdocs.metadata.formats.audio/id3v2tag/version) { get; } | ID3 संस्करण प्राप्त करता है। |
| [Year](../../groupdocs.metadata.formats.audio/id3v2tag/year) { get; set; } | रिकॉर्डिंग के एक वर्ष के साथ एक संख्यात्मक स्ट्रिंग प्राप्त या सेट करता है। यह फ़्रेम हमेशा चार वर्णों का होता है (वर्ष 10000 तक). यह मान TYER फ़्रेम द्वारा दर्शाया जाता है. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Add](../../groupdocs.metadata.formats.audio/id3v2tag/add)(ID3V2TagFrame) | टैग में एक फ्रेम जोड़ता है। |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को जोड़ता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Clear](../../groupdocs.metadata.formats.audio/id3v2tag/clear)(string) | निर्दिष्ट आईडी के साथ सभी फ़्रेमों को हटाता है। |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | निर्धारित करता है कि पैकेज में निर्दिष्ट नाम के साथ मेटाडेटा गुण है या नहीं। |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को संतुष्ट करने वाले मेटाडेटा गुणों को ढूँढता है। खोज पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करती है। |
| [Get](../../groupdocs.metadata.formats.audio/id3v2tag/get)(string) | निर्दिष्ट आईडी के साथ फ्रेम की एक सरणी प्राप्त करता है। |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृति करता है। |
| [Remove](../../groupdocs.metadata.formats.audio/id3v2tag/remove)(ID3V2TagFrame) | निर्दिष्ट फ्रेम को टैग से हटाता है। |
| [RemoveAttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/removeattachedpictures)() | एपीआईसी फ्रेम में संग्रहीत सभी संलग्न चित्रों को हटा देता है। |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को पूरा करने वाले मेटाडेटा गुणों को हटाता है। |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | पैकेज से लिखने योग्य मेटाडेटा गुणों को हटाता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Set](../../groupdocs.metadata.formats.audio/id3v2tag/set)(ID3V2TagFrame) | निर्दिष्ट आईडी के समान आईडी वाले सभी फ्रेम हटा देता है और टैग में नया फ्रेम जोड़ता है। |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को सेट करता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। यह विधि एक संयोजन है[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) और[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) यदि कोई मौजूदा संपत्ति विधेय को संतुष्ट करती है तो उसका मान अपडेट किया जाता है। यदि पैकेज में कोई ज्ञात संपत्ति गायब है जो विधेय को संतुष्ट करती है तो इसे पैकेज में जोड़ा जाता है। |
| [ToList](../../groupdocs.metadata.formats.audio/id3v2tag/tolist)() | पैकेज से एक सूची बनाता है। |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | अद्यतन ज्ञात मेटाडेटा गुण निर्दिष्ट विधेय को संतुष्ट करते हैं। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |

### टिप्पणियों

**और अधिक जानें**

* [ID3v2 टैग को संभालना](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### उदाहरण

यह उदाहरण दिखाता है कि MP3 फ़ाइल में ID3v2 टैग को कैसे पढ़ा जाए।

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V2 != null)
    {
        Console.WriteLine(root.ID3V2.Album);
        Console.WriteLine(root.ID3V2.Artist);
        Console.WriteLine(root.ID3V2.Band);
        Console.WriteLine(root.ID3V2.Title);
        Console.WriteLine(root.ID3V2.Composers);
        Console.WriteLine(root.ID3V2.Copyright);
        Console.WriteLine(root.ID3V2.Publisher);
        Console.WriteLine(root.ID3V2.OriginalAlbum);
        Console.WriteLine(root.ID3V2.MusicalKey);

        if (root.ID3V2.AttachedPictures != null)
        {
            foreach (var attachedPicture in root.ID3V2.AttachedPictures)
            {
                Console.WriteLine(attachedPicture.AttachedPictureType);
                Console.WriteLine(attachedPicture.MimeType);
                Console.WriteLine(attachedPicture.Description);

                // ...
            }
        }

        // ...
    }
}
```

### यह सभी देखें

* class [ID3Tag](../id3tag)
* नाम स्थान [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
