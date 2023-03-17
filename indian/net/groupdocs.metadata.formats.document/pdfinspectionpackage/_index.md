---
title: PdfInspectionPackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: में PDF दस्तवेज़ के हस्सं के बरे में जनकर शमल है जसे कुछ ममलं में मेटडेट मन ज सकत है
type: docs
weight: 1020
url: /hi/net/groupdocs.metadata.formats.document/pdfinspectionpackage/
---
## PdfInspectionPackage class

में PDF दस्तावेज़ के हिस्सों के बारे में जानकारी शामिल है जिसे कुछ मामलों में मेटाडेटा माना जा सकता है।

```csharp
public sealed class PdfInspectionPackage : CustomPackage
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Annotations](../../groupdocs.metadata.formats.document/pdfinspectionpackage/annotations) { get; } | एनोटेशन की एक सरणी प्राप्त करता है। |
| [Attachments](../../groupdocs.metadata.formats.document/pdfinspectionpackage/attachments) { get; } | अनुलग्नकों की एक सरणी प्राप्त करता है। |
| [Bookmarks](../../groupdocs.metadata.formats.document/pdfinspectionpackage/bookmarks) { get; } | बुकमार्क की एक सरणी प्राप्त करता है। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/pdfinspectionpackage/digitalsignatures) { get; } | डिजिटल हस्ताक्षरों की एक सरणी प्राप्त करता है। |
| [Fields](../../groupdocs.metadata.formats.document/pdfinspectionpackage/fields) { get; } | प्रपत्र फ़ील्ड की एक सरणी प्राप्त करता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को जोड़ता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [ClearAnnotations](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearannotations)() | दस्तावेज़ से सभी ज्ञात एनोटेशन को हटाता है। |
| [ClearAttachments](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearattachments)() | दस्तावेज़ से सभी खोजे गए अटैचमेंट हटा देता है. |
| [ClearBookmarks](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearbookmarks)() | दस्तावेज़ से खोजे गए सभी बुकमार्क हटा देता है. |
| [ClearDigitalSignatures](../../groupdocs.metadata.formats.document/pdfinspectionpackage/cleardigitalsignatures)() | दस्तावेज़ से सभी पहचाने गए डिजिटल हस्ताक्षर हटा देता है। |
| [ClearFields](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearfields)() | दस्तावेज़ से सभी ज्ञात फ़ॉर्म फ़ील्ड को हटा देता है। |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | निर्धारित करता है कि पैकेज में निर्दिष्ट नाम के साथ मेटाडेटा गुण है या नहीं। |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को संतुष्ट करने वाले मेटाडेटा गुणों को ढूँढता है। खोज पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करती है। |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृति करता है। |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/pdfinspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को पूरा करने वाले मेटाडेटा गुणों को हटाता है। |
| override [Sanitize](../../groupdocs.metadata.formats.document/pdfinspectionpackage/sanitize)() | पैकेज से लिखने योग्य मेटाडेटा गुणों को हटाता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को सेट करता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। यह विधि एक संयोजन है[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) और[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) यदि कोई मौजूदा संपत्ति विधेय को संतुष्ट करती है तो उसका मान अपडेट किया जाता है। यदि पैकेज में कोई ज्ञात संपत्ति गायब है जो विधेय को संतुष्ट करती है तो इसे पैकेज में जोड़ा जाता है। |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | अद्यतन ज्ञात मेटाडेटा गुण निर्दिष्ट विधेय को संतुष्ट करते हैं। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |

### टिप्पणियों

**और अधिक जानें**

* [पीडीएफ दस्तावेजों में मेटाडेटा के साथ काम करना](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)

### उदाहरण

यह कोड नमूना दर्शाता है कि पीडीएफ दस्तावेज़ में निरीक्षण गुणों को कैसे हटाया जाए।

```csharp
using (Metadata metadata = new Metadata(Constants.SignedPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    root.InspectionPackage.ClearAnnotations();
    root.InspectionPackage.ClearAttachments();
    root.InspectionPackage.ClearFields();
    root.InspectionPackage.ClearBookmarks();
    root.InspectionPackage.ClearDigitalSignatures();

    metadata.Save(Constants.OutputPdf);
}
```

### यह सभी देखें

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
