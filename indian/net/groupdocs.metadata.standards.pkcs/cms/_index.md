---
title: Cms
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: क्रप्टग्रफ़क मैसेज संटैक्स CMS के सथ बनए गए डजटल चह्न क प्रतनधत्व करत है  क्रप्टग्रफ़क रूप से संरक्षत संदेशं के लए IETF क मनक सएमएस आरएफस 5652 में नर्दष्ट पकेसएस 7 के संटैक्स पर आधरत है कृपय देखेंhttps//tools.ietf.org/html/rfc5652https//tools.ietf.org/html/rfc5652 अधक जनकर के लए.
type: docs
weight: 2960
url: /hi/net/groupdocs.metadata.standards.pkcs/cms/
---
## Cms class

क्रिप्टोग्राफ़िक मैसेज सिंटैक्स (CMS) के साथ बनाए गए डिजिटल चिह्न का प्रतिनिधित्व करता है - क्रिप्टोग्राफ़िक रूप से संरक्षित संदेशों के लिए IETF का मानक। सीएमएस आरएफसी 5652 में निर्दिष्ट पीकेसीएस #7 के सिंटैक्स पर आधारित है। कृपया देखें[https://tools.ietf.org/html/rfc5652](https://tools.ietf.org/html/rfc5652) अधिक जानकारी के लिए.

```csharp
public class Cms : DigitalSignature
```

## गुण

| नाम | विवरण |
| --- | --- |
| [CertificateRawData](../../groupdocs.metadata.standards.signing/digitalsignature/certificaterawdata) { get; } | प्रमाणपत्र कच्चा डेटा प्राप्त करता है। |
| [Certificates](../../groupdocs.metadata.standards.pkcs/cms/certificates) { get; } | प्रमाणपत्रों का संग्रह प्राप्त करता है। |
| [CertificateSubject](../../groupdocs.metadata.standards.signing/digitalsignature/certificatesubject) { get; } | एक प्रमाण पत्र से विषय विशिष्ट नाम प्राप्त करता है। |
| [Comments](../../groupdocs.metadata.standards.signing/digitalsignature/comments) { get; } | हस्ताक्षर उद्देश्य टिप्पणी प्राप्त करता है। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [DigestAlgorithms](../../groupdocs.metadata.standards.pkcs/cms/digestalgorithms) { get; } | संदेश-डाइजेस्ट एल्गोरिथम पहचानकर्ताओं की सरणी प्राप्त करता है। संग्रह में शून्य सहित कई तत्व हो सकते हैं। |
| [EncapsulatedContent](../../groupdocs.metadata.standards.pkcs/cms/encapsulatedcontent) { get; } | हस्ताक्षरित सामग्री प्राप्त करता है, जिसमें सामग्री प्रकार पहचानकर्ता और स्वयं सामग्री शामिल होती है। |
| virtual [IsValid](../../groupdocs.metadata.standards.signing/digitalsignature/isvalid) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि हस्ताक्षर वैध है या नहीं। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [Signers](../../groupdocs.metadata.standards.pkcs/cms/signers) { get; } | प्रति-हस्ताक्षरकर्ता सूचना पैकेज का संग्रह प्राप्त करता है। |
| override [SignTime](../../groupdocs.metadata.standards.pkcs/cms/signtime) { get; } | उस समय को प्राप्त करता है जिस पर हस्ताक्षरकर्ता (कथित तौर पर) ने हस्ताक्षर करने की प्रक्रिया की थी। |

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

* class [DigitalSignature](../../groupdocs.metadata.standards.signing/digitalsignature)
* नाम स्थान [GroupDocs.Metadata.Standards.Pkcs](../../groupdocs.metadata.standards.pkcs)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
