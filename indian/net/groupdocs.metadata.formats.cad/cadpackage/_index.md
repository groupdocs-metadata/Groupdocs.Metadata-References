---
title: CadPackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: सएड कंप्यूटर एडेड डजइन मेटडेट क प्रतनधत्व करत है
type: docs
weight: 840
url: /hi/net/groupdocs.metadata.formats.cad/cadpackage/
---
## CadPackage class

सीएडी (कंप्यूटर एडेड डिजाइन) मेटाडेटा का प्रतिनिधित्व करता है।

```csharp
public sealed class CadPackage : CustomPackage
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AcadVersion](../../groupdocs.metadata.formats.cad/cadpackage/acadversion) { get; } | ऑटोकैड आरेखण डेटाबेस संस्करण संख्या प्राप्त करता है। |
| [Author](../../groupdocs.metadata.formats.cad/cadpackage/author) { get; } | ड्राइंग लेखक प्राप्त करता है। |
| [Comments](../../groupdocs.metadata.formats.cad/cadpackage/comments) { get; } | उपयोगकर्ता टिप्पणियां प्राप्त करता है। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [CreatedDateTime](../../groupdocs.metadata.formats.cad/cadpackage/createddatetime) { get; } | वह दिनांक और समय प्राप्त करता है जब आरेखण बनाया गया था. |
| [CustomProperties](../../groupdocs.metadata.formats.cad/cadpackage/customproperties) { get; } | कस्टम मेटाडेटा गुणों वाला पैकेज प्राप्त करता है। |
| [Height](../../groupdocs.metadata.formats.cad/cadpackage/height) { get; } | ड्राइंग ऊंचाई प्राप्त करता है। |
| [HyperlinkBase](../../groupdocs.metadata.formats.cad/cadpackage/hyperlinkbase) { get; } | हाइपरलिंक आधार प्राप्त करता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [Keywords](../../groupdocs.metadata.formats.cad/cadpackage/keywords) { get; } | कीवर्ड प्राप्त करता है। |
| [LastSavedBy](../../groupdocs.metadata.formats.cad/cadpackage/lastsavedby) { get; } | अंतिम संपादक का नाम प्राप्त करता है। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [ModifiedDateTime](../../groupdocs.metadata.formats.cad/cadpackage/modifieddatetime) { get; } | वह दिनांक और समय प्राप्त करता है जब आरेखण संशोधित किया गया था। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [RevisionNumber](../../groupdocs.metadata.formats.cad/cadpackage/revisionnumber) { get; } | संशोधन संख्या प्राप्त करता है। |
| [Subject](../../groupdocs.metadata.formats.cad/cadpackage/subject) { get; } | विषय प्राप्त करता है। |
| [Title](../../groupdocs.metadata.formats.cad/cadpackage/title) { get; } | शीर्षक प्राप्त करता है। |
| [Width](../../groupdocs.metadata.formats.cad/cadpackage/width) { get; } | आरेखण चौड़ाई प्राप्त करता है. |

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

* [सीएडी मेटाडेटा के साथ काम करना](https://docs.groupdocs.com/display/metadatanet/Working+with+CAD+metadata)

### यह सभी देखें

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Cad](../../groupdocs.metadata.formats.cad)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
