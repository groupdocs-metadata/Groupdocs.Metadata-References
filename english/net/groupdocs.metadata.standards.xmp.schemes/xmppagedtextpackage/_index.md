---
title: XmpPagedTextPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents the XMP PagedText package.
type: docs
weight: 4430
url: /net/groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/
---
## XmpPagedTextPackage class

Represents the XMP Paged-Text package.

```csharp
public sealed class XmpPagedTextPackage : XmpPackage
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpPagedTextPackage](xmppagedtextpackage)() | Initializes a new instance of the [`XmpPagedTextPackage`](../xmppagedtextpackage) class. |

## Properties

| Name | Description |
| --- | --- |
| [Colorants](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/colorants) { get; set; } | Gets or sets an ordered array of colorants (swatches) that are used in the document (including any in contained documents). |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Fonts](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/fonts) { get; set; } | Gets or sets an unordered array of fonts that are used in the document (including any in contained documents). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MaxPageSize](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/maxpagesize) { get; set; } | Gets or sets the size of the largest page in the document (including any in contained documents). |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Gets the namespace URI. |
| [NumberOfPages](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/numberofpages) { get; set; } | Gets or sets the number of pages in the document. |
| [PlateNames](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/platenames) { get; set; } | Gets or set an ordered array of plate names that are needed to print the document (including any in contained documents). |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Gets the xmlns prefix. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Gets the XML namespace. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Removes all XMP properties. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Converts the XMP value to the XML representation. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Removes the property with the specified name. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Sets boolean property. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | Sets DateTime property. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Sets double property. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Sets integer property. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/set#set_7)(string, string) | Sets string property. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/set#set_2)(string, XmpArray) | Sets the value inherited from [`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Sets the value inherited from [`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Sets the value inherited from [`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### See Also

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* namespace [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
