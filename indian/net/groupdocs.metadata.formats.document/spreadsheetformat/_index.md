---
title: SpreadsheetFormat
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: वभन्न स्प्रैडशट उपप्ररूपं क परभषत करत है.
type: docs
weight: 1180
url: /hi/net/groupdocs.metadata.formats.document/spreadsheetformat/
---
## SpreadsheetFormat enumeration

विभिन्न स्प्रैडशीट उपप्रारूपों को परिभाषित करता है.

```csharp
public enum SpreadsheetFormat
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| Unknown | `0` | प्रारूप पहचाना नहीं गया है। |
| Xls | `1` | .XLS एक्सेल प्रारूप का प्रतिनिधित्व करता है। एक्सएलएस एक्सटेंशन वाली फाइलें एक्सेल बाइनरी फाइल फॉर्मेट का प्रतिनिधित्व करती हैं। ऐसी फाइलें माइक्रोसॉफ्ट एक्सेल के साथ-साथ अन्य समान स्प्रेडशीट प्रोग्राम जैसे ओपनऑफिस कैल्क या ऐप्पल नंबर द्वारा बनाई जा सकती हैं। एक्सेल द्वारा सहेजी गई फ़ाइल ज्ञात है कार्यपुस्तिका के रूप में जहां प्रत्येक कार्यपुस्तिका में एक या अधिक कार्यपत्रक हो सकते हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xls/) . |
| Xlsb | `2` | .XLSB एक्सेल प्रारूप का प्रतिनिधित्व करता है। XLSB फ़ाइल प्रारूप एक्सेल बाइनरी फ़ाइल प्रारूप को निर्दिष्ट करता है, जो रिकॉर्ड और संरचनाओं का एक संग्रह है जो एक्सेल कार्यपुस्तिका सामग्री को निर्दिष्ट करता है। सामग्री में संख्याओं, पाठ, या की असंरचित या अर्ध-संरचित तालिकाएँ शामिल हो सकती हैं। संख्या और पाठ, सूत्र, बाहरी डेटा कनेक्शन, चार्ट और चित्र दोनों। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xlsb/) . |
| Xlsx | `3` | .XLSX एक्सेल प्रारूप का प्रतिनिधित्व करता है। XLSX माइक्रोसॉफ्ट एक्सेल दस्तावेज़ों के लिए प्रसिद्ध प्रारूप है जिसे माइक्रोसॉफ्ट द्वारा माइक्रोसॉफ्ट ऑफिस 2007 के रिलीज के साथ पेश किया गया था। के भाग 2 में उल्लिखित ओपन पैकेजिंग सम्मेलनों के अनुसार आयोजित संरचना के आधार पर OOXML मानक ECMA-376, नया प्रारूप एक ज़िप पैकेज है जिसमें कई XML फाइलें हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xlsx/) . |
| Xlsm | `4` | .XLSM एक्सेल प्रारूप का प्रतिनिधित्व करता है। XLSM एक्सटेंशन वाली फाइलें एक प्रकार की स्प्रेशीट फाइलें हैं जो मैक्रोज़ का समर्थन करती हैं। आवेदन के दृष्टिकोण से, एक मैक्रो निर्देशों का सेट है जो प्रक्रियाओं को स्वचालित करने के लिए उपयोग किया जाता है। एक मैक्रो का उपयोग रिकॉर्ड करने के लिए किया जाता है चरण जो बार-बार किए जाते हैं और मैक्रो को फिर से चलाकर क्रियाओं को करने में सुविधा प्रदान करते हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xlsm/) . |
| Xltx | `5` | .XLTX एक्सेल प्रारूप का प्रतिनिधित्व करता है। XLTX एक्सटेंशन वाली फाइलें माइक्रोसॉफ्ट एक्सेल टेम्पलेट फाइलों का प्रतिनिधित्व करती हैं जो कि ऑफिस ओपनएक्सएमएल फाइल प्रारूप विनिर्देशों पर आधारित हैं। XLTX फ़ाइल में निर्दिष्ट समान सेटिंग्स. इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xltx/) . |
| Xltm | `6` | .XLTM एक्सेल प्रारूप का प्रतिनिधित्व करता है। XLTM फ़ाइल एक्सटेंशन उन फ़ाइलों का प्रतिनिधित्व करता है जो Microsoft Excel द्वारा मैक्रो-सक्षम टेम्पलेट फ़ाइलों के रूप में उत्पन्न होती हैं। XLTM फाइलें संरचना में XLTX के समान हैं, इसके अलावा बाद में टेम्पलेट फ़ाइलों को बनाने का समर्थन नहीं करता है मैक्रोज़. ऐसी टेम्पलेट फ़ाइलों का उपयोग मैक्रोज़ के साथ लेआउट, फ़ॉर्मेटिंग और अन्य सेटिंग्स को उत्पन्न करने और सेट करने के लिए किया जाता है ताकि समान XLSX फ़ाइलें बनाने में सुविधा हो। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xltm/) . |
| Ods | `7` | Opendocument स्प्रेडशीट प्रारूप का प्रतिनिधित्व करता है। ODS एक्सटेंशन वाली फाइलें OpenDocument स्प्रेडशीट दस्तावेज़ प्रारूप के लिए हैं जो उपयोगकर्ता द्वारा संपादन योग्य हैं। डेटा को ODF फ़ाइल के अंदर पंक्तियों और स्तंभों में संग्रहीत किया जाता है। यह XML-आधारित प्रारूप है और कई उपप्रकारों में से एक है। ओपन डॉक्यूमेंट फॉर्मेट्स (ओडीएफ) परिवार में। इस फाइल फॉर्मेट के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/ods/) . |
| Xlt | `8` | .XLT एक्सेल प्रारूप का प्रतिनिधित्व करता है। .XLT एक्सटेंशन वाली फाइलें माइक्रोसॉफ्ट एक्सेल के साथ बनाई गई टेम्पलेट फाइलें हैं जो एक स्प्रेडशीट एप्लिकेशन है जो माइक्रोसॉफ्ट ऑफिस सूट के हिस्से के रूप में आती है। माइक्रोसॉफ्ट ऑफिस 97-2003 नई एक्सएलटी फाइलों को खोलने के साथ-साथ खोलने का समर्थन करता है। ये. एक्सेल का नवीनतम संस्करण अभी भी इस पुराने स्वरूप वाली टेम्पलेट फ़ाइलों को खोलने में सक्षम है. इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xlt/) . |

### यह सभी देखें

* नाम स्थान [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->