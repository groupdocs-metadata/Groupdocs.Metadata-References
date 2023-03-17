---
title: AviHeader
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: AVI वडय में AVIMAINHEADER संरचन क प्रतनधत्व करत है
type: docs
weight: 2380
url: /hi/net/groupdocs.metadata.formats.video/aviheader/
---
## AviHeader class

AVI वीडियो में AVIMAINHEADER संरचना का प्रतिनिधित्व करता है।

```csharp
public sealed class AviHeader : CustomPackage
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [AviHeader](aviheader)() | का एक नया उदाहरण प्रारंभ करता है[`AviHeader`](../aviheader) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [AviHeaderFlags](../../groupdocs.metadata.formats.video/aviheader/aviheaderflags) { get; } | शून्य या अधिक AVI फ़्लैग का बिटवाइज़ संयोजन प्राप्त करता है. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [Height](../../groupdocs.metadata.formats.video/aviheader/height) { get; } | पिक्सेल में AVI फ़ाइल की ऊंचाई प्राप्त करता है। |
| [InitialFrames](../../groupdocs.metadata.formats.video/aviheader/initialframes) { get; } | इंटरलीव की गई फ़ाइलों के लिए प्रारंभिक फ़्रेम प्राप्त करता है।  गैर-अंतर्निहित फ़ाइलों को शून्य निर्दिष्ट करना चाहिए। यदि आप इंटरलीव्ड फाइलें बना रहे हैं, तो इस सदस्य में एवीआई अनुक्रम के प्रारंभिक फ्रेम से पहले फ़ाइल में फ्रेम की संख्या निर्दिष्ट करें। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [MaxBytesPerSec](../../groupdocs.metadata.formats.video/aviheader/maxbytespersec) { get; } | फ़ाइल की अनुमानित अधिकतम डेटा दर प्राप्त करता है।  यह मान प्रति सेकंड बाइट्स की संख्या को इंगित करता है जिसे सिस्टम को मुख्य हेडर और स्ट्रीम हेडर चंक्स में निहित अन्य मापदंडों द्वारा निर्दिष्ट के रूप में एक AVI अनुक्रम प्रस्तुत करने के लिए संभालना चाहिए। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [MicroSecPerFrame](../../groupdocs.metadata.formats.video/aviheader/microsecperframe) { get; } | फ्रेम के बीच माइक्रोसेकंड की संख्या प्राप्त करता है। यह मान फ़ाइल के समग्र समय को इंगित करता है. |
| [PaddingGranularity](../../groupdocs.metadata.formats.video/aviheader/paddinggranularity) { get; } | बाइट्स में डेटा के लिए संरेखण प्राप्त करता है। डेटा को इस मान के गुणकों में पैड करें. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [Streams](../../groupdocs.metadata.formats.video/aviheader/streams) { get; } | फ़ाइल में स्ट्रीम की संख्या प्राप्त करता है। उदाहरण के लिए, ऑडियो और वीडियो वाली फ़ाइल में दो स्ट्रीम होती हैं. |
| [SuggestedBufferSize](../../groupdocs.metadata.formats.video/aviheader/suggestedbuffersize) { get; } | फ़ाइल पढ़ने के लिए सुझाए गए बफर आकार को प्राप्त करता है।  आम तौर पर, यह आकार इतना बड़ा होना चाहिए कि फ़ाइल में सबसे बड़ा हिस्सा शामिल हो सके। यदि शून्य पर सेट किया जाता है, या यदि यह बहुत छोटा है, तो प्लेबैक सॉफ़्टवेयर को प्लेबैक के दौरान मेमोरी को पुनः आवंटित करना होगा, जिससे प्रदर्शन कम हो जाएगा। एक इंटरलीव की गई फ़ाइल के लिए, बफ़र का आकार इतना बड़ा होना चाहिए कि वह पूरे रिकॉर्ड को पढ़ सके, न कि केवल एक हिस्सा। |
| [TotalFrames](../../groupdocs.metadata.formats.video/aviheader/totalframes) { get; } | फ़ाइल में डेटा के फ्रेम की कुल संख्या प्राप्त करता है। |
| [Width](../../groupdocs.metadata.formats.video/aviheader/width) { get; } | पिक्सेल में AVI फ़ाइल की चौड़ाई प्राप्त करता है। |

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

* [AVI फ़ाइलों में मेटाडेटा के साथ कार्य करना](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+AVI+files)

### यह सभी देखें

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
