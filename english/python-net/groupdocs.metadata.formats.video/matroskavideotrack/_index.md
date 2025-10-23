---
title: MatroskaVideoTrack class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.video/matroskavideotrack/
is_root: false
weight: 260
---

## MatroskaVideoTrack class

Represents video metadata in a Matroska video.



**Inheritance:** [`MatroskaVideoTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack) → 
[`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack) → 
[`MatroskaBasePackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskabasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The MatroskaVideoTrack type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/count) | Gets the number of metadata properties. |
| [track_number](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/track_number) | Gets the track number as used in the Block Header.<br/>Using more than 127 tracks is not encouraged, though the design allows an unlimited number. |
| [track_uid](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/track_uid) | Gets the unique ID to identify the Track.<br/>This SHOULD be kept the same when making a direct stream copy of the Track to another file. |
| [track_type](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/track_type) | Gets the type of the track. |
| [flag_enabled](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/flag_enabled) | Gets the enabled flag, true if the track is usable. |
| [default_duration](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/default_duration) | Gets the number of nanoseconds (not scaled via [`MatroskaSegment.timecode_scale`](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment#timecode_scale)) per frame. |
| [name](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/name) | Gets the human-readable track name. |
| [language](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/language) | Gets the language of the track in the Matroska languages form.<br/>This Element MUST be ignored if the [`MatroskaTrack.language_ietf`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack#language_ietf) Element is used in the same TrackEntry. |
| [language_ietf](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/language_ietf) | Gets the language of the track according to BCP 47 and using the IANA Language Subtag Registry. <br/>If this Element is used, then any [`MatroskaTrack.language`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack#language) Elements used in the same TrackEntry MUST be ignored. |
| [codec_id](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/codec_id) | Gets an ID corresponding to the codec. |
| [codec_name](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/codec_name) | Gets a human-readable string specifying the codec. |
| [flag_interlaced](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/flag_interlaced) | Gets a flag to declare if the video is known to be progressive or interlaced and if applicable to declare details about the interlacement. |
| [field_order](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/field_order) | Gets declare the field ordering of the video. <br/>If FlagInterlaced is not set to 1, this Element MUST be ignored. |
| [stereo_mode](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/stereo_mode) | Gets the stereo-3D video mode. |
| [alpha_mode](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/alpha_mode) | Gets the alpha Video Mode. <br/>Presence of this Element indicates that the BlockAdditional Element could contain Alpha data. |
| [pixel_width](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/pixel_width) | Gets the width of the encoded video frames in pixels. |
| [pixel_height](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/pixel_height) | Gets the height of the encoded video frames in pixels. |
| [pixel_crop_bottom](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/pixel_crop_bottom) | Gets the number of video pixels to remove at the bottom of the image. |
| [pixel_crop_top](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/pixel_crop_top) | Gets the number of video pixels to remove at the top of the image. |
| [pixel_crop_left](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/pixel_crop_left) | Gets the number of video pixels to remove on the left of the image. |
| [pixel_crop_right](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/pixel_crop_right) | Gets the number of video pixels to remove on the right of the image. |
| [display_width](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/display_width) | Gets the width of the video frames to display. <br/>Applies to the video frame after cropping (PixelCrop* Elements). |
| [display_height](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/display_height) | Gets the height of the video frames to display. <br/>Applies to the video frame after cropping (PixelCrop* Elements). |
| [display_unit](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/display_unit) | Gets the how [`MatroskaVideoTrack.display_width`](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack#display_width)and [`MatroskaVideoTrack.display_height`](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack#display_height) are interpreted. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.video`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MatroskaBasePackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskabasepackage)
* class [`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack)
* class [`MatroskaVideoTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
