---
title: MatroskaVideoTrack
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents video metadata in a Matroska video.
type: docs
weight: 4100
url: /net/groupdocs.metadata.formats.video/matroskavideotrack/
---
## MatroskaVideoTrack class

Represents video metadata in a Matroska video.

```csharp
public class MatroskaVideoTrack : MatroskaTrack
```

## Properties

| Name | Description |
| --- | --- |
| [AlphaMode](../../groupdocs.metadata.formats.video/matroskavideotrack/alphamode) { get; } | Gets the alpha Video Mode. Presence of this Element indicates that the BlockAdditional Element could contain Alpha data. |
| [CodecID](../../groupdocs.metadata.formats.video/matroskatrack/codecid) { get; } | Gets an ID corresponding to the codec. |
| [CodecName](../../groupdocs.metadata.formats.video/matroskatrack/codecname) { get; } | Gets a human-readable string specifying the codec. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [DefaultDuration](../../groupdocs.metadata.formats.video/matroskatrack/defaultduration) { get; } | Gets the number of nanoseconds (not scaled via [`TimecodeScale`](../matroskasegment/timecodescale)) per frame. |
| [DisplayHeight](../../groupdocs.metadata.formats.video/matroskavideotrack/displayheight) { get; } | Gets the height of the video frames to display. Applies to the video frame after cropping (PixelCrop* Elements). |
| [DisplayUnit](../../groupdocs.metadata.formats.video/matroskavideotrack/displayunit) { get; } | Gets the how [`DisplayWidth`](./displaywidth)and [`DisplayHeight`](./displayheight) are interpreted. |
| [DisplayWidth](../../groupdocs.metadata.formats.video/matroskavideotrack/displaywidth) { get; } | Gets the width of the video frames to display. Applies to the video frame after cropping (PixelCrop* Elements). |
| [FieldOrder](../../groupdocs.metadata.formats.video/matroskavideotrack/fieldorder) { get; } | Gets declare the field ordering of the video. If FlagInterlaced is not set to 1, this Element MUST be ignored. |
| [FlagEnabled](../../groupdocs.metadata.formats.video/matroskatrack/flagenabled) { get; } | Gets the enabled flag, true if the track is usable. |
| [FlagInterlaced](../../groupdocs.metadata.formats.video/matroskavideotrack/flaginterlaced) { get; } | Gets a flag to declare if the video is known to be progressive or interlaced and if applicable to declare details about the interlacement. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Language](../../groupdocs.metadata.formats.video/matroskatrack/language) { get; } | Gets the language of the track in the Matroska languages form. This Element MUST be ignored if the [`LanguageIetf`](../matroskatrack/languageietf) Element is used in the same TrackEntry. |
| [LanguageIetf](../../groupdocs.metadata.formats.video/matroskatrack/languageietf) { get; } | Gets the language of the track according to BCP 47 and using the IANA Language Subtag Registry. If this Element is used, then any [`Language`](../matroskatrack/language) Elements used in the same TrackEntry MUST be ignored. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [Name](../../groupdocs.metadata.formats.video/matroskatrack/name) { get; } | Gets the human-readable track name. |
| [PixelCropBottom](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropbottom) { get; } | Gets the number of video pixels to remove at the bottom of the image. |
| [PixelCropLeft](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropleft) { get; } | Gets the number of video pixels to remove on the left of the image. |
| [PixelCropRight](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropright) { get; } | Gets the number of video pixels to remove on the right of the image. |
| [PixelCropTop](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcroptop) { get; } | Gets the number of video pixels to remove at the top of the image. |
| [PixelHeight](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelheight) { get; } | Gets the height of the encoded video frames in pixels. |
| [PixelWidth](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelwidth) { get; } | Gets the width of the encoded video frames in pixels. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [StereoMode](../../groupdocs.metadata.formats.video/matroskavideotrack/stereomode) { get; } | Gets the stereo-3D video mode. |
| [TrackNumber](../../groupdocs.metadata.formats.video/matroskatrack/tracknumber) { get; } | Gets the track number as used in the Block Header. Using more than 127 tracks is not encouraged, though the design allows an unlimited number. |
| [TrackType](../../groupdocs.metadata.formats.video/matroskatrack/tracktype) { get; } | Gets the type of the track. |
| [TrackUid](../../groupdocs.metadata.formats.video/matroskatrack/trackuid) { get; } | Gets the unique ID to identify the Track. This SHOULD be kept the same when making a direct stream copy of the Track to another file. |

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

* [Working with metadata in Matroska (MKV) files](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### See Also

* class [MatroskaTrack](../matroskatrack)
* namespace [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
