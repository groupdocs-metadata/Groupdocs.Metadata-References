---
title: MatroskaAudioTrack class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/
is_root: false
weight: 150
---

## MatroskaAudioTrack class

Represents audio metadata in a Matroska video.



**Inheritance:** [`MatroskaAudioTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack) → 
[`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack) → 
[`MatroskaBasePackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskabasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The MatroskaAudioTrack type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/count) | Gets the number of metadata properties. |
| [track_number](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/track_number) | Gets the track number as used in the Block Header.<br/>Using more than 127 tracks is not encouraged, though the design allows an unlimited number. |
| [track_uid](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/track_uid) | Gets the unique ID to identify the Track.<br/>This SHOULD be kept the same when making a direct stream copy of the Track to another file. |
| [track_type](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/track_type) | Gets the type of the track. |
| [flag_enabled](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/flag_enabled) | Gets the enabled flag, true if the track is usable. |
| [default_duration](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/default_duration) | Gets the number of nanoseconds (not scaled via [`MatroskaSegment.timecode_scale`](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment#timecode_scale)) per frame. |
| [name](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/name) | Gets the human-readable track name. |
| [language](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/language) | Gets the language of the track in the Matroska languages form.<br/>This Element MUST be ignored if the [`MatroskaTrack.language_ietf`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack#language_ietf) Element is used in the same TrackEntry. |
| [language_ietf](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/language_ietf) | Gets the language of the track according to BCP 47 and using the IANA Language Subtag Registry. <br/>If this Element is used, then any [`MatroskaTrack.language`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack#language) Elements used in the same TrackEntry MUST be ignored. |
| [codec_id](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/codec_id) | Gets an ID corresponding to the codec. |
| [codec_name](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/codec_name) | Gets a human-readable string specifying the codec. |
| [sampling_frequency](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/sampling_frequency) | Gets the sampling frequency in Hz. |
| [output_sampling_frequency](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/output_sampling_frequency) | Gets the real output sampling frequency in Hz (used for SBR techniques). |
| [channels](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/channels) | Gets the numbers of channels in the track. |
| [bit_depth](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/bit_depth) | Gets the bits per sample, mostly used for PCM. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.video`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MatroskaAudioTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack)
* class [`MatroskaBasePackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskabasepackage)
* class [`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
