---
title: MatroskaSegment
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: एक Matroska वडय में SEGMENTINFO तत्व क प्रतनधत्व करत है जसमें SEGMENT के बरे में समन्य जनकर हत है
type: docs
weight: 2490
url: /hi/net/groupdocs.metadata.formats.video/matroskasegment/
---
## MatroskaSegment class

एक Matroska वीडियो में SEGMENTINFO तत्व का प्रतिनिधित्व करता है जिसमें SEGMENT के बारे में सामान्य जानकारी होती है।

```csharp
public class MatroskaSegment : MatroskaBasePackage
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [DateUtc](../../groupdocs.metadata.formats.video/matroskasegment/dateutc) { get; } | वह दिनांक और समय प्राप्त करता है जब सेगमेंट मक्सिंग एप्लिकेशन या लाइब्रेरी द्वारा बनाया गया था। |
| [Duration](../../groupdocs.metadata.formats.video/matroskasegment/duration) { get; } | सेगमेंट की अवधि प्राप्त करता है। कृपया देखें[`TimecodeScale`](./timecodescale) अधिक जानकारी के लिए. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [MuxingApp](../../groupdocs.metadata.formats.video/matroskasegment/muxingapp) { get; } | एप्लिकेशन या लाइब्रेरी का पूरा नाम प्राप्त करता है जिसके बाद संस्करण संख्या होती है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [ScaledDuration](../../groupdocs.metadata.formats.video/matroskasegment/scaledduration) { get; } | सेगमेंट की स्केल की गई अवधि प्राप्त करता है। |
| [SegmentFilename](../../groupdocs.metadata.formats.video/matroskasegment/segmentfilename) { get; } | इस सेगमेंट से संबंधित फ़ाइल नाम प्राप्त करता है। |
| [SegmentUid](../../groupdocs.metadata.formats.video/matroskasegment/segmentuid) { get; } | एक सेगमेंट की पहचान करने वाला अद्वितीय 128 बिट नंबर प्राप्त करता है। जाहिर है, एक फ़ाइल को केवल दूसरी फ़ाइल द्वारा संदर्भित किया जा सकता है यदि कोई SEGMENTUID मौजूद है, हालांकि, उस यूआईडी के बिना प्लेबैक संभव है। |
| [TimecodeScale](../../groupdocs.metadata.formats.video/matroskasegment/timecodescale) { get; } | टाइमकोड स्केल मान प्राप्त करता है। नैनोसेकंड में टाइमकोड प्राप्त करने के लिए MATROSKA फ़ाइल में प्रत्येक स्केल किए गए टाइमकोड को TIMECODESCALE से गुणा किया जाता है। ध्यान दें कि सभी टाइमकोड स्केल नहीं किए जाते हैं! |
| [Title](../../groupdocs.metadata.formats.video/matroskasegment/title) { get; } | सेगमेंट का सामान्य नाम प्राप्त करता है। |
| [WritingApp](../../groupdocs.metadata.formats.video/matroskasegment/writingapp) { get; } | एप्लिकेशन का पूरा नाम प्राप्त करता है जिसके बाद संस्करण संख्या होती है। |

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

* [Matroska (MKV) फ़ाइलों में मेटाडेटा के साथ कार्य करना](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### यह सभी देखें

* class [MatroskaBasePackage](../matroskabasepackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
