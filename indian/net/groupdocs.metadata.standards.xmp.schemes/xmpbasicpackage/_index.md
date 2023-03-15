---
title: XmpBasicPackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: XMP मूल नमस्थन क प्रतनधत्व करत है
type: docs
weight: 3090
url: /hi/net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/
---
## XmpBasicPackage class

XMP मूल नामस्थान का प्रतिनिधित्व करता है।

```csharp
public sealed class XmpBasicPackage : XmpPackage
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [XmpBasicPackage](xmpbasicpackage)() | का एक नया उदाहरण प्रारंभ करता है[`XmpBasicPackage`](../xmpbasicpackage) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [BaseUrl](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/baseurl) { get; set; } | दस्तावेज़ सामग्री में सापेक्ष URL के लिए आधार URL प्राप्त या सेट करता है। यदि इस दस्तावेज़ में इंटरनेट लिंक हैं, और वे लिंक सापेक्ष हैं, तो वे इस आधार URL के सापेक्ष हैं। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [CreateDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/createdate) { get; set; } | संसाधन बनाए जाने की तिथि और समय प्राप्त या सेट करता है। |
| [CreatorTool](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/creatortool) { get; set; } | संसाधन बनाने के लिए उपयोग किए जाने वाले टूल का नाम प्राप्त या सेट करता है। |
| [Identifiers](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/identifiers) { get; set; } | टेक्स्ट स्ट्रिंग्स की एक अनियंत्रित सरणी प्राप्त या सेट करता है जो किसी दिए गए संदर्भ में स्पष्ट रूप से संसाधन की पहचान करता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [Label](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/label) { get; set; } | एक शब्द या छोटा वाक्यांश प्राप्त या सेट करता है जो उपयोगकर्ता परिभाषित संग्रह के सदस्य के रूप में संसाधन की पहचान करता है। |
| [MetadataDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/metadatadate) { get; set; } | वह दिनांक और समय प्राप्त या सेट करता है जब इस संसाधन के लिए कोई मेटाडेटा पिछली बार बदला गया था। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [ModifyDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/modifydate) { get; set; } | वह दिनांक और समय प्राप्त या सेट करता है जब संसाधन को अंतिम बार संशोधित किया गया था। |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | नाम स्थान URI प्राप्त करता है. |
| [Nickname](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/nickname) { get; set; } | संसाधन के लिए एक छोटा अनौपचारिक नाम प्राप्त या सेट करता है। |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | xmlns उपसर्ग प्राप्त करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [Rating](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/rating) { get; set; } | इस फ़ाइल के लिए उपयोगकर्ता द्वारा निर्दिष्ट रेटिंग प्राप्त या सेट करता है। मान -1 या श्रेणी [0..5] में होगा, जहां -1 "अस्वीकृत" इंगित करता है और 0 "अनरेटेड" इंगित करता है। |
| [Thumbnails](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/thumbnails) { get; set; } | फ़ाइल के लिए थंबनेल छवियों की एक सरणी प्राप्त या सेट करता है, जो आकार या छवि एन्कोडिंग जैसी विशेषताओं में भिन्न हो सकती है। |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | एक्सएमएल नेमस्पेस प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को जोड़ता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | सभी XMP गुण निकालता है. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | निर्धारित करता है कि पैकेज में निर्दिष्ट नाम के साथ मेटाडेटा गुण है या नहीं। |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को संतुष्ट करने वाले मेटाडेटा गुणों को ढूँढता है। खोज पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करती है। |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृति करता है। |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | XMP मान को XML प्रतिनिधित्व में कनवर्ट करता है। |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | संपत्ति को निर्दिष्ट नाम से हटाता है। |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को पूरा करने वाले मेटाडेटा गुणों को हटाता है। |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | पैकेज से लिखने योग्य मेटाडेटा गुणों को हटाता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | बूलियन संपत्ति सेट करता है। |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | सेटDateTime संपत्ति. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | डबल संपत्ति सेट करता है। |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | पूर्णांक संपत्ति सेट करता है। |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/set#set_7)(string, string) | स्ट्रिंग गुण जोड़ता है. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | से विरासत में मिला मान सेट करता है[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | से विरासत में मिला मान सेट करता है[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | से विरासत में मिला मान सेट करता है[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को सेट करता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। यह विधि एक संयोजन है[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) और[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) यदि कोई मौजूदा संपत्ति विधेय को संतुष्ट करती है तो उसका मान अपडेट किया जाता है। यदि पैकेज में कोई ज्ञात संपत्ति गायब है जो विधेय को संतुष्ट करती है तो इसे पैकेज में जोड़ा जाता है। |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | अद्यतन ज्ञात मेटाडेटा गुण निर्दिष्ट विधेय को संतुष्ट करते हैं। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |

## खेत

| नाम | विवरण |
| --- | --- |
| const [RatingMax](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingmax) | रेटिंग अधिकतम मान. |
| const [RatingMin](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingmin) | रेटिंग न्यूनतम मान. |
| const [RatingRejected](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingrejected) | रेटिंग अस्वीकृत मान. |

### यह सभी देखें

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* नाम स्थान [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
