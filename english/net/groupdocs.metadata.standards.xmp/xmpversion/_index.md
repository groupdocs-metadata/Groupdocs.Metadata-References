---
title: XmpVersion
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents a version of a document.
type: docs
weight: 5080
url: /net/groupdocs.metadata.standards.xmp/xmpversion/
---
## XmpVersion class

Represents a version of a document.

```csharp
public sealed class XmpVersion : XmpComplexType
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpVersion](xmpversion)() | Initializes a new instance of the [`XmpVersion`](../xmpversion) class. |

## Properties

| Name | Description |
| --- | --- |
| [Comments](../../groupdocs.metadata.standards.xmp/xmpversion/comments) { get; set; } | Gets or sets the comments concerning what was changed. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Event](../../groupdocs.metadata.standards.xmp/xmpversion/event) { get; set; } | Gets or sets the high-level, formal description of what operation the user performed. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [Modifier](../../groupdocs.metadata.standards.xmp/xmpversion/modifier) { get; set; } | Gets or sets the person who modified this version. |
| [ModifyDate](../../groupdocs.metadata.standards.xmp/xmpversion/modifydate) { get; set; } | Gets or sets the date on which this version was checked in. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Gets the namespace URIs that are used in the [`XmpComplexType`](../xmpcomplextype) instance. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Gets the namespace prefixes that are used in the [`XmpComplexType`](../xmpcomplextype) instance. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [VersionNumber](../../groupdocs.metadata.standards.xmp/xmpversion/versionnumber) { get; set; } | Gets or sets the new version number. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | Gets the namespace URI associated with the specified prefix. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | Returns string contained value in XMP format. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | Returns a String that represents this instance. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### See Also

* class [XmpComplexType](../xmpcomplextype)
* namespace [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
