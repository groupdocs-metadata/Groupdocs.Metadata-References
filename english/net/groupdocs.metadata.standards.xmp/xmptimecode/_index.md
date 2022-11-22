---
title: XmpTimecode
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents a timecode value in a video.
type: docs
weight: 3600
url: /net/groupdocs.metadata.standards.xmp/xmptimecode/
---
## XmpTimecode class

Represents a timecode value in a video.

```csharp
public sealed class XmpTimecode : XmpComplexType
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpTimecode](xmptimecode#constructor)() | Initializes a new instance of the [`XmpTimecode`](../xmptimecode) class. |
| [XmpTimecode](xmptimecode#constructor_1)(XmpTimeFormat, string) | Initializes a new instance of the [`XmpTimecode`](../xmptimecode) class. |

## Properties

| Name | Description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Gets the namespace URIs that are used in the [`XmpComplexType`](../xmpcomplextype) instance. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Gets the namespace prefixes that are used in the [`XmpComplexType`](../xmpcomplextype) instance. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [TimeFormat](../../groupdocs.metadata.standards.xmp/xmptimecode/timeformat) { get; set; } | Gets or sets the format used in the time value. |
| [TimeValue](../../groupdocs.metadata.standards.xmp/xmptimecode/timevalue) { get; set; } | Gets or sets the time value in the specified format. Time values use a colon delimiter in all formats except 2997drop and 5994drop, which uses a semicolon. The four fields indicate hours, minutes, seconds, and frames: hh:mm:ss:ff |

## Methods

| Name | Description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | Gets the namespace URI associated with the specified prefix. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | Returns string contained value in XMP format. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| [SetTimeFormat](../../groupdocs.metadata.standards.xmp/xmptimecode/settimeformat)(XmpTimeFormat) | Sets the time format. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | Returns a String that represents this instance. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### See Also

* class [XmpComplexType](../xmpcomplextype)
* namespace [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
