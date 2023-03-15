---
title: XmpResourceRef
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: एक संसधन के लए एक बहु भग संदर्भ क प्रतनधत्व करत है पछले संस्करणं प्रतपदन के मूल व्युत्पन्न दस्तवेजं के लए मूल और इस तरह आगे इंगत करने के लए उपयग कय जत है
type: docs
weight: 3550
url: /hi/net/groupdocs.metadata.standards.xmp/xmpresourceref/
---
## XmpResourceRef class

एक संसाधन के लिए एक बहु भाग संदर्भ का प्रतिनिधित्व करता है। पिछले संस्करणों, प्रतिपादन के मूल, व्युत्पन्न दस्तावेजों के लिए मूल, और इसी तरह आगे इंगित करने के लिए उपयोग किया जाता है।

```csharp
public sealed class XmpResourceRef : XmpComplexType
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [XmpResourceRef](xmpresourceref)() | का एक नया उदाहरण प्रारंभ करता है[`XmpResourceRef`](../xmpresourceref) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternatePaths](../../groupdocs.metadata.standards.xmp/xmpresourceref/alternatepaths) { get; set; } | संदर्भित संसाधन के फ़ॉलबैक फ़ाइल पथ या URL प्राप्त या सेट करता है। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [DocumentID](../../groupdocs.metadata.standards.xmp/xmpresourceref/documentid) { get; set; } | संदर्भित संसाधन से xmpMM:DocumentID गुण का मान प्राप्त या सेट करता है। |
| [FilePath](../../groupdocs.metadata.standards.xmp/xmpresourceref/filepath) { get; set; } | संदर्भित संसाधन के फ़ाइल पथ या URL को प्राप्त या सेट करता है। |
| [InstanceID](../../groupdocs.metadata.standards.xmp/xmpresourceref/instanceid) { get; set; } | संदर्भित संसाधन से xmpMM:InstanceID गुण का मान प्राप्त या सेट करता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [LastModifyDate](../../groupdocs.metadata.standards.xmp/xmpresourceref/lastmodifydate) { get; set; } | stEvt का मान प्राप्त या सेट करता है: जब पिछली बार फ़ाइल लिखी गई थी। |
| [Manager](../../groupdocs.metadata.standards.xmp/xmpresourceref/manager) { get; set; } | संदर्भित संसाधन के xmpMM को प्राप्त या सेट करता है: प्रबंधक। |
| [ManagerVariant](../../groupdocs.metadata.standards.xmp/xmpresourceref/managervariant) { get; set; } | संदर्भित संसाधन के xmpMM को प्राप्त या सेट करता है: प्रबंधक। |
| [ManageTo](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageto) { get; set; } | संदर्भित संसाधन के xmpMM:ManageTo को प्राप्त या सेट करता है। |
| [ManageUI](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageui) { get; set; } | संदर्भित संसाधन के xmpMM को प्राप्त या सेट करता है:ManageUI. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | में उपयोग किए जाने वाले नामस्थान यूआरआई प्राप्त करता है[`XmpComplexType`](../xmpcomplextype) उदाहरण. |
| [PartMapping](../../groupdocs.metadata.standards.xmp/xmpresourceref/partmapping) { get; set; } | मैपिंग फ़ंक्शन का नाम या यूआरआई प्राप्त करता है या सेट करता है जिसका उपयोग पार्ट से पार्ट तक मैप करने के लिए किया जाता है। |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | में उपयोग किए जाने वाले नामस्थान उपसर्ग प्राप्त करता है[`XmpComplexType`](../xmpcomplextype) उदाहरण. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [RenditionClass](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionclass) { get; set; } | संदर्भित संसाधन से xmpMM:RenditionClass गुण का मान प्राप्त या सेट करता है। |
| [RenditionParams](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionparams) { get; set; } | संदर्भित संसाधन से xmpMM:RenditionParams संपत्ति का मान प्राप्त या सेट करता है। |
| [VersionID](../../groupdocs.metadata.standards.xmp/xmpresourceref/versionid) { get; set; } | संदर्भित संसाधन से xmpMM:RenditionParams संपत्ति का मान प्राप्त या सेट करता है। |

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
