---
title: ID3V2UserDefinedFrame
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: एक में एक TXXX फ्रेम क प्रतनधत्व करत हैID3V2Tag./id3v2tag .
type: docs
weight: 540
url: /hi/net/groupdocs.metadata.formats.audio/id3v2userdefinedframe/
---
## ID3V2UserDefinedFrame class

एक में एक TXXX फ्रेम का प्रतिनिधित्व करता है[`ID3V2Tag`](../id3v2tag) .

```csharp
public sealed class ID3V2UserDefinedFrame : ID3V2TagFrame
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ID3V2UserDefinedFrame](id3v2userdefinedframe#constructor_1)(string, string) | का एक नया उदाहरण प्रारंभ करता है[`ID3V2UserDefinedFrame`](../id3v2userdefinedframe) वर्ग. |
| [ID3V2UserDefinedFrame](id3v2userdefinedframe#constructor)(ID3V2EncodingType, string, string) | का एक नया उदाहरण प्रारंभ करता है[`ID3V2UserDefinedFrame`](../id3v2userdefinedframe) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [Data](../../groupdocs.metadata.formats.audio/id3v2tagframe/data) { get; } | फ्रेम डेटा प्राप्त करता है। |
| [Description](../../groupdocs.metadata.formats.audio/id3v2userdefinedframe/description) { get; } | विवरण प्राप्त करता है। |
| [Encoding](../../groupdocs.metadata.formats.audio/id3v2userdefinedframe/encoding) { get; } | फ्रेम का एन्कोडिंग प्राप्त करता है। |
| [Flags](../../groupdocs.metadata.formats.audio/id3v2tagframe/flags) { get; } | फ़्रेम फ़्लैग प्राप्त करता है. |
| [Id](../../groupdocs.metadata.formats.audio/id3v2tagframe/id) { get; } | फ्रेम की आईडी प्राप्त करता है (पैटर्न से मेल खाने वाले चार वर्ण [A-Z0-9])। |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | हो जाता है[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) निर्दिष्ट नाम के साथ. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [Value](../../groupdocs.metadata.formats.audio/id3v2userdefinedframe/value) { get; } | मान प्राप्त करता है। |

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

* [ID3v2 टैग को संभालना](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### यह सभी देखें

* class [ID3V2TagFrame](../id3v2tagframe)
* नाम स्थान [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
