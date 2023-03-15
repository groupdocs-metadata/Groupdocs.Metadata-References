---
title: XmpRenditionClass
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: XMP रेंडशनक्लस क प्रतनधत्व करत है
type: docs
weight: 3530
url: /hi/net/groupdocs.metadata.standards.xmp/xmprenditionclass/
---
## XmpRenditionClass class

XMP रेंडिशनक्लास का प्रतिनिधित्व करता है।

```csharp
public sealed class XmpRenditionClass : XmpText
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [XmpRenditionClass](xmprenditionclass)(params string[]) | का एक नया उदाहरण प्रारंभ करता है[`XmpRenditionClass`](../xmprenditionclass) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [RawValue](../../groupdocs.metadata.common/propertyvalue/rawvalue) { get; } | अपरिष्कृत मान प्राप्त करता है। |
| [Type](../../groupdocs.metadata.common/propertyvalue/type) { get; } | हो जाता है[`MetadataPropertyType`](../../groupdocs.metadata.common/metadatapropertytype) . |
| [Value](../../groupdocs.metadata.standards.xmp/xmptext/value) { get; } | मान प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AcceptValue](../../groupdocs.metadata.common/propertyvalue/acceptvalue)(ValueAcceptor) | कस्टम का उपयोग करके गुण मान निकालता है[`ValueAcceptor`](../../groupdocs.metadata.common/valueacceptor) . |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmptext/getxmprepresentation)() | स्ट्रिंग में मौजूद मान को XMP फ़ॉर्मैट में लौटाता है. |
| [ToArray&lt;TElement&gt;](../../groupdocs.metadata.common/propertyvalue/toarray)() | गुण मान को निर्दिष्ट प्रकार की सरणी में कनवर्ट करता है। |
| [ToClass&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/toclass)() | गुण मान को संदर्भ प्रकार में कनवर्ट करता है. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpvaluebase/tostring)() | एक स्ट्रिंग लौटाता है जो गुण मान का प्रतिनिधित्व करता है। |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)() | गुण मान को मान प्रकार में कनवर्ट करता है. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)(T) | गुण मान को मान प्रकार में कनवर्ट करता है. |

## खेत

| नाम | विवरण |
| --- | --- |
| const [Default](../../groupdocs.metadata.standards.xmp/xmprenditionclass/default) | मास्टर संसाधन; कोई अतिरिक्त टोकन की अनुमति नहीं है। |
| const [Draft](../../groupdocs.metadata.standards.xmp/xmprenditionclass/draft) | एक समीक्षा प्रस्तुति. |
| const [LowRes](../../groupdocs.metadata.standards.xmp/xmprenditionclass/lowres) | कम रिज़ॉल्यूशन वाला, पूर्ण आकार का स्टैंड-इन. |
| const [Proof](../../groupdocs.metadata.standards.xmp/xmprenditionclass/proof) | एक समीक्षा प्रमाण. |
| const [Screen](../../groupdocs.metadata.standards.xmp/xmprenditionclass/screen) | स्क्रीन रिज़ॉल्यूशन या वेब प्रतिपादन। |
| const [Thumbnail](../../groupdocs.metadata.standards.xmp/xmprenditionclass/thumbnail) | एक सरलीकृत या छोटा पूर्वावलोकन। अतिरिक्त टोकन विशेषताएं प्रदान कर सकते हैं। अनुशंसित क्रम थंबनेल है: प्रारूप: आकार: कलरस्पेस. |

### यह सभी देखें

* class [XmpText](../xmptext)
* नाम स्थान [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->