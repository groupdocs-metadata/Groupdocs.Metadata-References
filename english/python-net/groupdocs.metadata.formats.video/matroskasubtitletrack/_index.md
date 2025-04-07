---
title: MatroskaSubtitleTrack class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/
is_root: false
weight: 230
---

## MatroskaSubtitleTrack class

Represents subtitle metadata in a Matroska video.



**Inheritance:** [`MatroskaSubtitleTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack) → 
[`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack) → 
[`MatroskaBasePackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskabasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The MatroskaSubtitleTrack type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/count) | Gets the number of metadata properties. |
| [track_number](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/track_number) | Gets the track number as used in the Block Header.<br/>Using more than 127 tracks is not encouraged, though the design allows an unlimited number. |
| [track_uid](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/track_uid) | Gets the unique ID to identify the Track.<br/>This SHOULD be kept the same when making a direct stream copy of the Track to another file. |
| [track_type](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/track_type) | Gets the type of the track. |
| [flag_enabled](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/flag_enabled) | Gets the enabled flag, true if the track is usable. |
| [default_duration](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/default_duration) | Gets the number of nanoseconds (not scaled via [`MatroskaSegment.timecode_scale`](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment#timecode_scale)) per frame. |
| [name](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/name) | Gets the human-readable track name. |
| [language](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/language) | Gets the language of the track in the Matroska languages form.<br/>This Element MUST be ignored if the [`MatroskaTrack.language_ietf`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack#language_ietf) Element is used in the same TrackEntry. |
| [language_ietf](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/language_ietf) | Gets the language of the track according to BCP 47 and using the IANA Language Subtag Registry. <br/>If this Element is used, then any [`MatroskaTrack.language`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack#language) Elements used in the same TrackEntry MUST be ignored. |
| [codec_id](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/codec_id) | Gets an ID corresponding to the codec. |
| [codec_name](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/codec_name) | Gets a human-readable string specifying the codec. |
| [subtitles](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/subtitles) | Gets the subtitles. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.video`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MatroskaBasePackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskabasepackage)
* class [`MatroskaSubtitleTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskasubtitletrack)
* class [`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
