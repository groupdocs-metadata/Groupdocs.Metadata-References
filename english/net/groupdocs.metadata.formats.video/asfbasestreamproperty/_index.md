---
title: AsfBaseStreamProperty
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents base stream property metadata in the ASF media container.
type: docs
weight: 3570
url: /net/groupdocs.metadata.formats.video/asfbasestreamproperty/
---
## AsfBaseStreamProperty class

Represents base stream property metadata in the ASF media container.

```csharp
public abstract class AsfBaseStreamProperty : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [AlternateBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/alternatebitrate) { get; } | Gets the leak rate RAlt, in bits per second, of a leaky bucket that contains the data portion of the stream without overflowing, excluding all ASF Data Packet overhead. |
| [AverageBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagebitrate) { get; } | Gets the average bitrate. |
| [AverageTimePerFrame](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagetimeperframe) { get; } | Gets the average time duration, measured in 100-nanosecond units, of each frame. |
| [Bitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/bitrate) { get; } | Gets the leak rate R, in bits per second, of a leaky bucket that contains the data portion of the stream without overflowing, excluding all ASF Data Packet overhead. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [EndTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/endtime) { get; } | Gets the presentation time of the last object plus the duration of play, indicating where this digital media stream ends within the context of the timeline of the ASF file as a whole. |
| [Flags](../../groupdocs.metadata.formats.video/asfbasestreamproperty/flags) { get; } | Gets the flags. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Language](../../groupdocs.metadata.formats.video/asfbasestreamproperty/language) { get; } | Gets the stream language. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [StartTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/starttime) { get; } | Gets the presentation time of the first object, indicating where this digital media stream starts within the context of the timeline of the ASF file as a whole. |
| [StreamNumber](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamnumber) { get; } | Gets the number of this stream. |
| [StreamType](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamtype) { get; } | Gets the type of this stream. |

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

* [Working with Metadata in ASF Files](https://docs.groupdocs.com/display/metadatanet/Working+with+Metadata+in+ASF+Files)

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
