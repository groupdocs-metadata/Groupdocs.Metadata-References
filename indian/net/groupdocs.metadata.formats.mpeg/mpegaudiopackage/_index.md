---
title: MpegAudioPackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: एमपईज ऑडय मेटडेट क प्रतनधत्व करत है
type: docs
weight: 2150
url: /hi/net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/
---
## MpegAudioPackage class

एमपीईजी ऑडियो मेटाडेटा का प्रतिनिधित्व करता है।

```csharp
public sealed class MpegAudioPackage : CustomPackage
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MpegAudioPackage](mpegaudiopackage)() | का एक नया उदाहरण प्रारंभ करता है[`MpegAudioPackage`](../mpegaudiopackage) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Bitrate](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/bitrate) { get; } | बिटरेट प्राप्त करता है। |
| [ChannelMode](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/channelmode) { get; } | चैनल मोड प्राप्त करता है। |
| [Copyright](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/copyright) { get; } | कॉपीराइट बिट प्राप्त करता है. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [Emphasis](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/emphasis) { get; } | पर जोर दिया जाता है। |
| [Frequency](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/frequency) { get; } | आवृत्ति प्राप्त करता है। |
| [HeaderPosition](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/headerposition) { get; } | हेडर ऑफ़सेट हो जाता है. |
| [IsOriginal](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/isoriginal) { get; } | मूल बिट प्राप्त करता है। |
| [IsProtected](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/isprotected) { get; } | हो जाता है`सत्य` अगर संरक्षित है. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [Layer](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/layer) { get; } | परत विवरण प्राप्त करता है। एक MP3 ऑडियो के लिए यह '3' है. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [ModeExtensionBits](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/modeextensionbits) { get; } | मोड एक्सटेंशन बिट्स प्राप्त करता है। |
| [MpegAudioVersion](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/mpegaudioversion) { get; } | एमपीईजी ऑडियो संस्करण प्राप्त करता है। MPEG-1, MPEG-2 आदि हो सकते हैं. |
| [PaddingBit](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/paddingbit) { get; } | पैडिंग बिट प्राप्त करता है. |
| [PrivateBit](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/privatebit) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि [निजी बिट]. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |

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

### उदाहरण

यह उदाहरण दर्शाता है कि एमपी3 फ़ाइल से एमपीईजी ऑडियो मेटाडेटा कैसे पढ़ा जाए।

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    Console.WriteLine(root.MpegAudioPackage.Bitrate);
    Console.WriteLine(root.MpegAudioPackage.ChannelMode);
    Console.WriteLine(root.MpegAudioPackage.Emphasis);
    Console.WriteLine(root.MpegAudioPackage.Frequency);
    Console.WriteLine(root.MpegAudioPackage.HeaderPosition);
    Console.WriteLine(root.MpegAudioPackage.Layer);

    // ...
}
```

### यह सभी देखें

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Mpeg](../../groupdocs.metadata.formats.mpeg)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
