---
title: AviHeader class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.video/aviheader/
is_root: false
weight: 110
---

## AviHeader class

Represents the AVIMAINHEADER structure in an AVI video.



**Inheritance:** [`AviHeader`](/metadata/python-net/groupdocs.metadata.formats.video/aviheader) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The AviHeader type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/__init__/#) | Initializes a new instance of the [`AviHeader`](/metadata/python-net/groupdocs.metadata.formats.video/aviheader) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/count) | Gets the number of metadata properties. |
| [micro_sec_per_frame](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/micro_sec_per_frame) | Gets the the number of microseconds between frames. This value indicates the overall timing for the file. |
| [max_bytes_per_sec](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/max_bytes_per_sec) | Gets the approximate maximum data rate of the file.<br/><br/><br/>This value indicates the number of bytes per second the system must handle to present an AVI sequence as <br/>specified by the other parameters contained in the main header and stream header chunks. |
| [padding_granularity](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/padding_granularity) | Gets the alignment for data, in bytes. Pad the data to multiples of this value. |
| [avi_header_flags](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/avi_header_flags) | Gets a bitwise combination of zero or more of the AVI flags. |
| [total_frames](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/total_frames) | Gets the the total number of frames of data in the file. |
| [initial_frames](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/initial_frames) | Gets the initial frame for interleaved files.<br/><br/><br/>Noninterleaved files should specify zero. If you are creating interleaved files, specify the number of frames <br/>in the file prior to the initial frame of the AVI sequence in this member. |
| [streams](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/streams) | Gets the number of streams in the file. For example, a file with audio and video has two streams. |
| [suggested_buffer_size](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/suggested_buffer_size) | Gets the suggested buffer size for reading the file.<br/><br/><br/>Generally, this size should be large enough to contain the largest chunk in the file. <br/>If set to zero, or if it is too small, the playback software will have to reallocate memory during playback, which will reduce performance. For an interleaved file, <br/>the buffer size should be large enough to read an entire record, and not just a chunk. |
| [width](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/width) | Gets the width of the AVI file in pixels. |
| [height](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/height) | Gets the height of the AVI file in pixels. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.video`](..)
* class [`AviHeader`](/metadata/python-net/groupdocs.metadata.formats.video/aviheader)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
