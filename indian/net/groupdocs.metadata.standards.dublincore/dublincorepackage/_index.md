---
title: DublinCorePackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: डबलन कर मेटडेट पैकेज क प्रतनधत्व करत है
type: docs
weight: 2730
url: /hi/net/groupdocs.metadata.standards.dublincore/dublincorepackage/
---
## DublinCorePackage class

डबलिन कोर मेटाडेटा पैकेज का प्रतिनिधित्व करता है।

```csharp
public sealed class DublinCorePackage : CustomPackage
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Contributor](../../groupdocs.metadata.standards.dublincore/dublincorepackage/contributor) { get; } | योगदानकर्ता डबलिन कोर तत्व प्राप्त करता है। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [Coverage](../../groupdocs.metadata.standards.dublincore/dublincorepackage/coverage) { get; } | कवरेज डबलिन कोर तत्व प्राप्त करता है। |
| [Creator](../../groupdocs.metadata.standards.dublincore/dublincorepackage/creator) { get; } | निर्माता डबलिन कोर तत्व प्राप्त करता है। |
| [Date](../../groupdocs.metadata.standards.dublincore/dublincorepackage/date) { get; } | दिनांक डबलिन कोर तत्व प्राप्त करता है। |
| [Description](../../groupdocs.metadata.standards.dublincore/dublincorepackage/description) { get; } | विवरण डबलिन कोर तत्व प्राप्त करता है। |
| [Format](../../groupdocs.metadata.standards.dublincore/dublincorepackage/format) { get; } | प्रारूप डबलिन कोर तत्व प्राप्त करता है। |
| [Identifier](../../groupdocs.metadata.standards.dublincore/dublincorepackage/identifier) { get; } | पहचानकर्ता डबलिन कोर तत्व प्राप्त करता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [Language](../../groupdocs.metadata.standards.dublincore/dublincorepackage/language) { get; } | भाषा डबलिन कोर तत्व प्राप्त करता है। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [Publisher](../../groupdocs.metadata.standards.dublincore/dublincorepackage/publisher) { get; } | प्रकाशक डबलिन कोर तत्व प्राप्त करता है। |
| [Relation](../../groupdocs.metadata.standards.dublincore/dublincorepackage/relation) { get; } | संबंध डबलिन कोर तत्व प्राप्त करता है। |
| [Rights](../../groupdocs.metadata.standards.dublincore/dublincorepackage/rights) { get; } | अधिकार डबलिन कोर तत्व प्राप्त करता है। |
| [Source](../../groupdocs.metadata.standards.dublincore/dublincorepackage/source) { get; } | स्रोत डबलिन कोर तत्व प्राप्त करता है। |
| [Subject](../../groupdocs.metadata.standards.dublincore/dublincorepackage/subject) { get; } | विषय डबलिन कोर तत्व प्राप्त करता है। |
| [Title](../../groupdocs.metadata.standards.dublincore/dublincorepackage/title) { get; } | शीर्षक डबलिन कोर तत्व प्राप्त करता है। |
| [Type](../../groupdocs.metadata.standards.dublincore/dublincorepackage/type) { get; } | प्रकार डबलिन कोर तत्व प्राप्त करता है। |

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

### यह सभी देखें

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* नाम स्थान [GroupDocs.Metadata.Standards.DublinCore](../../groupdocs.metadata.standards.dublincore)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
