---
title: XmpColorantBase
second_title: GroupDocs.Metadata for .NET API Reference
description: A structure containing the characteristics of a colorant swatch used in a document.
type: docs
weight: 4630
url: /net/groupdocs.metadata.standards.xmp/xmpcolorantbase/
---
## XmpColorantBase class

A structure containing the characteristics of a colorant (swatch) used in a document.

```csharp
public class XmpColorantBase : XmpComplexType
```

## Properties

| Name | Description |
| --- | --- |
| [ColorType](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/colortype) { get; set; } | Gets or sets the type of color. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [Mode](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/mode) { get; } | Gets the colour space in which the colour is defined. One of: CMYK, RGB, LAB. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Gets the namespace URIs that are used in the [`XmpComplexType`](../xmpcomplextype) instance. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Gets the namespace prefixes that are used in the [`XmpComplexType`](../xmpcomplextype) instance. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [SwatchName](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/swatchname) { get; set; } | Gets or sets the name of the swatch. |

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
