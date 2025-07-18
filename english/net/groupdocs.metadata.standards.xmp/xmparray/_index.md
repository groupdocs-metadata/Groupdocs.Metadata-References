---
title: XmpArray
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents base abstraction for XMP array.
type: docs
weight: 4820
url: /net/groupdocs.metadata.standards.xmp/xmparray/
---
## XmpArray class

Represents base abstraction for XMP array.

```csharp
public class XmpArray : XmpValueBase
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpArray](xmparray#constructor)(XmpArrayType, XmpComplexType[]) | Initializes a new instance of the [`XmpArray`](../xmparray) class. |
| [XmpArray](xmparray#constructor_1)(XmpArrayType, XmpValueBase[]) | Initializes a new instance of the [`XmpArray`](../xmparray) class. |

## Properties

| Name | Description |
| --- | --- |
| [ArrayType](../../groupdocs.metadata.standards.xmp/xmparray/arraytype) { get; } | Gets the type of the XMP array. |
| [RawValue](../../groupdocs.metadata.common/propertyvalue/rawvalue) { get; } | Gets the raw value. |
| [Type](../../groupdocs.metadata.common/propertyvalue/type) { get; } | Gets the [`MetadataPropertyType`](../../groupdocs.metadata.common/metadatapropertytype). |

## Methods

| Name | Description |
| --- | --- |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from_2)(DateTime[], XmpArrayType) | Creates an [`XmpArray`](../xmparray) instance form a date array. |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from)(double[], XmpArrayType) | Creates an [`XmpArray`](../xmparray) instance form a double array. |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from_1)(int[], XmpArrayType) | Creates an [`XmpArray`](../xmparray) instance form an integer array. |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from_3)(string[], XmpArrayType) | Creates an [`XmpArray`](../xmparray) instance form a string array. |
| static [From&lt;T&gt;](../../groupdocs.metadata.standards.xmp/xmparray/from#from_4)(T[], XmpArrayType) | Creates an [`XmpArray`](../xmparray) instance form an array of [`XmpComplexType`](../xmpcomplextype). |
| [AcceptValue](../../groupdocs.metadata.common/propertyvalue/acceptvalue)(ValueAcceptor) | Extracts the property value using a custom [`ValueAcceptor`](../../groupdocs.metadata.common/valueacceptor). |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmparray/getxmprepresentation)() | Converts XMP value to the xml representation. |
| [ToArray&lt;TElement&gt;](../../groupdocs.metadata.common/propertyvalue/toarray)() | Converts the property value to an array of the specified type. |
| [ToClass&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/toclass)() | Converts the property value to a reference type. |
| [ToPlatformArray&lt;T&gt;](../../groupdocs.metadata.standards.xmp/xmparray/toplatformarray)() | Converts the [`XmpArray`](../xmparray) to a platform-specific array. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpvaluebase/tostring)() | Returns a string that represents the property value. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)() | Converts the property value to a value type. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)(T) | Converts the property value to a value type. |

### See Also

* class [XmpValueBase](../xmpvaluebase)
* namespace [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
