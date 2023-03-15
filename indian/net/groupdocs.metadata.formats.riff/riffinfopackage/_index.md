---
title: RiffInfoPackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: RIFF INFO चंक से नकले गए गुणं वले मेटडेट पैकेज क प्रतनधत्व करत है
type: docs
weight: 2220
url: /hi/net/groupdocs.metadata.formats.riff/riffinfopackage/
---
## RiffInfoPackage class

RIFF INFO चंक से निकाले गए गुणों वाले मेटाडेटा पैकेज का प्रतिनिधित्व करता है।

```csharp
public sealed class RiffInfoPackage : CustomPackage
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Artist](../../groupdocs.metadata.formats.riff/riffinfopackage/artist) { get; } | फ़ाइल के मूल विषय के कलाकार को प्राप्त करता है। |
| [Comment](../../groupdocs.metadata.formats.riff/riffinfopackage/comment) { get; } | फ़ाइल या फ़ाइल के विषय के बारे में टिप्पणी प्राप्त करता है। |
| [Copyright](../../groupdocs.metadata.formats.riff/riffinfopackage/copyright) { get; } | फ़ाइल के लिए कॉपीराइट जानकारी प्राप्त करता है। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [CreationDate](../../groupdocs.metadata.formats.riff/riffinfopackage/creationdate) { get; } | उस तारीख को प्राप्त करता है जिस पर फ़ाइल का विषय बनाया गया था। |
| [Engineer](../../groupdocs.metadata.formats.riff/riffinfopackage/engineer) { get; } | फ़ाइल पर काम करने वाले इंजीनियर का नाम मिलता है। |
| [Genre](../../groupdocs.metadata.formats.riff/riffinfopackage/genre) { get; } | मूल कार्य की शैली प्राप्त करता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [Keywords](../../groupdocs.metadata.formats.riff/riffinfopackage/keywords) { get; } | वे कीवर्ड प्राप्त करता है जो फ़ाइल या फ़ाइल के विषय को संदर्भित करते हैं। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [Name](../../groupdocs.metadata.formats.riff/riffinfopackage/name) { get; } | फ़ाइल के विषय का शीर्षक प्राप्त करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [Software](../../groupdocs.metadata.formats.riff/riffinfopackage/software) { get; } | फ़ाइल बनाने के लिए उपयोग किए जाने वाले सॉफ़्टवेयर पैकेज का नाम प्राप्त करता है। |
| [Source](../../groupdocs.metadata.formats.riff/riffinfopackage/source) { get; } | उस व्यक्ति या संगठन का नाम प्राप्त करता है जिसने फ़ाइल के मूल विषय की आपूर्ति की थी। |
| [Subject](../../groupdocs.metadata.formats.riff/riffinfopackage/subject) { get; } | फ़ाइल सामग्री का विवरण प्राप्त करता है, जैसे "सिएटल का हवाई दृश्य।" |
| [Technician](../../groupdocs.metadata.formats.riff/riffinfopackage/technician) { get; } | उस तकनीशियन को प्राप्त करता है जिसने विषय फ़ाइल को डिजिटाइज़ किया है। |

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
* नाम स्थान [GroupDocs.Metadata.Formats.Riff](../../groupdocs.metadata.formats.riff)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
