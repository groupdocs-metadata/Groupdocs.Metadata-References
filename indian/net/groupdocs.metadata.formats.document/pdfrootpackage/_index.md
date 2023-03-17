---
title: PdfRootPackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: एक पडएफ दस्तवेज़ में मेटडेट के सथ कम करने क अनुमत देने वले रूट पैकेज क प्रतनधत्व करत है
type: docs
weight: 1040
url: /hi/net/groupdocs.metadata.formats.document/pdfrootpackage/
---
## PdfRootPackage class

एक पीडीएफ दस्तावेज़ में मेटाडेटा के साथ काम करने की अनुमति देने वाले रूट पैकेज का प्रतिनिधित्व करता है।

```csharp
public class PdfRootPackage : DocumentRootPackage<PdfPackage>, IXmp
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| virtual [DocumentProperties](../../groupdocs.metadata.formats.document/documentrootpackage-1/documentproperties) { get; } | मूल मेटाडेटा गुणों को दस्तावेज़ में प्रस्तुत करता है। |
| [DocumentStatistics](../../groupdocs.metadata.formats.document/pdfrootpackage/documentstatistics) { get; } | दस्तावेज़ आँकड़े पैकेज प्राप्त करता है। |
| [FileType](../../groupdocs.metadata.formats.document/pdfrootpackage/filetype) { get; } | फ़ाइल प्रकार मेटाडेटा पैकेज प्राप्त करता है। (2 properties) |
| [InspectionPackage](../../groupdocs.metadata.formats.document/pdfrootpackage/inspectionpackage) { get; } | एक मेटाडेटा पैकेज प्राप्त करता है जिसमें दस्तावेज़ के लिए निरीक्षण परिणाम होते हैं। पैकेज में दस्तावेज़ के हिस्सों के बारे में जानकारी होती है जिसे कुछ मामलों में मेटाडेटा माना जा सकता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [XmpPackage](../../groupdocs.metadata.formats.document/pdfrootpackage/xmppackage) { get; set; } | एक्सएमपी मेटाडेटा पैकेज प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को जोड़ता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | निर्धारित करता है कि पैकेज में निर्दिष्ट नाम के साथ मेटाडेटा गुण है या नहीं। |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को संतुष्ट करने वाले मेटाडेटा गुणों को ढूँढता है। खोज पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करती है। |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृति करता है। |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को पूरा करने वाले मेटाडेटा गुणों को हटाता है। |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | पैकेज से लिखने योग्य मेटाडेटा गुणों को हटाता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को सेट करता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। यह विधि एक संयोजन है[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) और[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) यदि कोई मौजूदा संपत्ति विधेय को संतुष्ट करती है तो उसका मान अपडेट किया जाता है। यदि पैकेज में कोई ज्ञात संपत्ति गायब है जो विधेय को संतुष्ट करती है तो इसे पैकेज में जोड़ा जाता है। |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | अद्यतन ज्ञात मेटाडेटा गुण निर्दिष्ट विधेय को संतुष्ट करते हैं। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |

### टिप्पणियों

**और अधिक जानें**

* [पीडीएफ दस्तावेजों में मेटाडेटा के साथ काम करना](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)
* [XMP मेटाडेटा के साथ काम करना](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### उदाहरण

यह कोड नमूना दिखाता है कि पीडीएफ दस्तावेज़ से अंतर्निहित मेटाडेटा गुणों को कैसे निकालना है।

```csharp
using (Metadata metadata = new Metadata(Constants.InputPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    Console.WriteLine(root.DocumentProperties.Author);
    Console.WriteLine(root.DocumentProperties.CreatedDate);
    Console.WriteLine(root.DocumentProperties.Subject);
    Console.WriteLine(root.DocumentProperties.Producer);
    Console.WriteLine(root.DocumentProperties.Keywords);

    // ... 
}
```

### यह सभी देखें

* class [DocumentRootPackage&lt;TPackage&gt;](../documentrootpackage-1)
* class [PdfPackage](../pdfpackage)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* नाम स्थान [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
