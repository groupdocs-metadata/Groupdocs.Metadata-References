---
title: XmpArray
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: XMP सरण के लए आधर अमूर्तत क प्रतनधत्व करत है
type: docs
weight: 3250
url: /hi/net/groupdocs.metadata.standards.xmp/xmparray/
---
## XmpArray class

XMP सरणी के लिए आधार अमूर्तता का प्रतिनिधित्व करता है।

```csharp
public class XmpArray : XmpValueBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [XmpArray](xmparray#constructor)(XmpArrayType, XmpComplexType[]) | का एक नया उदाहरण प्रारंभ करता है[`XmpArray`](../xmparray) वर्ग. |
| [XmpArray](xmparray#constructor_1)(XmpArrayType, XmpValueBase[]) | का एक नया उदाहरण प्रारंभ करता है[`XmpArray`](../xmparray) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [ArrayType](../../groupdocs.metadata.standards.xmp/xmparray/arraytype) { get; } | XMP सरणी का प्रकार प्राप्त करता है। |
| [RawValue](../../groupdocs.metadata.common/propertyvalue/rawvalue) { get; } | अपरिष्कृत मान प्राप्त करता है। |
| [Type](../../groupdocs.metadata.common/propertyvalue/type) { get; } | हो जाता है[`MetadataPropertyType`](../../groupdocs.metadata.common/metadatapropertytype) . |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from_2)(DateTime[], XmpArrayType) | एक बनाता है[`XmpArray`](../xmparray) उदाहरण एक दिनांक सरणी बनाते हैं। |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from)(double[], XmpArrayType) | एक बनाता है[`XmpArray`](../xmparray) उदाहरण एक डबल सरणी बनाते हैं। |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from_1)(int[], XmpArrayType) | एक बनाता है[`XmpArray`](../xmparray) उदाहरण एक पूर्णांक सरणी बनाते हैं। |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from_3)(string[], XmpArrayType) | एक बनाता है[`XmpArray`](../xmparray) उदाहरण एक स्ट्रिंग सरणी बनाते हैं। |
| static [From&lt;T&gt;](../../groupdocs.metadata.standards.xmp/xmparray/from#from_4)(T[], XmpArrayType) | एक बनाता है[`XmpArray`](../xmparray)उदाहरण की एक सरणी बनाते हैं[`XmpComplexType`](../xmpcomplextype) . |
| [AcceptValue](../../groupdocs.metadata.common/propertyvalue/acceptvalue)(ValueAcceptor) | कस्टम का उपयोग करके गुण मान निकालता है[`ValueAcceptor`](../../groupdocs.metadata.common/valueacceptor) . |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmparray/getxmprepresentation)() | XMP मान को xml प्रतिनिधित्व में कनवर्ट करता है। |
| [ToArray&lt;TElement&gt;](../../groupdocs.metadata.common/propertyvalue/toarray)() | गुण मान को निर्दिष्ट प्रकार की सरणी में कनवर्ट करता है। |
| [ToClass&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/toclass)() | गुण मान को संदर्भ प्रकार में कनवर्ट करता है. |
| [ToPlatformArray&lt;T&gt;](../../groupdocs.metadata.standards.xmp/xmparray/toplatformarray)() | परिवर्तित करता है[`XmpArray`](../xmparray) एक प्लेटफ़ॉर्म-विशिष्ट सरणी के लिए. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpvaluebase/tostring)() | एक स्ट्रिंग लौटाता है जो गुण मान का प्रतिनिधित्व करता है। |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)() | गुण मान को मान प्रकार में कनवर्ट करता है. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)(T) | गुण मान को मान प्रकार में कनवर्ट करता है. |

### यह सभी देखें

* class [XmpValueBase](../xmpvaluebase)
* नाम स्थान [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->