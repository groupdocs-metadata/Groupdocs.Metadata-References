---
title: XmpRenditionClass
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents XMP RenditionClass.
type: docs
weight: 5100
url: /net/groupdocs.metadata.standards.xmp/xmprenditionclass/
---
## XmpRenditionClass class

Represents XMP RenditionClass.

```csharp
public sealed class XmpRenditionClass : XmpText
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpRenditionClass](xmprenditionclass)(params string[]) | Initializes a new instance of the [`XmpRenditionClass`](../xmprenditionclass) class. |

## Properties

| Name | Description |
| --- | --- |
| [RawValue](../../groupdocs.metadata.common/propertyvalue/rawvalue) { get; } | Gets the raw value. |
| [Type](../../groupdocs.metadata.common/propertyvalue/type) { get; } | Gets the [`MetadataPropertyType`](../../groupdocs.metadata.common/metadatapropertytype). |
| [Value](../../groupdocs.metadata.standards.xmp/xmptext/value) { get; } | Gets the value. |

## Methods

| Name | Description |
| --- | --- |
| [AcceptValue](../../groupdocs.metadata.common/propertyvalue/acceptvalue)(ValueAcceptor) | Extracts the property value using a custom [`ValueAcceptor`](../../groupdocs.metadata.common/valueacceptor). |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmptext/getxmprepresentation)() | Returns string contained value in XMP format. |
| [ToArray&lt;TElement&gt;](../../groupdocs.metadata.common/propertyvalue/toarray)() | Converts the property value to an array of the specified type. |
| [ToClass&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/toclass)() | Converts the property value to a reference type. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpvaluebase/tostring)() | Returns a string that represents the property value. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)() | Converts the property value to a value type. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)(T) | Converts the property value to a value type. |

## Fields

| Name | Description |
| --- | --- |
| const [Default](../../groupdocs.metadata.standards.xmp/xmprenditionclass/default) | The master resource; no additional tokens allowed. |
| const [Draft](../../groupdocs.metadata.standards.xmp/xmprenditionclass/draft) | A review rendition. |
| const [LowRes](../../groupdocs.metadata.standards.xmp/xmprenditionclass/lowres) | A low-resolution, full-size stand-in. |
| const [Proof](../../groupdocs.metadata.standards.xmp/xmprenditionclass/proof) | A review proof. |
| const [Screen](../../groupdocs.metadata.standards.xmp/xmprenditionclass/screen) | Screen resolution or Web rendition. |
| const [Thumbnail](../../groupdocs.metadata.standards.xmp/xmprenditionclass/thumbnail) | A simplified or reduced preview. Additional tokens can provide characteristics. The recommended order is thumbnail:format:size:colorspace. |

### See Also

* class [XmpText](../xmptext)
* namespace [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
