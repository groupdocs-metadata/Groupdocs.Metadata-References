---
title: DiagramPackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: आरेख प्ररूप में मूल मेटडेट पैकेज क प्रतनधत्व करत है
type: docs
weight: 890
url: /hi/net/groupdocs.metadata.formats.document/diagrampackage/
---
## DiagramPackage class

आरेख प्रारूप में मूल मेटाडेटा पैकेज का प्रतिनिधित्व करता है।

```csharp
public class DiagramPackage : DocumentPackage
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternateNames](../../groupdocs.metadata.formats.document/diagrampackage/alternatenames) { get; set; } | दस्तावेज़ के लिए वैकल्पिक नाम प्राप्त या सेट करता है। केवल VDX और VSX स्वरूपों में अद्यतन किया जा सकता है. |
| [BuildNumberCreated](../../groupdocs.metadata.formats.document/diagrampackage/buildnumbercreated) { get; } | दस्तावेज़ बनाने के लिए उपयोग किए गए इंस्टेंस की पूरी बिल्ड संख्या प्राप्त करता है। |
| [BuildNumberEdited](../../groupdocs.metadata.formats.document/diagrampackage/buildnumberedited) { get; } | पिछले दस्तावेज़ को संपादित करने के लिए उपयोग किए गए इंस्टेंस की बिल्ड संख्या प्राप्त करता है। |
| [Category](../../groupdocs.metadata.formats.document/diagrampackage/category) { get; set; } | ड्राइंग के प्रकार के लिए वर्णनात्मक पाठ प्राप्त या सेट करता है, जैसे फ़्लोचार्ट या कार्यालय लेआउट। यह पाठ गुण संवाद बॉक्स में श्रेणी बॉक्स में Microsoft Visio उपयोगकर्ता इंटरफ़ेस में भी दर्ज किया जा सकता है। |
| [Company](../../groupdocs.metadata.formats.document/diagrampackage/company) { get; set; } | उपयोगकर्ता द्वारा दर्ज की गई जानकारी प्राप्त करता है या सेट करता है जो ड्राइंग बनाने वाली कंपनी या ड्राइंग बनाने वाली कंपनी की पहचान करता है। अधिकतम लंबाई 63 वर्ण है। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [Creator](../../groupdocs.metadata.formats.document/diagrampackage/creator) { get; set; } | फ़ाइल बनाने वाले या अंतिम बार अपडेट करने वाले व्यक्ति को प्राप्त या सेट करता है. अधिकतम लंबाई 63 वर्ण है.. |
| [Description](../../groupdocs.metadata.formats.document/diagrampackage/description) { get; set; } | दस्तावेज़ के लिए एक वर्णनात्मक टेक्स्ट स्ट्रिंग प्राप्त या सेट करता है। दस्तावेज़ के बारे में महत्वपूर्ण जानकारी संग्रहीत करने के लिए इस तत्व का उपयोग करें, जैसे इसका उद्देश्य, हाल के परिवर्तन, या लंबित परिवर्तन। अधिकतम 191 वर्ण हैं। |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/diagrampackage/hyperlinkbase) { get; set; } | संबंधित हाइपरलिंक्स के लिए उपयोग किए जाने वाले पथ को प्राप्त या सेट करता है (हाइपरलिंक जिसके लिए Microsoft Visio आरेख के संबंध में लिंक की गई फ़ाइल स्थान का वर्णन किया गया है)। इस तत्व में. अधिकतम लंबाई 256 वर्ण है. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [Keywords](../../groupdocs.metadata.formats.document/diagrampackage/keywords) { get; set; } | एक टेक्स्ट स्ट्रिंग प्राप्त या सेट करता है जो विषयों या फ़ाइल के बारे में अन्य महत्वपूर्ण जानकारी, जैसे प्रोजेक्ट नाम, क्लाइंट नाम, या संस्करण संख्या की पहचान करता है। अधिकतम स्ट्रिंग लंबाई 63 वर्ण है। |
| [Language](../../groupdocs.metadata.formats.document/diagrampackage/language) { get; set; } | दस्तावेज़ की भाषा प्राप्त या सेट करता है। केवल वीएसडी और वीएसडीएक्स प्रारूपों में अद्यतन किया जा सकता है। |
| [Manager](../../groupdocs.metadata.formats.document/diagrampackage/manager) { get; set; } | प्रोजेक्ट या विभाग के प्रभारी व्यक्ति की पहचान करने वाली उपयोगकर्ता द्वारा दर्ज टेक्स्ट स्ट्रिंग प्राप्त या सेट करता है। अधिकतम लंबाई 63 वर्ण है। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [PreviewPicture](../../groupdocs.metadata.formats.document/diagrampackage/previewpicture) { get; set; } | पूर्वावलोकन चित्र प्राप्त या सेट करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [Subject](../../groupdocs.metadata.formats.document/diagrampackage/subject) { get; set; } | दस्तावेज़ की सामग्री का वर्णन करने वाले उपयोगकर्ता-परिभाषित पाठ स्ट्रिंग को प्राप्त या सेट करता है। अधिकतम लंबाई 63 वर्ण है। |
| [Template](../../groupdocs.metadata.formats.document/diagrampackage/template) { get; set; } | उस टेम्पलेट के फ़ाइल नाम को निर्दिष्ट करते हुए एक स्ट्रिंग मान प्राप्त या सेट करता है जिससे दस्तावेज़ बनाया गया था। |
| [TimeCreated](../../groupdocs.metadata.formats.document/diagrampackage/timecreated) { get; set; } | दस्तावेज़ कब बनाया गया था यह इंगित करने के लिए दिनांक और समय मान प्राप्त या सेट करता है। |
| [TimeEdited](../../groupdocs.metadata.formats.document/diagrampackage/timeedited) { get; } | दिनांक और समय मान प्राप्त करता है जो इंगित करता है कि दस्तावेज़ को अंतिम बार कब संपादित किया गया था। |
| [TimePrinted](../../groupdocs.metadata.formats.document/diagrampackage/timeprinted) { get; } | दिनांक और समय मान प्राप्त करता है जो इंगित करता है कि दस्तावेज़ अंतिम बार कब मुद्रित किया गया था। |
| [TimeSaved](../../groupdocs.metadata.formats.document/diagrampackage/timesaved) { get; } | दिनांक और समय मान प्राप्त करता है जो इंगित करता है कि दस्तावेज़ को अंतिम बार सहेजा गया था। |
| [Title](../../groupdocs.metadata.formats.document/diagrampackage/title) { get; set; } | उपयोगकर्ता-परिभाषित टेक्स्ट स्ट्रिंग प्राप्त या सेट करता है जो दस्तावेज़ के लिए वर्णनात्मक शीर्षक के रूप में कार्य करता है। अधिकतम लंबाई 63 वर्ण है। |

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
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set)(string, bool) | निर्दिष्ट नाम के साथ मेटाडेटा गुण जोड़ता या प्रतिस्थापित करता है। |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_2)(string, DateTime) | निर्दिष्ट नाम के साथ मेटाडेटा गुण जोड़ता या प्रतिस्थापित करता है। |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_1)(string, double) | निर्दिष्ट नाम के साथ मेटाडेटा गुण जोड़ता या प्रतिस्थापित करता है। |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_3)(string, string) | निर्दिष्ट नाम के साथ मेटाडेटा गुण जोड़ता या प्रतिस्थापित करता है। |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को सेट करता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। यह विधि एक संयोजन है[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) और[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) यदि कोई मौजूदा संपत्ति विधेय को संतुष्ट करती है तो उसका मान अपडेट किया जाता है। यदि पैकेज में कोई ज्ञात संपत्ति गायब है जो विधेय को संतुष्ट करती है तो इसे पैकेज में जोड़ा जाता है। |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | अद्यतन ज्ञात मेटाडेटा गुण निर्दिष्ट विधेय को संतुष्ट करते हैं। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |

### टिप्पणियों

**और अधिक जानें**

* [आरेखों में मेटाडेटा के साथ कार्य करना](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### उदाहरण

यह कोड नमूना दर्शाता है कि आरेख से अंतर्निहित मेटाडेटा गुण कैसे निकालें।

```csharp
using (Metadata metadata = new Metadata(Constants.InputVsdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    Console.WriteLine(root.DocumentProperties.Creator);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.Language);
    Console.WriteLine(root.DocumentProperties.TimeCreated);
    Console.WriteLine(root.DocumentProperties.Category);

    // ... 
}
```

### यह सभी देखें

* class [DocumentPackage](../documentpackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
