---
title: XmpFont
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: एक संरचन जसमें दस्तवेज़ में प्रयुक्त फ़न्ट क वशेषतएं हत हैं
type: docs
weight: 3400
url: /hi/net/groupdocs.metadata.standards.xmp/xmpfont/
---
## XmpFont class

एक संरचना जिसमें दस्तावेज़ में प्रयुक्त फ़ॉन्ट की विशेषताएं होती हैं।

```csharp
public sealed class XmpFont : XmpComplexType
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [XmpFont](xmpfont#constructor)() | का एक नया उदाहरण प्रारंभ करता है[`XmpFont`](../xmpfont) वर्ग. |
| [XmpFont](xmpfont#constructor_1)(string) | का एक नया उदाहरण प्रारंभ करता है[`XmpFont`](../xmpfont) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [ChildFontFiles](../../groupdocs.metadata.standards.xmp/xmpfont/childfontfiles) { get; set; } | उन फॉन्ट के लिए फ़ाइल नामों की सूची प्राप्त या सेट करता है जो एक मिश्रित फॉन्ट बनाते हैं। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [FontFace](../../groupdocs.metadata.standards.xmp/xmpfont/fontface) { get; set; } | फॉन्ट फेस नाम प्राप्त या सेट करता है। |
| [FontFamily](../../groupdocs.metadata.standards.xmp/xmpfont/fontfamily) { get; set; } | फ़ॉन्ट पारिवारिक नाम प्राप्त या सेट करता है। |
| [FontFileName](../../groupdocs.metadata.standards.xmp/xmpfont/fontfilename) { get; set; } | फ़ॉन्ट फ़ाइल नाम प्राप्त या सेट करता है (पूर्ण पथ नहीं)। |
| [FontName](../../groupdocs.metadata.standards.xmp/xmpfont/fontname) { get; set; } | फ़ॉन्ट का पोस्टस्क्रिप्ट नाम प्राप्त या सेट करता है। |
| [FontType](../../groupdocs.metadata.standards.xmp/xmpfont/fonttype) { get; set; } | फ़ॉन्ट प्रकार प्राप्त या सेट करता है। |
| [IsComposite](../../groupdocs.metadata.standards.xmp/xmpfont/iscomposite) { get; set; } | एक मान प्राप्त या सेट करता है जो इंगित करता है कि फ़ॉन्ट समग्र है या नहीं। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | में उपयोग किए जाने वाले नामस्थान यूआरआई प्राप्त करता है[`XmpComplexType`](../xmpcomplextype) उदाहरण. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | में उपयोग किए जाने वाले नामस्थान उपसर्ग प्राप्त करता है[`XmpComplexType`](../xmpcomplextype) उदाहरण. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [Version](../../groupdocs.metadata.standards.xmp/xmpfont/version) { get; set; } | फ़ॉन्ट संस्करण प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को जोड़ता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | निर्धारित करता है कि पैकेज में निर्दिष्ट नाम के साथ मेटाडेटा गुण है या नहीं। |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को संतुष्ट करने वाले मेटाडेटा गुणों को ढूँढता है। खोज पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करती है। |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृति करता है। |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | निर्दिष्ट उपसर्ग से संबद्ध नाम स्थान URI प्राप्त करता है। |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | स्ट्रिंग में मौजूद मान को XMP फ़ॉर्मैट में लौटाता है. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को पूरा करने वाले मेटाडेटा गुणों को हटाता है। |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | पैकेज से लिखने योग्य मेटाडेटा गुणों को हटाता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को सेट करता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। यह विधि एक संयोजन है[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) और[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) यदि कोई मौजूदा संपत्ति विधेय को संतुष्ट करती है तो उसका मान अपडेट किया जाता है। यदि पैकेज में कोई ज्ञात संपत्ति गायब है जो विधेय को संतुष्ट करती है तो इसे पैकेज में जोड़ा जाता है। |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | अद्यतन ज्ञात मेटाडेटा गुण निर्दिष्ट विधेय को संतुष्ट करते हैं। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |

### यह सभी देखें

* class [XmpComplexType](../xmpcomplextype)
* नाम स्थान [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
