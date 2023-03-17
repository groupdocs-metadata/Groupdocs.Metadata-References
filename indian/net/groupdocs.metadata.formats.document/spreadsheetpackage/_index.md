---
title: SpreadsheetPackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: एक स्प्रेडशट में मूल मेटडेट पैकेज क प्रतनधत्व करत है
type: docs
weight: 1200
url: /hi/net/groupdocs.metadata.formats.document/spreadsheetpackage/
---
## SpreadsheetPackage class

एक स्प्रेडशीट में मूल मेटाडेटा पैकेज का प्रतिनिधित्व करता है।

```csharp
public class SpreadsheetPackage : DocumentPackage
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/spreadsheetpackage/author) { get; set; } | दस्तावेज़ लेखक को प्राप्त या सेट करता है। |
| [Category](../../groupdocs.metadata.formats.document/spreadsheetpackage/category) { get; set; } | श्रेणी प्राप्त या सेट करता है। |
| [Comments](../../groupdocs.metadata.formats.document/spreadsheetpackage/comments) { get; set; } | टिप्पणियों को प्राप्त या सेट करता है। |
| [Company](../../groupdocs.metadata.formats.document/spreadsheetpackage/company) { get; set; } | कंपनी प्राप्त करता है या सेट करता है। |
| [ContentStatus](../../groupdocs.metadata.formats.document/spreadsheetpackage/contentstatus) { get; set; } | सामग्री स्थिति प्राप्त या सेट करता है। |
| [ContentType](../../groupdocs.metadata.formats.document/spreadsheetpackage/contenttype) { get; set; } | सामग्री प्रकार प्राप्त या सेट करता है। |
| [ContentTypeProperties](../../groupdocs.metadata.formats.document/spreadsheetpackage/contenttypeproperties) { get; } | मेटाडेटा पैकेज प्राप्त करता है जिसमें सामग्री प्रकार गुण होते हैं। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [CreatedTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/createdtime) { get; set; } | दस्तावेज़ निर्मित दिनांक प्राप्त या सेट करता है। |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/spreadsheetpackage/hyperlinkbase) { get; set; } | हाइपरलिंक आधार प्राप्त या सेट करता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [Keywords](../../groupdocs.metadata.formats.document/spreadsheetpackage/keywords) { get; set; } | कीवर्ड प्राप्त या सेट करता है। |
| [Language](../../groupdocs.metadata.formats.document/spreadsheetpackage/language) { get; set; } | दस्तावेज़ की भाषा प्राप्त या सेट करता है. |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastprinteddate) { get; set; } | UTC. में अंतिम मुद्रित तिथि प्राप्त या सेट करता है |
| [LastSavedBy](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastsavedby) { get; set; } | अंतिम लेखक का नाम प्राप्त या सेट करता है। |
| [LastSavedTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastsavedtime) { get; set; } | UTC. में अंतिम बचत का समय प्राप्त या सेट करता है |
| [Manager](../../groupdocs.metadata.formats.document/spreadsheetpackage/manager) { get; set; } | प्रबंधक प्राप्त करता है या सेट करता है। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [NameOfApplication](../../groupdocs.metadata.formats.document/spreadsheetpackage/nameofapplication) { get; set; } | एप्लिकेशन का नाम प्राप्त या सेट करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [Revision](../../groupdocs.metadata.formats.document/spreadsheetpackage/revision) { get; set; } | दस्तावेज़ संशोधन संख्या प्राप्त या सेट करता है। |
| [Subject](../../groupdocs.metadata.formats.document/spreadsheetpackage/subject) { get; set; } | विषय प्राप्त करता है या सेट करता है। |
| [Template](../../groupdocs.metadata.formats.document/spreadsheetpackage/template) { get; set; } | दस्तावेज़ टेम्पलेट नाम प्राप्त या सेट करता है। |
| [Title](../../groupdocs.metadata.formats.document/spreadsheetpackage/title) { get; set; } | दस्तावेज़ का शीर्षक प्राप्त या सेट करता है। |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/totaleditingtime) { get; set; } | मिनटों में कुल संपादन समय प्राप्त या सेट करता है। |
| [Version](../../groupdocs.metadata.formats.document/spreadsheetpackage/version) { get; set; } | दस्तावेज़ बनाने वाले एप्लिकेशन का संस्करण संख्या प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को जोड़ता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | पैकेज से सभी लिखने योग्य मेटाडेटा गुणों को हटाता है। |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | सभी अंतर्निहित मेटाडेटा गुणों को हटाता है। |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | सभी कस्टम मेटाडेटा गुण निकालता है. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | निर्धारित करता है कि पैकेज में निर्दिष्ट नाम के साथ मेटाडेटा गुण है या नहीं। |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को संतुष्ट करने वाले मेटाडेटा गुणों को ढूँढता है। खोज पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करती है। |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृति करता है। |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | निर्दिष्ट नाम से लिखने योग्य मेटाडेटा गुण को निकालता है. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को पूरा करने वाले मेटाडेटा गुणों को हटाता है। |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | पैकेज से लिखने योग्य मेटाडेटा गुणों को हटाता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set)(string, bool) | निर्दिष्ट नाम के साथ मेटाडेटा गुण जोड़ता या प्रतिस्थापित करता है। |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_3)(string, DateTime) | निर्दिष्ट नाम के साथ मेटाडेटा गुण जोड़ता या प्रतिस्थापित करता है। |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_1)(string, double) | निर्दिष्ट नाम के साथ मेटाडेटा गुण जोड़ता या प्रतिस्थापित करता है। |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_2)(string, int) | निर्दिष्ट नाम के साथ मेटाडेटा गुण जोड़ता या प्रतिस्थापित करता है। |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_4)(string, string) | निर्दिष्ट नाम के साथ मेटाडेटा गुण जोड़ता या प्रतिस्थापित करता है। |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को सेट करता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। यह विधि एक संयोजन है[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) और[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) यदि कोई मौजूदा संपत्ति विधेय को संतुष्ट करती है तो उसका मान अपडेट किया जाता है। यदि पैकेज में कोई ज्ञात संपत्ति गायब है जो विधेय को संतुष्ट करती है तो इसे पैकेज में जोड़ा जाता है। |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | अद्यतन ज्ञात मेटाडेटा गुण निर्दिष्ट विधेय को संतुष्ट करते हैं। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |

### टिप्पणियों

**और अधिक जानें**

* [स्प्रेडशीट में मेटाडेटा के साथ काम करना](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Spreadsheets)

### उदाहरण

यह उदाहरण दिखाता है कि स्प्रेडशीट में अंतर्निहित मेटाडेटा गुणों को कैसे अपडेट किया जाए।

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    var root = metadata.GetRootPackage<SpreadsheetRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputXlsx);
}
```

### यह सभी देखें

* class [DocumentPackage](../documentpackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
