---
title: XmpBasicPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents the XMP basic namespace.
type: docs
weight: 4380
url: /net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/
---
## XmpBasicPackage class

Represents the XMP basic namespace.

```csharp
public sealed class XmpBasicPackage : XmpPackage
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpBasicPackage](xmpbasicpackage)() | Initializes a new instance of the [`XmpBasicPackage`](../xmpbasicpackage) class. |

## Properties

| Name | Description |
| --- | --- |
| [BaseUrl](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/baseurl) { get; set; } | Gets or sets the base URL for relative URLs in the document content. If this document contains Internet links, and those links are relative, they are relative to this base URL. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [CreateDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/createdate) { get; set; } | Gets or sets the date and time the resource was created. |
| [CreatorTool](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/creatortool) { get; set; } | Gets or sets the name of the tool used to create the resource. |
| [Identifiers](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/identifiers) { get; set; } | Gets or sets an unordered array of text strings that unambiguously identify the resource within a given context. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Label](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/label) { get; set; } | Gets or sets a word or short phrase that identifies the resource as a member of a user-defined collection. |
| [MetadataDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/metadatadate) { get; set; } | Gets or sets the date and time that any metadata for this resource was last changed. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [ModifyDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/modifydate) { get; set; } | Gets or sets the date and time the resource was last modified. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Gets the namespace URI. |
| [Nickname](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/nickname) { get; set; } | Gets or sets a short informal name for the resource. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Gets the xmlns prefix. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Rating](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/rating) { get; set; } | Gets or sets a user-assigned rating for this file. The value shall be -1 or in the range [0..5], where -1 indicates “rejected” and 0 indicates “unrated”. |
| [Thumbnails](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/thumbnails) { get; set; } | Gets or sets an array of thumbnail images for the file, which can differ in characteristics such as size or image encoding. |
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
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/set#set_7)(string, string) | Adds string property. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Sets the value inherited from [`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Sets the value inherited from [`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Sets the value inherited from [`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

## Fields

| Name | Description |
| --- | --- |
| const [RatingMax](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingmax) | Rating max value. |
| const [RatingMin](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingmin) | Rating min value. |
| const [RatingRejected](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingrejected) | Rating rejected value. |

### See Also

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* namespace [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
