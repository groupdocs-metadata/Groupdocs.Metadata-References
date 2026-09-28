---
title: MatroskaVideoTrack class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents video metadata in a Matroska video."
type: docs
url: /python-net/groupdocs.metadata.formats.video/matroskavideotrack/
is_root: false
weight: 390
---


## MatroskaVideoTrack class

Represents video metadata in a Matroska video.

Learn more

- Working with metadata in Matroska (MKV) files: https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files

The MatroskaVideoTrack type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [add_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties/) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [add_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains/) | Returns True if the package contains a metadata property with the specified name; otherwise, False. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains_file](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_file/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains_string](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_string/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [find_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties/) | Finds metadata properties that satisfy the specified predicate, searching recursively through all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [find_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_enumerator](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_enumerator/) | Returns an enumerator that iterates through the collection. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_file](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_file/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_string](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_string/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [remove_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/remove_properties/) | Removes metadata properties satisfying the specified predicate. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [remove_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/remove_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [sanitize](/metadata/python-net/groupdocs.metadata.common/metadatapackage/sanitize/) | Removes writable metadata properties from the package, recursively affecting all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [set_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties/) | Sets known metadata properties satisfying the specified predicate. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [set_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [update_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties/) | Updates known metadata properties that satisfy the specified predicate, recursively affecting all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [update_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### Properties
| Property | Description |
| :- | :- |
| [alpha_mode](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/alpha_mode/) | The alpha video mode. |
| [display_height](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/display_height/) | The height of the video frames to display. Applies to the video frame after cropping (PixelCrop* Elements). |
| [display_unit](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/display_unit/) | The way the [`MatroskaVideoTrack.display_width`](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/display_width/) and [`MatroskaVideoTrack.display_height`](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/display_height/) are interpreted. |
| [display_width](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/display_width/) | The width of the video frames to display. |
| [field_order](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/field_order/) | The field ordering of the video. Declares the field ordering of the video. |
| [flag_interlaced](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/flag_interlaced/) | The flag to declare if the video is known to be progressive or interlaced and if applicable to declare details about the interlacement. |
| [pixel_crop_bottom](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/pixel_crop_bottom/) | The number of video pixels to remove at the bottom of the image. |
| [pixel_crop_left](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/pixel_crop_left/) | The number of video pixels to remove on the left of the image. |
| [pixel_crop_right](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/pixel_crop_right/) | The number of video pixels to remove on the right of the image. |
| [pixel_crop_top](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/pixel_crop_top/) | The number of video pixels to remove at the top of the image. |
| [pixel_height](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/pixel_height/) | The height of the encoded video frames in pixels. |
| [pixel_width](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/pixel_width/) | The width of the encoded video frames in pixels. |
| [stereo_mode](/metadata/python-net/groupdocs.metadata.formats.video/matroskavideotrack/stereo_mode/) | The stereo-3D video mode. |
| [codec_id](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/codec_id/) | The ID corresponding to the codec. (inherited from [`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/)) |
| [codec_name](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/codec_name/) | The codec name as a human‑readable string specifying the codec. (inherited from [`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/)) |
| [count](/metadata/python-net/groupdocs.metadata.common/metadatapackage/count/) | The number of metadata properties. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [default_duration](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/default_duration/) | The number of nanoseconds (not scaled via [`MatroskaSegment.timecode_scale`](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/timecode_scale/)) per frame. (inherited from [`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/)) |
| [flag_enabled](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/flag_enabled/) | The enabled flag. True if the track is usable. (inherited from [`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/)) |
| [keys](/metadata/python-net/groupdocs.metadata.common/metadatapackage/keys/) | The collection of metadata property names. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [know_property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/know_property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [language](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/language/) | The language of the track in the Matroska languages form, which must be ignored if [`MatroskaTrack.LanguageIetf`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/language_ietf/) is used in the same TrackEntry. (inherited from [`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/)) |
| [language_ietf](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/language_ietf/) | The language of the track according to BCP 47 and using the IANA Language Subtag Registry. (inherited from [`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/)) |
| [metadata_type](/metadata/python-net/groupdocs.metadata.common/metadatapackage/metadata_type/) | The metadata type of the package. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [name](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/name/) | The human-readable track name. (inherited from [`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/)) |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [track_number](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/track_number/) | The track number as used in the Block Header. (inherited from [`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/)) |
| [track_type](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/track_type/) | The type of the track. (inherited from [`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/)) |
| [track_uid](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/track_uid/) | The unique ID to identify the Track. (inherited from [`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/)) |

### See Also
* module [`groupdocs.metadata.formats.video`](/metadata/python-net/groupdocs.metadata.formats.video/)
