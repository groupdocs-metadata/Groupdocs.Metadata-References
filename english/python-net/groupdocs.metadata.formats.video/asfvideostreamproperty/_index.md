---
title: AsfVideoStreamProperty class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents video stream property metadata in the ASF media container."
type: docs
url: /python-net/groupdocs.metadata.formats.video/asfvideostreamproperty/
is_root: false
weight: 150
---


## AsfVideoStreamProperty class

Represents video stream property metadata in the ASF media container.

Learn more

- https://docs.groupdocs.com/display/metadatanet/Working+with+Metadata+in+ASF+Files

The AsfVideoStreamProperty type exposes the following members:

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
| [bits_per_pixels](/metadata/python-net/groupdocs.metadata.formats.video/asfvideostreamproperty/bits_per_pixels/) | The bits per pixels. |
| [compression](/metadata/python-net/groupdocs.metadata.formats.video/asfvideostreamproperty/compression/) | The video compression Id. |
| [image_height](/metadata/python-net/groupdocs.metadata.formats.video/asfvideostreamproperty/image_height/) | The height of the encoded image in pixels. |
| [image_width](/metadata/python-net/groupdocs.metadata.formats.video/asfvideostreamproperty/image_width/) | The width of the encoded image in pixels. |
| [alternate_bitrate](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/alternate_bitrate/) | The leak rate RAlt, in bits per second, of a leaky bucket that contains the data portion of the stream without overflowing, excluding all ASF Data Packet overhead. (inherited from [`AsfBaseStreamProperty`](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/)) |
| [average_bitrate](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/average_bitrate/) | The average bitrate. (inherited from [`AsfBaseStreamProperty`](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/)) |
| [average_time_per_frame](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/average_time_per_frame/) | The average time duration, measured in 100-nanosecond units, of each frame. (inherited from [`AsfBaseStreamProperty`](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/)) |
| [bitrate](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/bitrate/) | The leak rate R, in bits per second, of a leaky bucket that contains the data portion of the stream without overflowing, excluding all ASF Data Packet overhead. (inherited from [`AsfBaseStreamProperty`](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/)) |
| [count](/metadata/python-net/groupdocs.metadata.common/metadatapackage/count/) | The number of metadata properties. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [end_time](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/end_time/) | The presentation time of the last object plus the duration of play, indicating where this digital media stream ends within the context of the timeline of the ASF file as a whole. (inherited from [`AsfBaseStreamProperty`](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/)) |
| [flags](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/flags/) | The flags. (inherited from [`AsfBaseStreamProperty`](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/)) |
| [keys](/metadata/python-net/groupdocs.metadata.common/metadatapackage/keys/) | The collection of metadata property names. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [know_property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/know_property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [language](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/language/) | The stream language. (inherited from [`AsfBaseStreamProperty`](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/)) |
| [metadata_type](/metadata/python-net/groupdocs.metadata.common/metadatapackage/metadata_type/) | The metadata type of the package. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [start_time](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/start_time/) | The presentation time of the first object, indicating where this digital media stream starts within the context of the timeline of the ASF file as a whole. (inherited from [`AsfBaseStreamProperty`](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/)) |
| [stream_number](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/stream_number/) | The number of this stream. (inherited from [`AsfBaseStreamProperty`](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/)) |
| [stream_type](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/stream_type/) | The type of this stream. (inherited from [`AsfBaseStreamProperty`](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty/)) |

### See Also
* module [`groupdocs.metadata.formats.video`](/metadata/python-net/groupdocs.metadata.formats.video/)
