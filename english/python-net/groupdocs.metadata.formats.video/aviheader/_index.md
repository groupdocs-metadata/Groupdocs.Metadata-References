---
title: AviHeader class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents the AVIMAINHEADER structure in an AVI video."
type: docs
url: /python-net/groupdocs.metadata.formats.video/aviheader/
is_root: false
weight: 160
---


## AviHeader class

Represents the AVIMAINHEADER structure in an AVI video.

Learn more

- Working with metadata in AVI files: https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+AVI+files

The AviHeader type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/__init__/) | Initializes a new instance of the [`AviHeader`](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/) class. |

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
| [avi_header_flags](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/avi_header_flags/) | The AVI flags as a bitwise combination of zero or more of the AVI flags. |
| [height](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/height/) | The height of the AVI file in pixels. |
| [initial_frames](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/initial_frames/) | The initial frames for interleaved files. |
| [max_bytes_per_sec](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/max_bytes_per_sec/) | The approximate maximum data rate of the file. |
| [micro_sec_per_frame](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/micro_sec_per_frame/) | The number of microseconds between frames. |
| [padding_granularity](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/padding_granularity/) | The alignment for data, in bytes. |
| [streams](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/streams/) | The number of streams in the file. |
| [suggested_buffer_size](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/suggested_buffer_size/) | The suggested buffer size for reading the file. |
| [total_frames](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/total_frames/) | The total number of frames of data in the file. |
| [width](/metadata/python-net/groupdocs.metadata.formats.video/aviheader/width/) | The width of the AVI file in pixels. |
| [count](/metadata/python-net/groupdocs.metadata.common/metadatapackage/count/) | The number of metadata properties. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [keys](/metadata/python-net/groupdocs.metadata.common/metadatapackage/keys/) | The collection of metadata property names. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [know_property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/know_property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [metadata_type](/metadata/python-net/groupdocs.metadata.common/metadatapackage/metadata_type/) | The metadata type of the package. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### See Also
* module [`groupdocs.metadata.formats.video`](/metadata/python-net/groupdocs.metadata.formats.video/)
