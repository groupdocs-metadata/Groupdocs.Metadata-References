---
title: Metadata
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: सभ समर्थत स्वरूपं में मेटडेट तक पहुँचने के लए मुख्य वर्ग प्रदन करत है
type: docs
weight: 2660
url: /hi/net/groupdocs.metadata/metadata/
---
## Metadata class

सभी समर्थित स्वरूपों में मेटाडेटा तक पहुँचने के लिए मुख्य वर्ग प्रदान करता है।

```csharp
public sealed class Metadata : IDisposable
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Metadata](metadata#constructor)(Stream) | का एक नया उदाहरण प्रारंभ करता है[`Metadata`](../metadata) वर्ग. |
| [Metadata](metadata#constructor_2)(string) | का एक नया उदाहरण प्रारंभ करता है[`Metadata`](../metadata) वर्ग. |
| [Metadata](metadata#constructor_1)(Stream, LoadOptions) | का एक नया उदाहरण प्रारंभ करता है[`Metadata`](../metadata) वर्ग. |
| [Metadata](metadata#constructor_3)(string, LoadOptions) | का एक नया उदाहरण प्रारंभ करता है[`Metadata`](../metadata) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [FileFormat](../../groupdocs.metadata/metadata/fileformat) { get; } | लोड की गई फ़ाइल का प्रकार प्राप्त करता है (यदि पहचाना जाता है)। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddProperties](../../groupdocs.metadata/metadata/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को जोड़ता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Dispose](../../groupdocs.metadata/metadata/dispose)() | अप्रबंधित संसाधनों को मुक्त करने, जारी करने या रीसेट करने से संबंधित एप्लिकेशन-परिभाषित कार्य करता है। |
| [FindProperties](../../groupdocs.metadata/metadata/findproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को संतुष्ट करने वाले मेटाडेटा गुणों को ढूँढता है। खोज पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करती है। |
| [GeneratePreview](../../groupdocs.metadata/metadata/generatepreview)(PreviewOptions) | निर्दिष्ट पृष्ठों के लिए पूर्वावलोकन चित्र बनाता है। |
| [GetDocumentInfo](../../groupdocs.metadata/metadata/getdocumentinfo)() | लोड किए गए दस्तावेज़ के बारे में सामान्य जानकारी प्राप्त करता है। |
| [GetRootPackage](../../groupdocs.metadata/metadata/getrootpackage#getrootpackage)() | फ़ाइल से निकाले गए सभी मेटाडेटा गुणों तक पहुँच प्रदान करने वाला रूट पैकेज प्राप्त करता है। |
| [GetRootPackage&lt;TRoot&gt;](../../groupdocs.metadata/metadata/getrootpackage#getrootpackage_1)() | फ़ाइल से निकाले गए सभी मेटाडेटा गुणों तक पहुँच प्रदान करने वाला रूट पैकेज प्राप्त करता है। |
| [RemoveProperties](../../groupdocs.metadata/metadata/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को पूरा करने वाले मेटाडेटा गुणों को हटाता है। |
| [Sanitize](../../groupdocs.metadata/metadata/sanitize)() | यदि संभव हो तो सभी ज्ञात पैकेजों या पूरे पैकेजों से लिखने योग्य मेटाडेटा गुणों को हटा देता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Save](../../groupdocs.metadata/metadata/save#save)() | लोड किए गए दस्तावेज़ में किए गए सभी परिवर्तनों को सहेजता है। |
| [Save](../../groupdocs.metadata/metadata/save#save_1)(Stream) | दस्तावेज़ सामग्री को स्ट्रीम में सहेजता है. |
| [Save](../../groupdocs.metadata/metadata/save#save_2)(string) | दस्तावेज़ सामग्री को निर्दिष्ट फ़ाइल में सहेजता है। |
| [SetProperties](../../groupdocs.metadata/metadata/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को सेट करता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। यह विधि एक संयोजन है[`AddProperties`](./addproperties) और[`UpdateProperties`](./updateproperties) . यदि कोई मौजूदा संपत्ति विधेय को संतुष्ट करती है तो उसका मान अपडेट किया जाता है। यदि किसी पैकेज में कोई ज्ञात संपत्ति गायब है जो विधेय को संतुष्ट करती है तो इसे पैकेज में जोड़ा जाता है। |
| [UpdateProperties](../../groupdocs.metadata/metadata/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | अद्यतन ज्ञात मेटाडेटा गुण निर्दिष्ट विधेय को संतुष्ट करते हैं। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |

### यह सभी देखें

* नाम स्थान [GroupDocs.Metadata](../../groupdocs.metadata)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
