---
title: ProjectManagementPackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: एक परयजन प्रबंधन फ़इल में मूल मेटडेट पैकेज क प्रतनधत्व करत है
type: docs
weight: 1130
url: /hi/net/groupdocs.metadata.formats.document/projectmanagementpackage/
---
## ProjectManagementPackage class

एक परियोजना प्रबंधन फ़ाइल में मूल मेटाडेटा पैकेज का प्रतिनिधित्व करता है।

```csharp
public sealed class ProjectManagementPackage : DocumentPackage
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/projectmanagementpackage/author) { get; set; } | प्रोजेक्ट के लेखक को प्राप्त या सेट करता है। |
| [Category](../../groupdocs.metadata.formats.document/projectmanagementpackage/category) { get; set; } | श्रेणी प्राप्त या सेट करता है। |
| [Comments](../../groupdocs.metadata.formats.document/projectmanagementpackage/comments) { get; set; } | उपयोगकर्ता टिप्पणियों को प्राप्त या सेट करता है। |
| [Company](../../groupdocs.metadata.formats.document/projectmanagementpackage/company) { get; set; } | कंपनी प्राप्त करता है या सेट करता है। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [CreationDate](../../groupdocs.metadata.formats.document/projectmanagementpackage/creationdate) { get; set; } | निर्माण तिथि प्राप्त या सेट करता है। |
| [Guid](../../groupdocs.metadata.formats.document/projectmanagementpackage/guid) { get; set; } | प्रोजेक्ट की आईडी प्राप्त या सेट करता है। |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/projectmanagementpackage/hyperlinkbase) { get; set; } | हाइपरलिंक आधार प्राप्त या सेट करता है। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [Keywords](../../groupdocs.metadata.formats.document/projectmanagementpackage/keywords) { get; set; } | कीवर्ड प्राप्त या सेट करता है। |
| [LastAuthor](../../groupdocs.metadata.formats.document/projectmanagementpackage/lastauthor) { get; set; } | अंतिम लेखक को प्राप्त या सेट करता है। |
| [LastPrinted](../../groupdocs.metadata.formats.document/projectmanagementpackage/lastprinted) { get; set; } | प्रोजेक्ट के अंतिम प्रिंट समय को प्राप्त या सेट करता है। |
| [LastSaved](../../groupdocs.metadata.formats.document/projectmanagementpackage/lastsaved) { get; set; } | वह दिनांक प्राप्त या सेट करता है जब प्रोजेक्ट पिछली बार सहेजा गया था। |
| [Manager](../../groupdocs.metadata.formats.document/projectmanagementpackage/manager) { get; set; } | प्रोजेक्ट मैनेजर प्राप्त करता है या सेट करता है। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [Revision](../../groupdocs.metadata.formats.document/projectmanagementpackage/revision) { get; set; } | संशोधन संख्या प्राप्त या सेट करता है। |
| [SaveVersion](../../groupdocs.metadata.formats.document/projectmanagementpackage/saveversion) { get; } | Microsoft Office प्रोजेक्ट का वह संस्करण प्राप्त करता है जिससे प्रोजेक्ट फ़ाइल सहेजी गई थी. |
| [Subject](../../groupdocs.metadata.formats.document/projectmanagementpackage/subject) { get; set; } | विषय प्राप्त करता है या सेट करता है। |
| [Template](../../groupdocs.metadata.formats.document/projectmanagementpackage/template) { get; set; } | टेम्प्लेट प्राप्त करता है या सेट करता है. |
| [Title](../../groupdocs.metadata.formats.document/projectmanagementpackage/title) { get; set; } | शीर्षक प्राप्त या सेट करता है। |

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
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set)(string, bool) | निर्दिष्ट नाम के साथ मेटाडेटा गुण जोड़ता या प्रतिस्थापित करता है। |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_3)(string, DateTime) | निर्दिष्ट नाम के साथ मेटाडेटा गुण जोड़ता या प्रतिस्थापित करता है। |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_1)(string, double) | निर्दिष्ट नाम के साथ मेटाडेटा गुण जोड़ता या प्रतिस्थापित करता है। |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_2)(string, int) | निर्दिष्ट नाम के साथ मेटाडेटा गुण जोड़ता या प्रतिस्थापित करता है। |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_4)(string, string) | निर्दिष्ट नाम के साथ मेटाडेटा गुण जोड़ता या प्रतिस्थापित करता है। |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को सेट करता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। यह विधि एक संयोजन है[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) और[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) यदि कोई मौजूदा संपत्ति विधेय को संतुष्ट करती है तो उसका मान अपडेट किया जाता है। यदि पैकेज में कोई ज्ञात संपत्ति गायब है जो विधेय को संतुष्ट करती है तो इसे पैकेज में जोड़ा जाता है। |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | अद्यतन ज्ञात मेटाडेटा गुण निर्दिष्ट विधेय को संतुष्ट करते हैं। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |

### टिप्पणियों

**और अधिक जानें**

* [ProjectManagement स्वरूपों में मेटाडेटा के साथ कार्य करना](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+ProjectManagement+formats)

### उदाहरण

यह कोड नमूना दर्शाता है कि प्रोजेक्ट प्रबंधन दस्तावेज़ में अंतर्निहित गुणों को कैसे अपडेट किया जाए।

```csharp
using (Metadata metadata = new Metadata(Constants.InputMpp))
{
    var root = metadata.GetRootPackage<ProjectManagementRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreationDate = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Comments = "test comment";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputMpp);
}
```

### यह सभी देखें

* class [DocumentPackage](../documentpackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
