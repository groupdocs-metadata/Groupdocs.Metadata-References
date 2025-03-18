---
title: Cr2AFInfo2Package
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents Canon MakerNotes tags.
type: docs
weight: 2740
url: /net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/
---
## Cr2AFInfo2Package class

Represents Canon MakerNotes tags.

```csharp
public sealed class Cr2AFInfo2Package : RawDictionaryBasePackage
```

## Constructors

| Name | Description |
| --- | --- |
| [Cr2AFInfo2Package](cr2afinfo2package)() | Initializes a new instance of the [`Cr2AFInfo2Package`](../cr2afinfo2package) class. |

## Properties

| Name | Description |
| --- | --- |
| [AFAreaHeights](../../groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/afareaheights) { get; } | Gets the AFAreaHeights. |
| [AFAreaMode](../../groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/afareamode) { get; } | Gets the AFAreaMode. |
| [AFAreaWidths](../../groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/afareawidths) { get; } | Gets the AFAreaWidths. |
| [AFAreaXPositions](../../groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/afareaxpositions) { get; } | Gets the AFAreaXPositions. |
| [AFAreaYPositions](../../groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/afareaypositions) { get; } | Gets the AFAreaYPositions. |
| [AFImageHeight](../../groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/afimageheight) { get; } | Gets the AFImageHeight. |
| [AFImageWidth](../../groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/afimagewidth) { get; } | Gets the AFImageWidth. |
| [AFInfoSize](../../groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/afinfosize) { get; } | Gets the AFInfoSize. |
| [AFPointsInFocus](../../groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/afpointsinfocus) { get; } | Gets the AFPointsInFocus. |
| [AFPointsSelected](../../groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/afpointsselected) { get; } | Gets the AFPointsSelected. |
| [CanonImageHeight](../../groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/canonimageheight) { get; } | Gets the CanonImageHeight. |
| [CanonImageWidth](../../groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/canonimagewidth) { get; } | Gets the CanonImageWidth. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Item](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/item) { get; } | Gets the Raw tag with the specified id. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [NumAFPoints](../../groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/numafpoints) { get; } | Gets the NumAFPoints. |
| [PrimaryAFPoint](../../groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/primaryafpoint) { get; } | Gets the PrimaryAFPoint. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [ValidAFPoints](../../groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/validafpoints) { get; } | Gets the ValidAFPoints. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Clear](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/clear)() | Removes all Raw tags stored in the package. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [Remove](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/remove)(uint) | Removes the property with the specified id. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [Set](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/set)(RawTag) | Adds or replaces the specified tag. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| [ToList](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/tolist)() | Creates a list from the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### See Also

* class [RawDictionaryBasePackage](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage)
* namespace [GroupDocs.Metadata.Formats.Raw.Cr2](../../groupdocs.metadata.formats.raw.cr2)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
