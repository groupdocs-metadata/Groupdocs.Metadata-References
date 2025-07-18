---
title: XmpTrailerPI
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents XMP trailer processing instruction.
type: docs
weight: 5180
url: /net/groupdocs.metadata.standards.xmp/xmptrailerpi/
---
## XmpTrailerPI class

Represents XMP trailer processing instruction.

```csharp
public sealed class XmpTrailerPI : IXmpType
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpTrailerPI](xmptrailerpi#constructor)() | Initializes a new instance of the [`XmpTrailerPI`](../xmptrailerpi) class. |
| [XmpTrailerPI](xmptrailerpi#constructor_1)(bool) | Initializes a new instance of the [`XmpTrailerPI`](../xmptrailerpi) class. |

## Properties

| Name | Description |
| --- | --- |
| [IsWritable](../../groupdocs.metadata.standards.xmp/xmptrailerpi/iswritable) { get; } | Indicates whether form may be modified in-place. |

## Methods

| Name | Description |
| --- | --- |
| [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmptrailerpi/getxmprepresentation)() | Converts XMP value to the xml representation. |

### Remarks

The end="w" or end="r" portion shall be used by packet scanning processors to determine whether the XMP may be modified in-place.

### Examples

Allowed forms of the trailer PI:

### See Also

* interface [IXmpType](../ixmptype)
* namespace [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
