---
title: MatroskaVideoTrack
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: Matroska वडय में वडय मेटडेट क प्रतनधत्व करत है
type: docs
weight: 2610
url: /hi/net/groupdocs.metadata.formats.video/matroskavideotrack/
---
## MatroskaVideoTrack class

Matroska वीडियो में वीडियो मेटाडेटा का प्रतिनिधित्व करता है।

```csharp
public class MatroskaVideoTrack : MatroskaTrack
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlphaMode](../../groupdocs.metadata.formats.video/matroskavideotrack/alphamode) { get; } | अल्फ़ा वीडियो मोड प्राप्त करता है। इस तत्व की उपस्थिति इंगित करती है कि ब्लॉक अतिरिक्त तत्व में अल्फा डेटा हो सकता है। |
| [CodecID](../../groupdocs.metadata.formats.video/matroskatrack/codecid) { get; } | कोडेक से संबंधित एक आईडी प्राप्त करता है। |
| [CodecName](../../groupdocs.metadata.formats.video/matroskatrack/codecname) { get; } | कोडेक निर्दिष्ट करते हुए मानव-पठनीय स्ट्रिंग प्राप्त करता है. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [DefaultDuration](../../groupdocs.metadata.formats.video/matroskatrack/defaultduration) { get; } | नैनोसेकंड की संख्या प्राप्त करता है (के माध्यम से स्केल नहीं किया गया[`TimecodeScale`](../matroskasegment/timecodescale) ) प्रति फ्रेम. |
| [DisplayHeight](../../groupdocs.metadata.formats.video/matroskavideotrack/displayheight) { get; } | प्रदर्शित करने के लिए वीडियो फ़्रेम की ऊंचाई प्राप्त करता है। काटने के बाद वीडियो फ्रेम पर लागू होता है (PixelCrop* Elements)। |
| [DisplayUnit](../../groupdocs.metadata.formats.video/matroskavideotrack/displayunit) { get; } | कैसे मिलता है[`DisplayWidth`](./displaywidth) और[`DisplayHeight`](./displayheight) व्याख्या की जाती है। |
| [DisplayWidth](../../groupdocs.metadata.formats.video/matroskavideotrack/displaywidth) { get; } | प्रदर्शित करने के लिए वीडियो फ़्रेम की चौड़ाई प्राप्त करता है। काटने के बाद वीडियो फ्रेम पर लागू होता है (PixelCrop* Elements)। |
| [FieldOrder](../../groupdocs.metadata.formats.video/matroskavideotrack/fieldorder) { get; } | वीडियो के फील्ड ऑर्डरिंग की घोषणा करता है। यदि फ्लैग इंटरलेस्ड 1 पर सेट नहीं है, तो इस तत्व को अनदेखा किया जाना चाहिए। |
| [FlagEnabled](../../groupdocs.metadata.formats.video/matroskatrack/flagenabled) { get; } | सक्षम ध्वज प्राप्त करता है, यदि ट्रैक प्रयोग करने योग्य है तो सही है। |
| [FlagInterlaced](../../groupdocs.metadata.formats.video/matroskavideotrack/flaginterlaced) { get; } | यह घोषणा करने के लिए एक फ़्लैग प्राप्त करता है कि क्या वीडियो प्रगतिशील या इंटरलेस्ड होने के लिए जाना जाता है और यदि लागू हो तो इंटरलेसमेंट के बारे में विवरण घोषित करने के लिए. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [Language](../../groupdocs.metadata.formats.video/matroskatrack/language) { get; } | मैट्रोस्का भाषा के रूप में ट्रैक की भाषा प्राप्त करता है। इस तत्व को अनदेखा किया जाना चाहिए यदि[`LanguageIetf`](../matroskatrack/languageietf) समान TrackEntry में तत्व का उपयोग किया जाता है. |
| [LanguageIetf](../../groupdocs.metadata.formats.video/matroskatrack/languageietf) { get; } | BCP 47 के अनुसार और IANA भाषा सबटैग रजिस्ट्री का उपयोग करके ट्रैक की भाषा प्राप्त करता है। यदि इस Element का प्रयोग किया जाता है तो कोई भी[`Language`](../matroskatrack/language) समान TrackEntry में उपयोग किए गए तत्वों को अनदेखा किया जाना चाहिए। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [Name](../../groupdocs.metadata.formats.video/matroskatrack/name) { get; } | मानव-पठनीय ट्रैक नाम प्राप्त करता है। |
| [PixelCropBottom](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropbottom) { get; } | छवि के नीचे निकालने के लिए वीडियो पिक्सेल की संख्या प्राप्त करता है। |
| [PixelCropLeft](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropleft) { get; } | छवि के बाईं ओर निकालने के लिए वीडियो पिक्सेल की संख्या प्राप्त करता है। |
| [PixelCropRight](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropright) { get; } | छवि के दाईं ओर निकालने के लिए वीडियो पिक्सेल की संख्या प्राप्त करता है। |
| [PixelCropTop](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcroptop) { get; } | छवि के शीर्ष पर निकालने के लिए वीडियो पिक्सेल की संख्या प्राप्त करता है। |
| [PixelHeight](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelheight) { get; } | एन्कोडेड वीडियो फ़्रेम की पिक्सेल में ऊंचाई प्राप्त करता है. |
| [PixelWidth](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelwidth) { get; } | एन्कोडेड वीडियो फ़्रेम की पिक्सेल में चौड़ाई प्राप्त करता है. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [StereoMode](../../groupdocs.metadata.formats.video/matroskavideotrack/stereomode) { get; } | स्टीरियो-3डी वीडियो मोड प्राप्त करता है। |
| [TrackNumber](../../groupdocs.metadata.formats.video/matroskatrack/tracknumber) { get; } | ब्लॉक हैडर में उपयोग किए गए ट्रैक नंबर को प्राप्त करता है। 127 से अधिक ट्रैक का उपयोग करने के लिए प्रोत्साहित नहीं किया जाता है, हालांकि डिजाइन असीमित संख्या की अनुमति देता है। |
| [TrackType](../../groupdocs.metadata.formats.video/matroskatrack/tracktype) { get; } | ट्रैक का प्रकार प्राप्त करता है। |
| [TrackUid](../../groupdocs.metadata.formats.video/matroskatrack/trackuid) { get; } | ट्रैक की पहचान करने के लिए अद्वितीय आईडी प्राप्त करता है। ट्रैक की सीधी स्ट्रीम प्रतिलिपि किसी अन्य फ़ाइल में बनाते समय इसे वही रखा जाना चाहिए। |

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

* class [MatroskaTrack](../matroskatrack)
* नाम स्थान [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
