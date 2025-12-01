---
title: MatroskaSegment class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 200
url: /python-net/groupdocs.metadata.formats.video/matroskasegment/
is_root: false
---

## MatroskaSegment class

Represents a SEGMENTINFO element containing general information about the SEGMENT in a Matroska video.



**Inheritance:** [`MatroskaSegment`](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment) → 
[`MatroskaBasePackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskabasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The MatroskaSegment type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/count) | Gets the number of metadata properties. |
| [segment_uid](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/segment_uid) | Gets the unique 128 bit number identifying a SEGMENT.<br/>Obviously, a file can only be referred to by another file if a SEGMENTUID is present, however, playback is possible without that UID. |
| [segment_filename](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/segment_filename) | Gets the filename corresponding to this Segment. |
| [timecode_scale](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/timecode_scale) | Gets the timecode scale value. <br/>Each scaled timecode in a MATROSKA file is multiplied by TIMECODESCALE to obtain the timecode in nanoseconds. Note that not all timecodes are scaled! |
| [duration](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/duration) | Gets the duration of the SEGMENT.<br/>Please see [`MatroskaSegment.timecode_scale`](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment#timecode_scale) for more information. |
| [date_utc](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/date_utc) | Gets the date and time that the Segment was created by the muxing application or library. |
| [title](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/title) | Gets the general name of the Segment. |
| [muxing_app](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/muxing_app) | Gets the full name of the application or library followed by the version number. |
| [writing_app](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/writing_app) | Gets the full name of the application followed by the version number. |
| [scaled_duration](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/scaled_duration) | Gets the scaled duration of the SEGMENT. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.video`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MatroskaBasePackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskabasepackage)
* class [`MatroskaSegment`](/metadata/python-net/groupdocs.metadata.formats.video/matroskasegment)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
