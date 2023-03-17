---
title: CmsSigner
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: सएमएस प्रतहस्तक्षरकर्त जनकर क प्रतनधत्व करत है
type: docs
weight: 3010
url: /hi/net/groupdocs.metadata.standards.pkcs/cmssigner/
---
## CmsSigner class

सीएमएस प्रति-हस्ताक्षरकर्ता जानकारी का प्रतिनिधित्व करता है।

```csharp
public class CmsSigner : CustomPackage
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [DigestAlgorithm](../../groupdocs.metadata.standards.pkcs/cmssigner/digestalgorithm) { get; } | संदेश डाइजेस्ट एल्गोरिदम और हस्ताक्षरकर्ता द्वारा उपयोग किए जाने वाले किसी भी संबंधित पैरामीटर को प्राप्त करता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [SignatureAlgorithm](../../groupdocs.metadata.standards.pkcs/cmssigner/signaturealgorithm) { get; } | डिजिटल हस्ताक्षर उत्पन्न करने के लिए हस्ताक्षरकर्ता द्वारा उपयोग किए जाने वाले हस्ताक्षर एल्गोरिथ्म और किसी भी संबद्ध पैरामीटर को प्राप्त करता है। |
| [SignatureValue](../../groupdocs.metadata.standards.pkcs/cmssigner/signaturevalue) { get; } | संदेश डाइजेस्ट और हस्ताक्षरकर्ता की निजी कुंजी का उपयोग करके डिजिटल हस्ताक्षर जनरेशन का परिणाम प्राप्त करता है. |
| [SignedAttributes](../../groupdocs.metadata.standards.pkcs/cmssigner/signedattributes) { get; } | उन विशेषताओं का संग्रह प्राप्त करता है जिन पर हस्ताक्षर किए गए हैं। |
| [SignerIdentifier](../../groupdocs.metadata.standards.pkcs/cmssigner/signeridentifier) { get; } | हस्ताक्षरकर्ता का प्रमाणपत्र प्राप्त करता है (और इस प्रकार हस्ताक्षरकर्ता की सार्वजनिक कुंजी) कच्चा डेटा। |
| [SigningTime](../../groupdocs.metadata.standards.pkcs/cmssigner/signingtime) { get; } | उस समय को प्राप्त करता है जिस पर हस्ताक्षरकर्ता (कथित तौर पर) ने हस्ताक्षर करने की प्रक्रिया की थी। |
| [UnsignedAttributes](../../groupdocs.metadata.standards.pkcs/cmssigner/unsignedattributes) { get; } | उन विशेषताओं का संग्रह प्राप्त करता है जिन पर हस्ताक्षर नहीं किए गए हैं। |

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
* नाम स्थान [GroupDocs.Metadata.Standards.Pkcs](../../groupdocs.metadata.standards.pkcs)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
