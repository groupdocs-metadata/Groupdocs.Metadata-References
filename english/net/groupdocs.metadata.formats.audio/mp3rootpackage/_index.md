---
title: MP3RootPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents the root package allowing working with metadata in an MP3 audio.
type: docs
weight: 630
url: /net/groupdocs.metadata.formats.audio/mp3rootpackage/
---
## MP3RootPackage class

Represents the root package allowing working with metadata in an MP3 audio.

```csharp
public class MP3RootPackage : RootMetadataPackage, IXmp
```

## Properties

| Name | Description |
| --- | --- |
| [ApeV2](../../groupdocs.metadata.formats.audio/mp3rootpackage/apev2) { get; } | Gets the APE v2 metadata. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Gets the file type metadata package. |
| [ID3V1](../../groupdocs.metadata.formats.audio/mp3rootpackage/id3v1) { get; set; } | Gets or sets the ID3v1 metadata tag. Please find more information at [http://id3.org/ID3v1](http://id3.org/ID3v1). |
| [ID3V2](../../groupdocs.metadata.formats.audio/mp3rootpackage/id3v2) { get; set; } | Gets or sets the ID3v2 metadata tag. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Lyrics3V2](../../groupdocs.metadata.formats.audio/mp3rootpackage/lyrics3v2) { get; set; } | Gets or sets the Lyrics3v2 metadata tag. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [MpegAudioPackage](../../groupdocs.metadata.formats.audio/mp3rootpackage/mpegaudiopackage) { get; } | Gets the MPEG audio metadata package. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [XmpPackage](../../groupdocs.metadata.formats.audio/mp3rootpackage/xmppackage) { get; set; } | Gets or sets the XMP metadata package. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [RemoveApeV2](../../groupdocs.metadata.formats.audio/mp3rootpackage/removeapev2)() | Removes the APEv2 audio tag. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| override [Sanitize](../../groupdocs.metadata.formats.audio/mp3rootpackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Working with MP3 metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+MP3+metadata)
* [Working with XMP metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### See Also

* class [RootMetadataPackage](../../groupdocs.metadata.common/rootmetadatapackage)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* namespace [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
