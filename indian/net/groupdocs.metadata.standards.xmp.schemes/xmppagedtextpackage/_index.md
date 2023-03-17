---
title: XmpPagedTextPackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: XMP पेजेडटेक्स्ट पैकेज क प्रतनधत्व करत है
type: docs
weight: 3180
url: /hi/net/groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/
---
## XmpPagedTextPackage class

XMP पेजेड-टेक्स्ट पैकेज का प्रतिनिधित्व करता है।

```csharp
public sealed class XmpPagedTextPackage : XmpPackage
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [XmpPagedTextPackage](xmppagedtextpackage)() | का एक नया उदाहरण प्रारंभ करता है[`XmpPagedTextPackage`](../xmppagedtextpackage) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Colorants](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/colorants) { get; set; } | दस्तावेज़ में उपयोग किए जाने वाले कलरेंट्स (स्वैचेस) की ऑर्डर की गई सरणी प्राप्त या सेट करता है (किसी भी निहित दस्तावेज़ सहित)। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [Fonts](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/fonts) { get; set; } | दस्तावेज़ में उपयोग किए जाने वाले फ़ॉन्ट्स की एक अनियंत्रित सरणी प्राप्त करता है या सेट करता है (दस्तावेज़ों में किसी भी सहित)। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [MaxPageSize](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/maxpagesize) { get; set; } | दस्तावेज़ में सबसे बड़े पृष्ठ का आकार प्राप्त या सेट करता है (दस्तावेज़ों में किसी भी सहित)। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | नाम स्थान URI प्राप्त करता है. |
| [NumberOfPages](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/numberofpages) { get; set; } | दस्तावेज़ में पृष्ठों की संख्या प्राप्त या सेट करता है। |
| [PlateNames](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/platenames) { get; set; } | दस्तावेज़ को प्रिंट करने के लिए आवश्यक प्लेट नामों की एक क्रमबद्ध सरणी प्राप्त या सेट करता है (किसी भी निहित दस्तावेज़ सहित)। |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | xmlns उपसर्ग प्राप्त करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
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
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/set#set_7)(string, string) | स्ट्रिंग गुण सेट करता है। |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/set#set_2)(string, XmpArray) | से विरासत में मिला मान सेट करता है[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | से विरासत में मिला मान सेट करता है[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | से विरासत में मिला मान सेट करता है[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को सेट करता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। यह विधि एक संयोजन है[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) और[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) यदि कोई मौजूदा संपत्ति विधेय को संतुष्ट करती है तो उसका मान अपडेट किया जाता है। यदि पैकेज में कोई ज्ञात संपत्ति गायब है जो विधेय को संतुष्ट करती है तो इसे पैकेज में जोड़ा जाता है। |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | अद्यतन ज्ञात मेटाडेटा गुण निर्दिष्ट विधेय को संतुष्ट करते हैं। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |

### यह सभी देखें

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* नाम स्थान [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
