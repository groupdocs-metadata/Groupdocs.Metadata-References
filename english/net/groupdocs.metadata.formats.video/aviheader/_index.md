---
title: AviHeader
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents the AVIMAINHEADER structure in an AVI video.
type: docs
weight: 3620
url: /net/groupdocs.metadata.formats.video/aviheader/
---
## AviHeader class

Represents the AVIMAINHEADER structure in an AVI video.

```csharp
public sealed class AviHeader : CustomPackage
```

## Constructors

| Name | Description |
| --- | --- |
| [AviHeader](aviheader)() | Initializes a new instance of the [`AviHeader`](../aviheader) class. |

## Properties

| Name | Description |
| --- | --- |
| [AviHeaderFlags](../../groupdocs.metadata.formats.video/aviheader/aviheaderflags) { get; } | Gets a bitwise combination of zero or more of the AVI flags. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Height](../../groupdocs.metadata.formats.video/aviheader/height) { get; } | Gets the height of the AVI file in pixels. |
| [InitialFrames](../../groupdocs.metadata.formats.video/aviheader/initialframes) { get; } | Gets the initial frame for interleaved files.  Noninterleaved files should specify zero. If you are creating interleaved files, specify the number of frames in the file prior to the initial frame of the AVI sequence in this member. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MaxBytesPerSec](../../groupdocs.metadata.formats.video/aviheader/maxbytespersec) { get; } | Gets the approximate maximum data rate of the file.  This value indicates the number of bytes per second the system must handle to present an AVI sequence as specified by the other parameters contained in the main header and stream header chunks. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [MicroSecPerFrame](../../groupdocs.metadata.formats.video/aviheader/microsecperframe) { get; } | Gets the the number of microseconds between frames. This value indicates the overall timing for the file. |
| [PaddingGranularity](../../groupdocs.metadata.formats.video/aviheader/paddinggranularity) { get; } | Gets the alignment for data, in bytes. Pad the data to multiples of this value. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Streams](../../groupdocs.metadata.formats.video/aviheader/streams) { get; } | Gets the number of streams in the file. For example, a file with audio and video has two streams. |
| [SuggestedBufferSize](../../groupdocs.metadata.formats.video/aviheader/suggestedbuffersize) { get; } | Gets the suggested buffer size for reading the file.  Generally, this size should be large enough to contain the largest chunk in the file. If set to zero, or if it is too small, the playback software will have to reallocate memory during playback, which will reduce performance. For an interleaved file, the buffer size should be large enough to read an entire record, and not just a chunk. |
| [TotalFrames](../../groupdocs.metadata.formats.video/aviheader/totalframes) { get; } | Gets the the total number of frames of data in the file. |
| [Width](../../groupdocs.metadata.formats.video/aviheader/width) { get; } | Gets the width of the AVI file in pixels. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Working with metadata in AVI files](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+AVI+files)

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
