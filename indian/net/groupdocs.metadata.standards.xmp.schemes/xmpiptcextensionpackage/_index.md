---
title: XmpIptcExtensionPackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: IPTC एक्सटेंशन XMP पैकेज क प्रतनधत्व करत है
type: docs
weight: 3150
url: /hi/net/groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/
---
## XmpIptcExtensionPackage class

IPTC एक्सटेंशन XMP पैकेज का प्रतिनिधित्व करता है।

```csharp
public sealed class XmpIptcExtensionPackage : XmpPackage
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [XmpIptcExtensionPackage](xmpiptcextensionpackage)() | का एक नया उदाहरण प्रारंभ करता है[`XmpIptcExtensionPackage`](../xmpiptcextensionpackage) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [AdditionalModelInformation](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/additionalmodelinformation) { get; set; } | मॉडल द्वारा जारी छवि में जातीयता और मॉडल के अन्य पहलुओं के बारे में जानकारी प्राप्त या सेट करता है। |
| [AgesOfModels](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/agesofmodels) { get; set; } | उस समय मानव मॉडल की आयु प्राप्त या सेट करता है जब यह छवि एक मॉडल जारी की गई छवि में ली गई थी। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [DigitalImageGuid](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/digitalimageguid) { get; set; } | इस डिजिटल छवि के लिए विश्व स्तर पर विशिष्ट पहचानकर्ता प्राप्त या सेट करता है। |
| [DigitalSourceType](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/digitalsourcetype) { get; set; } | इस डिजिटल छवि के स्रोत का प्रकार प्राप्त या सेट करता है। |
| [Event](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/event) { get; set; } | उस विशिष्ट घटना का विवरण प्राप्त या सेट करता है जिसमें फोटो लिया गया था। |
| [IptcLastEdited](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/iptclastedited) { get; set; } | किसी भी IPTC फोटो मेटाडेटा फ़ील्ड को अंतिम बार संपादित किए जाने पर दिनांक और वैकल्पिक रूप से समय प्राप्त या सेट करता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [MaxAvailableHeight](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/maxavailableheight) { get; set; } | उस मूल फ़ोटो के पिक्सेल में अधिकतम उपलब्ध ऊंचाई प्राप्त या सेट करता है जिससे यह फ़ोटो डाउनसाइज़ करके प्राप्त की गई है। |
| [MaxAvailableWidth](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/maxavailablewidth) { get; set; } | मूल फ़ोटो के पिक्सेल में अधिकतम उपलब्ध चौड़ाई प्राप्त करता है या सेट करता है जिससे यह फ़ोटो डाउनसाइज़ करके प्राप्त की गई है। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | नाम स्थान URI प्राप्त करता है. |
| [OrganisationInImageCodes](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/organisationinimagecodes) { get; set; } | उन संगठनों या कंपनियों की पहचान करने के लिए एक नियंत्रित शब्दावली से कोड प्राप्त या सेट करता है जो छवि में दिखाए गए हैं। |
| [OrganisationInImageNames](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/organisationinimagenames) { get; set; } | छवि में दिखाए गए संगठनों या कंपनियों के नाम प्राप्त या सेट करता है। |
| [PersonsInImage](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/personsinimage) { get; set; } | उन व्यक्तियों के नाम प्राप्त या सेट करता है जिनके बारे में आइटम की सामग्री है। |
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
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/set#set_7)(string, string) | स्ट्रिंग गुण सेट करता है। |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/set#set_2)(string, XmpArray) | से विरासत में मिला मान सेट करता है[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | से विरासत में मिला मान सेट करता है[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | से विरासत में मिला मान सेट करता है[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को सेट करता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। यह विधि एक संयोजन है[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) और[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) यदि कोई मौजूदा संपत्ति विधेय को संतुष्ट करती है तो उसका मान अपडेट किया जाता है। यदि पैकेज में कोई ज्ञात संपत्ति गायब है जो विधेय को संतुष्ट करती है तो इसे पैकेज में जोड़ा जाता है। |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | अद्यतन ज्ञात मेटाडेटा गुण निर्दिष्ट विधेय को संतुष्ट करते हैं। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |

### यह सभी देखें

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* नाम स्थान [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
