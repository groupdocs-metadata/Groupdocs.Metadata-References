---
title: PsdCompressionMethod
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: छव डेट के लए उपयग क जने वल संपड़न वध क परभषत करत है
type: docs
weight: 1890
url: /hi/net/groupdocs.metadata.formats.image/psdcompressionmethod/
---
## PsdCompressionMethod enumeration

छवि डेटा के लिए उपयोग की जाने वाली संपीड़न विधि को परिभाषित करता है।

```csharp
public enum PsdCompressionMethod
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| Raw | `0` | कोई संपीड़न नहीं। आरजीबीए प्लानर ऑर्डर में कच्चे बाइट्स के रूप में संग्रहीत छवि डेटा। इसका मतलब है कि पहले सभी आर डेटा लिखे गए हैं, फिर सभी जी लिखे गए हैं, फिर सभी बी और अंत में सभी ए डेटा लिखे गए हैं। |
| Rle | `1` | RLE संकुचित। छवि डेटा सभी स्कैन लाइनों (पंक्तियों * चैनलों) के लिए बाइट की संख्या से शुरू होता है, प्रत्येक गिनती को दो-बाइट मान के रूप में संग्रहीत किया जाता है। RLE कंप्रेस्ड डेटा अनुसरण करता है, प्रत्येक स्कैन लाइन के साथ अलग से कम्प्रेस किया जाता है। |
| ZipWithoutPrediction | `2` | ज़िप बिना भविष्यवाणी के। |
| ZipWithPrediction | `3` | भविष्यवाणी के साथ ज़िप। |

### यह सभी देखें

* नाम स्थान [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
