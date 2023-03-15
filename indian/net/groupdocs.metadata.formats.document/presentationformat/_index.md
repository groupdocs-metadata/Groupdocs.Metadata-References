---
title: PresentationFormat
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: प्रस्तुतकरण के वभन्न उपप्ररूपं क परभषत करत है
type: docs
weight: 1070
url: /hi/net/groupdocs.metadata.formats.document/presentationformat/
---
## PresentationFormat enumeration

प्रस्तुतिकरण के विभिन्न उपप्रारूपों को परिभाषित करता है।

```csharp
public enum PresentationFormat
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| Unknown | `0` | प्रारूप पहचाना नहीं गया है। |
| Ppt | `1` | .PPT PowerPoint प्रारूप का प्रतिनिधित्व करता है। PPT एक्सटेंशन वाली एक फ़ाइल PowerPoint फ़ाइल का प्रतिनिधित्व करती है जिसमें स्लाइड शो के रूप में प्रदर्शित करने के लिए स्लाइड्स का एक संग्रह होता है। यह Microsoft PowerPoint 97-2003 द्वारा उपयोग किए जाने वाले बाइनरी फ़ाइल प्रारूप को निर्दिष्ट करता है। एक PPT फ़ाइल में कई अलग-अलग प्रकार की जानकारी हो सकती है जैसे कि टेक्स्ट, बुलेटेड पॉइंट, इमेज, मल्टीमीडिया और अन्य एम्बेडेड OLE ऑब्जेक्ट. इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/ppt/) . |
| Pptx | `2` | .PPTX PowerPoint प्रारूप का प्रतिनिधित्व करता है। PPTX एक्सटेंशन वाली फ़ाइलें लोकप्रिय Microsoft PowerPoint एप्लिकेशन के साथ बनाई गई प्रस्तुति फ़ाइलें हैं। प्रस्तुति फ़ाइल प्रारूप PPT के पिछले संस्करण के विपरीत जो बाइनरी था, PPTX प्रारूप Microsoft PowerPoint खुली XML प्रस्तुति फ़ाइल पर आधारित है प्रारूप. इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/pptx/) . |
| Potm | `3` | .POTM पॉवरपॉइंट प्रारूप का प्रतिनिधित्व करता है। POTM एक्सटेंशन वाली फाइलें मैक्रोज़ के समर्थन के साथ Microsoft PowerPoint टेम्पलेट फाइलें हैं। POTM फाइलें PowerPoint 2007 या इसके बाद के संस्करण के साथ बनाई गई हैं और इसमें डिफ़ॉल्ट सेटिंग्स हैं जिनका उपयोग आगे की प्रस्तुति फ़ाइलों को बनाने के लिए किया जा सकता है। और जानें इस फ़ाइल स्वरूप के बारे में[यहाँ](https://wiki.fileformat.com/presentation/potm/) . |
| Potx | `4` | .POTX PowerPoint प्रारूप का प्रतिनिधित्व करता है। .POTX एक्सटेंशन वाली फाइलें Microsoft PowerPoint टेम्पलेट प्रस्तुतियों का प्रतिनिधित्व करती हैं जो Microsoft PowerPoint 2007 और इसके बाद के संस्करण के साथ बनाई गई हैं। यह प्रारूप POT फ़ाइल प्रारूप को बदलने के लिए बनाया गया था जो बाइनरी फ़ाइल प्रारूप पर आधारित है और है PowerPoint 97-2003 के साथ समर्थित. इस फ़ाइल स्वरूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/potx/) . |
| Pptm | `5` | .PPTM PowerPoint प्रारूप का प्रतिनिधित्व करता है। PPTM एक्सटेंशन वाली फ़ाइलें मैक्रो-सक्षम प्रस्तुति फ़ाइलें हैं जो Microsoft PowerPoint 2007 या उच्चतर संस्करणों के साथ बनाई गई हैं। वे PPTX फ़ाइलों के समान हैं, इस अंतर के साथ कि पार्श्व मैक्रोज़ को निष्पादित नहीं कर सकते हैं, हालांकि वे मैक्रोज़ हो सकते हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/pptm/) . |
| Pps | `6` | .PPS PowerPoint प्रारूप का प्रतिनिधित्व करता है। PPS, PowerPoint स्लाइड शो, फ़ाइलें स्लाइड शो उद्देश्य के लिए Microsoft PowerPoint का उपयोग करके बनाई गई हैं। PPS फ़ाइल पढ़ना और बनाना Microsoft PowerPoint 97-2003 द्वारा समर्थित है. इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/pps/) . |
| Ppsx | `7` | .PPSX PowerPoint प्रारूप का प्रतिनिधित्व करता है। PPSX, पावर प्वाइंट स्लाइड शो, फ़ाइलें स्लाइड शो के उद्देश्य के लिए Microsoft PowerPoint 2007 और इसके बाद के संस्करण का उपयोग करके बनाई गई हैं। यह PPS फ़ाइल प्रारूप का एक अद्यतन है जो Microsoft PowerPoint 97-2003 संस्करणों द्वारा समर्थित था . इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/ppsx/) . |
| Ppsm | `8` | .PPSM PowerPoint प्रारूप का प्रतिनिधित्व करता है। PPSM एक्सटेंशन वाली फाइलें Microsoft PowerPoint 2007 या उच्चतर के साथ बनाए गए मैक्रो-सक्षम स्लाइड शो फ़ाइल प्रारूप का प्रतिनिधित्व करती हैं। एक अन्य समान फ़ाइल प्रारूप PPTM है जो Microsoft PowerPoint के साथ संपादन योग्य प्रारूप में खुलने में भिन्न है स्लाइड शो इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/ppsm/) . |
| Pot | `9` | .POT PowerPoint प्रारूप का प्रतिनिधित्व करता है। .POT एक्सटेंशन वाली फ़ाइलें PowerPoint 97-2003 संस्करणों द्वारा बनाई गई Microsoft PowerPoint टेम्पलेट फ़ाइलों का प्रतिनिधित्व करती हैं। Microsoft PowerPoint के इन संस्करणों के साथ बनाई गई फ़ाइलें Office OpenXML फ़ाइल स्वरूपों में बनाई गई फ़ाइलों की तुलना में बाइनरी प्रारूप में हैं PowerPoint के उच्चतर संस्करणों का उपयोग कर रहे हैं. इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/pot/) . |

### यह सभी देखें

* नाम स्थान [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->