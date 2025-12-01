---
title: MatroskaTrack class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 250
url: /python-net/groupdocs.metadata.formats.video/matroskatrack/
is_root: false
---

## MatroskaTrack class

Represents track metadata in a Matroska video.



**Inheritance:** [`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack) → 
[`MatroskaBasePackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskabasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The MatroskaTrack type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/count) | Gets the number of metadata properties. |
| [track_number](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/track_number) | Gets the track number as used in the Block Header.<br/>Using more than 127 tracks is not encouraged, though the design allows an unlimited number. |
| [track_uid](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/track_uid) | Gets the unique ID to identify the Track.<br/>This SHOULD be kept the same when making a direct stream copy of the Track to another file. |
| [track_type](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/track_type) | Gets the type of the track. |
| [flag_enabled](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/flag_enabled) | Gets the enabled flag, true if the track is usable. |
| [default_duration](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/default_duration) | Gets the number of nanoseconds (not scaled via [`MatroskaSegment.timecode_scale`](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment#timecode_scale)) per frame. |
| [name](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/name) | Gets the human-readable track name. |
| [language](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/language) | Gets the language of the track in the Matroska languages form.<br/>This Element MUST be ignored if the [`MatroskaTrack.language_ietf`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack#language_ietf) Element is used in the same TrackEntry. |
| [language_ietf](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/language_ietf) | Gets the language of the track according to BCP 47 and using the IANA Language Subtag Registry. <br/>If this Element is used, then any [`MatroskaTrack.language`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack#language) Elements used in the same TrackEntry MUST be ignored. |
| [codec_id](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/codec_id) | Gets an ID corresponding to the codec. |
| [codec_name](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/codec_name) | Gets a human-readable string specifying the codec. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.video`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MatroskaBasePackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskabasepackage)
* class [`MatroskaTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
