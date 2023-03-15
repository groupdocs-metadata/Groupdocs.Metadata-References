---
title: MsgPackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: MSG संदेश मेटडेट क प्रतनधत्व करत है
type: docs
weight: 1400
url: /hi/net/groupdocs.metadata.formats.email/msgpackage/
---
## MsgPackage class

MSG संदेश मेटाडेटा का प्रतिनिधित्व करता है।

```csharp
public class MsgPackage : EmailPackage
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AttachedFileNames](../../groupdocs.metadata.formats.email/emailpackage/attachedfilenames) { get; } | संलग्न फ़ाइलों के नामों की एक सरणी प्राप्त करता है। |
| [BlindCarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/blindcarboncopyrecipients) { get; set; } | ईमेल संदेश के बीसीसी (अंधा कार्बन कॉपी) प्राप्तकर्ताओं की सरणी प्राप्त या सेट करता है। |
| [Body](../../groupdocs.metadata.formats.email/msgpackage/body) { get; } | ईमेल संदेश टेक्स्ट प्राप्त करता है. |
| [CarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/carboncopyrecipients) { get; set; } | ईमेल संदेश के सीसी (कार्बन कॉपी) प्राप्तकर्ताओं की सरणी प्राप्त या सेट करता है। |
| [Categories](../../groupdocs.metadata.formats.email/msgpackage/categories) { get; } | श्रेणियों या कीवर्ड की सरणी प्राप्त करता है। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [DeliveryTime](../../groupdocs.metadata.formats.email/msgpackage/deliverytime) { get; } | संदेश वितरित होने की तिथि और समय प्राप्त करता है। |
| [Headers](../../groupdocs.metadata.formats.email/emailpackage/headers) { get; } | ईमेल हेडर वाला मेटाडेटा पैकेज प्राप्त करता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [Recipients](../../groupdocs.metadata.formats.email/emailpackage/recipients) { get; set; } | ईमेल प्राप्तकर्ताओं की सरणी प्राप्त या सेट करता है। |
| [Sender](../../groupdocs.metadata.formats.email/emailpackage/sender) { get; } | प्रेषक का ईमेल पता प्राप्त करता है। |
| [Subject](../../groupdocs.metadata.formats.email/emailpackage/subject) { get; set; } | ईमेल विषय प्राप्त या सेट करता है। |

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

* [सहेजे गए ईमेल के साथ काम करना](https://docs.groupdocs.com/display/metadatanet/Working+with+saved+Emails)

### यह सभी देखें

* class [EmailPackage](../emailpackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Email](../../groupdocs.metadata.formats.email)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
