---
title: AsfVideoStreamProperty
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: ASF मडय कंटेनर में वडय स्ट्रम प्रपर्ट मेटडेट क प्रतनधत्व करत है
type: docs
weight: 2370
url: /hi/net/groupdocs.metadata.formats.video/asfvideostreamproperty/
---
## AsfVideoStreamProperty class

ASF मीडिया कंटेनर में वीडियो स्ट्रीम प्रॉपर्टी मेटाडेटा का प्रतिनिधित्व करता है।

```csharp
public class AsfVideoStreamProperty : AsfBaseStreamProperty
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternateBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/alternatebitrate) { get; } | रिसाव दर RAlt प्राप्त करता है, प्रति सेकंड बिट्स में, लीकी बकेट जिसमें स्ट्रीम का डेटा भाग बिना अतिप्रवाह के होता है, सभी ASF डेटा पैकेट ओवरहेड को छोड़कर। |
| [AverageBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagebitrate) { get; } | औसत बिटरेट प्राप्त करता है। |
| [AverageTimePerFrame](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagetimeperframe) { get; } | प्रत्येक फ्रेम की 100-नैनोसेकंड इकाइयों में मापी गई औसत समय अवधि प्राप्त करता है। |
| [Bitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/bitrate) { get; } | रिसाव दर R प्राप्त करता है, प्रति सेकंड बिट्स में, लीकी बकेट जिसमें स्ट्रीम का डेटा भाग बिना अतिप्रवाह के होता है, सभी ASF डेटा पैकेट ओवरहेड को छोड़कर। |
| [BitsPerPixels](../../groupdocs.metadata.formats.video/asfvideostreamproperty/bitsperpixels) { get; } | बिट्स प्रति पिक्सेल प्राप्त करता है। |
| [Compression](../../groupdocs.metadata.formats.video/asfvideostreamproperty/compression) { get; } | वीडियो कम्प्रेशन आईडी प्राप्त करता है. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [EndTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/endtime) { get; } | पिछले ऑब्जेक्ट की प्रस्तुति का समय और चलने की अवधि प्राप्त करता है, यह दर्शाता है कि यह डिजिटल मीडिया स्ट्रीम ASF फ़ाइल की समयरेखा के संदर्भ में कहां समाप्त होती है। |
| [Flags](../../groupdocs.metadata.formats.video/asfbasestreamproperty/flags) { get; } | झंडे प्राप्त करता है। |
| [ImageHeight](../../groupdocs.metadata.formats.video/asfvideostreamproperty/imageheight) { get; } | पिक्सेल में एन्कोडेड छवि की ऊंचाई प्राप्त करता है। |
| [ImageWidth](../../groupdocs.metadata.formats.video/asfvideostreamproperty/imagewidth) { get; } | एन्कोडेड इमेज की चौड़ाई पिक्सेल में प्राप्त करता है. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [Language](../../groupdocs.metadata.formats.video/asfbasestreamproperty/language) { get; } | स्ट्रीम भाषा प्राप्त करता है। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [StartTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/starttime) { get; } | पहले ऑब्जेक्ट की प्रस्तुति का समय प्राप्त करता है, यह दर्शाता है कि यह डिजिटल मीडिया स्ट्रीम ASF फ़ाइल की समयरेखा के संदर्भ में कहां से शुरू होती है। |
| [StreamNumber](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamnumber) { get; } | इस स्ट्रीम की संख्या प्राप्त करता है। |
| [StreamType](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamtype) { get; } | इस स्ट्रीम का प्रकार प्राप्त करता है। |

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

* [ASF फ़ाइलों में मेटाडेटा के साथ कार्य करना](https://docs.groupdocs.com/display/metadatanet/Working+with+Metadata+in+ASF+Files)

### यह सभी देखें

* class [AsfBaseStreamProperty](../asfbasestreamproperty)
* नाम स्थान [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
