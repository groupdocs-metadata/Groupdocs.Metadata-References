---
title: RawIFD2Package
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents IFD1 tags.
type: docs
weight: 3400
url: /net/groupdocs.metadata.formats.raw/rawifd2package/
---
## RawIFD2Package class

Represents IFD1 tags.

```csharp
public sealed class RawIFD2Package : RawDictionaryBasePackage
```

## Properties

| Name | Description |
| --- | --- |
| [BitsPerSample](../../groupdocs.metadata.formats.raw/rawifd2package/bitspersample) { get; } | Gets the image BitsPerSample. |
| [Compression](../../groupdocs.metadata.formats.raw/rawifd2package/compression) { get; } | Gets the image Compression. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [ImageHeight](../../groupdocs.metadata.formats.raw/rawifd2package/imageheight) { get; } | Gets the image height. |
| [ImageWidth](../../groupdocs.metadata.formats.raw/rawifd2package/imagewidth) { get; } | Gets the image width. |
| [Item](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/item) { get; } | Gets the Raw tag with the specified id. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PhotometricInterpretation](../../groupdocs.metadata.formats.raw/rawifd2package/photometricinterpretation) { get; } | Gets the image PhotometricInterpretation. |
| [PlanarConfiguration](../../groupdocs.metadata.formats.raw/rawifd2package/planarconfiguration) { get; } | Gets the PlanarConfiguration. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [RowPerStrip](../../groupdocs.metadata.formats.raw/rawifd2package/rowperstrip) { get; } | Gets the RowPerStrip. |
| [SamplesPerPixel](../../groupdocs.metadata.formats.raw/rawifd2package/samplesperpixel) { get; } | Gets the SamplesPerPixel. |
| [StripByteCounts](../../groupdocs.metadata.formats.raw/rawifd2package/stripbytecounts) { get; } | Gets the StripByteCounts. |
| [StripOffset](../../groupdocs.metadata.formats.raw/rawifd2package/stripoffset) { get; } | Gets the image StripOffset. |
| [Unknown1](../../groupdocs.metadata.formats.raw/rawifd2package/unknown1) { get; } | Gets the Unknown1. |
| [Unknown2](../../groupdocs.metadata.formats.raw/rawifd2package/unknown2) { get; } | Gets the Unknown2. |
| [Unknown3](../../groupdocs.metadata.formats.raw/rawifd2package/unknown3) { get; } | Gets the Unknown3. |

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

* class [RawDictionaryBasePackage](../rawdictionarybasepackage)
* namespace [GroupDocs.Metadata.Formats.Raw](../../groupdocs.metadata.formats.raw)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
