---
title: XmpVersion
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: दस्तवेज़ के एक संस्करण क प्रतनधत्व करत है
type: docs
weight: 3630
url: /hi/net/groupdocs.metadata.standards.xmp/xmpversion/
---
## XmpVersion class

दस्तावेज़ के एक संस्करण का प्रतिनिधित्व करता है।

```csharp
public sealed class XmpVersion : XmpComplexType
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [XmpVersion](xmpversion)() | का एक नया उदाहरण प्रारंभ करता है[`XmpVersion`](../xmpversion) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Comments](../../groupdocs.metadata.standards.xmp/xmpversion/comments) { get; set; } | जो बदला गया था उससे संबंधित टिप्पणियों को प्राप्त या सेट करता है। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [Event](../../groupdocs.metadata.standards.xmp/xmpversion/event) { get; set; } | उपयोगकर्ता द्वारा किए गए ऑपरेशन का उच्च-स्तरीय, औपचारिक विवरण प्राप्त या सेट करता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [Modifier](../../groupdocs.metadata.standards.xmp/xmpversion/modifier) { get; set; } | इस संस्करण को संशोधित करने वाले व्यक्ति को प्राप्त या सेट करता है। |
| [ModifyDate](../../groupdocs.metadata.standards.xmp/xmpversion/modifydate) { get; set; } | उस तिथि को प्राप्त या सेट करता है जिस पर इस संस्करण को चेक इन किया गया था। |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | में उपयोग किए जाने वाले नामस्थान यूआरआई प्राप्त करता है[`XmpComplexType`](../xmpcomplextype) उदाहरण. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | में उपयोग किए जाने वाले नामस्थान उपसर्ग प्राप्त करता है[`XmpComplexType`](../xmpcomplextype) उदाहरण. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [VersionNumber](../../groupdocs.metadata.standards.xmp/xmpversion/versionnumber) { get; set; } | नया संस्करण संख्या प्राप्त या सेट करता है। |

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
