---
title: MatroskaEbmlHeader
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: Matroska वडय में ईबएमएल हेडर मेटडेट क प्रतनधत्व करत है
type: docs
weight: 2460
url: /hi/net/groupdocs.metadata.formats.video/matroskaebmlheader/
---
## MatroskaEbmlHeader class

Matroska वीडियो में ईबीएमएल हेडर मेटाडेटा का प्रतिनिधित्व करता है।

```csharp
public class MatroskaEbmlHeader : MatroskaBasePackage
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [DocType](../../groupdocs.metadata.formats.video/matroskaebmlheader/doctype) { get; } | फ़ाइल की सामग्री प्राप्त करता है। MATROSKA फ़ाइल के मामले में, इसका मान 'matroska' है. |
| [DocTypeReadVersion](../../groupdocs.metadata.formats.video/matroskaebmlheader/doctypereadversion) { get; } | न्यूनतम संस्करण संख्या प्राप्त करता है[`DocType`](./doctype) फ़ाइल को पढ़ने के लिए पार्सर का अनुपालन होना चाहिए. |
| [DocTypeVersion](../../groupdocs.metadata.formats.video/matroskaebmlheader/doctypeversion) { get; } | का संस्करण प्राप्त करता है[`DocType`](./doctype) लेखक फ़ाइल बनाने के लिए प्रयोग किया जाता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [ReadVersion](../../groupdocs.metadata.formats.video/matroskaebmlheader/readversion) { get; } | फ़ाइल को पढ़ने में सक्षम होने के लिए ईबीएमएल पार्सर के लिए आवश्यक न्यूनतम संस्करण प्राप्त करता है। |
| [Version](../../groupdocs.metadata.formats.video/matroskaebmlheader/version) { get; } | ईबीएमएल राइटर का संस्करण प्राप्त करता है जिसका उपयोग फ़ाइल बनाने के लिए किया गया है। |

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

* class [MatroskaBasePackage](../matroskabasepackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->