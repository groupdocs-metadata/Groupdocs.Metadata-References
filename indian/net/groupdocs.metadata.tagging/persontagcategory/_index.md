---
title: PersonTagCategory
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: उन टैग्स क प्रदन करत है ज फ़इल य बद्धक समग्र नर्मण में यगदन करने वले लगं के बरे में जनकर रखने वले मेटडेट गुणं क चह्नत करते हैं ये टैग आपक दस्तवेज़ नर्मत संपदक य यहं तक क उस ग्रहक क खजने में मदद कर सकते हैं जसके लए कम कय गय थ श्रेण के नम के बवजूद टैग के सथ चह्नत कुछ मेटडेट गुणं में कस व्यक्त के नम के बजय कंपन क नम ह सकत है
type: docs
weight: 3690
url: /hi/net/groupdocs.metadata.tagging/persontagcategory/
---
## PersonTagCategory class

उन टैग्स को प्रदान करता है जो फ़ाइल या बौद्धिक सामग्री निर्माण में योगदान करने वाले लोगों के बारे में जानकारी रखने वाले मेटाडेटा गुणों को चिह्नित करते हैं। ये टैग आपको दस्तावेज़ निर्माता, संपादक या यहां तक कि उस ग्राहक को खोजने में मदद कर सकते हैं जिसके लिए काम किया गया था। श्रेणी के नाम के बावजूद टैग के साथ चिह्नित कुछ मेटाडेटा गुणों में किसी व्यक्ति के नाम के बजाय कंपनी का नाम हो सकता है।

```csharp
public class PersonTagCategory : TagCategory
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Client](../../groupdocs.metadata.tagging/persontagcategory/client) { get; } | उस क्लाइंट के बारे में जानकारी लेबल करने वाला टैग प्राप्त करता है जिसके लिए फ़ाइल/बौद्धिक सामग्री बनाई गई थी। |
| [Contributor](../../groupdocs.metadata.tagging/persontagcategory/contributor) { get; } | उस टैग को प्राप्त करता है जो किसी ऐसे व्यक्ति के नाम वाली संपत्ति को लेबल करता है जिसने किसी तरह फ़ाइल निर्माण में योगदान दिया है। कृपया ध्यान दें कि इस श्रेणी से अधिक विशिष्ट टैग के साथ चिह्नित मेटाडेटा गुणों के लिए टैग लागू नहीं किया गया है। उदाहरण के लिए यदि कोई संपत्ति निर्माता टैग के साथ लेबल की गई है। |
| [Creator](../../groupdocs.metadata.tagging/persontagcategory/creator) { get; } | उस टैग को प्राप्त करता है जो फ़ाइल/दस्तावेज़ के मूल लेखक को दर्शाता है। |
| [Editor](../../groupdocs.metadata.tagging/persontagcategory/editor) { get; } | वह टैग प्राप्त करता है जो किसी फ़ाइल को संपादित करने वाले व्यक्ति को लेबल करता है। टैग आमतौर पर अंतिम संपादक के बारे में जानकारी वाली संपत्ति को चिह्नित करने के लिए उपयोग किया जाता है। |
| [Manager](../../groupdocs.metadata.tagging/persontagcategory/manager) { get; } | वह टैग प्राप्त करता है जो किसी फ़ाइल की निर्माण प्रक्रिया को प्रबंधित करने वाले व्यक्ति के बारे में जानकारी को लेबल करता है. |
| [Model](../../groupdocs.metadata.tagging/persontagcategory/model) { get; } | वह टैग प्राप्त करता है जो उस व्यक्ति के बारे में जानकारी दर्शाता है जिसके बारे में फ़ाइल की सामग्री है। उन फ़ोटो के लिए जो इमेज में दिखाया गया व्यक्ति है. |
| [Publisher](../../groupdocs.metadata.tagging/persontagcategory/publisher) { get; } | फ़ाइल उपलब्ध कराने के लिए जिम्मेदार व्यक्ति को चिह्नित करने वाला टैग प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [ToString](../../groupdocs.metadata.tagging/tagcategory/tostring)() | एक स्ट्रिंग लौटाता है जो वर्तमान वस्तु का प्रतिनिधित्व करता है। |

### यह सभी देखें

* class [TagCategory](../tagcategory)
* नाम स्थान [GroupDocs.Metadata.Tagging](../../groupdocs.metadata.tagging)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->