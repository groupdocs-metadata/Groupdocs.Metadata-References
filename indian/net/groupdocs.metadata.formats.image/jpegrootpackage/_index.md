---
title: JpegRootPackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: जेपईज छव में मेटडेट के सथ कम करने क इजजत देने वले रूट पैकेज क प्रतनधत्व करत है
type: docs
weight: 1810
url: /hi/net/groupdocs.metadata.formats.image/jpegrootpackage/
---
## JpegRootPackage class

जेपीईजी छवि में मेटाडेटा के साथ काम करने की इजाजत देने वाले रूट पैकेज का प्रतिनिधित्व करता है।

```csharp
public class JpegRootPackage : ImageRootPackage, IExif, IIptc, IXmp
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [ExifPackage](../../groupdocs.metadata.formats.image/jpegrootpackage/exifpackage) { get; set; } | EXIF मेटाडेटा पैकेज प्राप्त या सेट करता है। |
| [FileType](../../groupdocs.metadata.formats.image/imagerootpackage/filetype) { get; } | फ़ाइल प्रकार मेटाडेटा पैकेज प्राप्त करता है। (2 properties) |
| [ImageResourcePackage](../../groupdocs.metadata.formats.image/jpegrootpackage/imageresourcepackage) { get; } | फोटोशॉप इमेज रिसोर्स मेटाडेटा पैकेज प्राप्त करता है। इमेज रिसोर्स ब्लॉक फोटोशॉप नेटिव फाइल फॉर्मेट की मूल बिल्डिंग यूनिट हैं। |
| [IptcPackage](../../groupdocs.metadata.formats.image/jpegrootpackage/iptcpackage) { get; set; } | IPTC मेटाडेटा पैकेज प्राप्त या सेट करता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [MakerNotePackage](../../groupdocs.metadata.formats.image/jpegrootpackage/makernotepackage) { get; } | मेकरनोट मेटाडेटा पैकेज प्राप्त या सेट करता है। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [XmpPackage](../../groupdocs.metadata.formats.image/jpegrootpackage/xmppackage) { get; set; } | एक्सएमपी मेटाडेटा पैकेज प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को जोड़ता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | निर्धारित करता है कि पैकेज में निर्दिष्ट नाम के साथ मेटाडेटा गुण है या नहीं। |
| [DetectBarcodeTypes](../../groupdocs.metadata.formats.image/jpegrootpackage/detectbarcodetypes)() | छवि में प्रस्तुत बारकोड के प्रकारों को निकालता है। |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को संतुष्ट करने वाले मेटाडेटा गुणों को ढूँढता है। खोज पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करती है। |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृति करता है। |
| [RemoveImageResourcePackage](../../groupdocs.metadata.formats.image/jpegrootpackage/removeimageresourcepackage)() | फोटोशॉप इमेज रिसोर्स मेटाडेटा पैकेज को हटाता है। |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को पूरा करने वाले मेटाडेटा गुणों को हटाता है। |
| override [Sanitize](../../groupdocs.metadata.formats.image/jpegrootpackage/sanitize)() | पैकेज से लिखने योग्य मेटाडेटा गुणों को हटाता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को सेट करता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। यह विधि एक संयोजन है[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) और[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) यदि कोई मौजूदा संपत्ति विधेय को संतुष्ट करती है तो उसका मान अपडेट किया जाता है। यदि पैकेज में कोई ज्ञात संपत्ति गायब है जो विधेय को संतुष्ट करती है तो इसे पैकेज में जोड़ा जाता है। |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | अद्यतन ज्ञात मेटाडेटा गुण निर्दिष्ट विधेय को संतुष्ट करते हैं। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |

### टिप्पणियों

**और अधिक जानें**

* [जेपीईजी छवियों में मेटाडेटा के साथ कार्य करना](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG+images)
* [EXIF मेटाडेटा के साथ काम करना](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)
* [XMP मेटाडेटा के साथ काम करना](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)
* [IPTC IIM मेटाडेटा के साथ कार्य करना](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### यह सभी देखें

* class [ImageRootPackage](../imagerootpackage)
* interface [IExif](../../groupdocs.metadata.standards.exif/iexif)
* interface [IIptc](../../groupdocs.metadata.standards.iptc/iiptc)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* नाम स्थान [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
