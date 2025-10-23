---
title: MpegAudioPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/
is_root: false
weight: 10
---

## MpegAudioPackage class

Represents MPEG audio metadata.



**Inheritance:** [`MpegAudioPackage`](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The MpegAudioPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/__init__/#) | Initializes a new instance of the [`MpegAudioPackage`](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/count) | Gets the number of metadata properties. |
| [mpeg_audio_version](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/mpeg_audio_version) | Gets the MPEG audio version. Can be MPEG-1, MPEG-2 etc. |
| [layer](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/layer) | Gets the layer description. For an MP3 audio it is '3'. |
| [is_protected](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/is_protected) | Gets `true` if protected. |
| [header_position](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/header_position) | Gets the header offset. |
| [bitrate](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/bitrate) | Gets the bitrate. |
| [frequency](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/frequency) | Gets the frequency. |
| [padding_bit](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/padding_bit) | Gets the padding bit. |
| [private_bit](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/private_bit) | Gets a value indicating whether [private bit]. |
| [channel_mode](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/channel_mode) | Gets the channel mode. |
| [copyright](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/copyright) | Gets the copyright bit. |
| [is_original](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/is_original) | Gets the original bit. |
| [emphasis](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/emphasis) | Gets the emphasis. |
| [mode_extension_bits](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/mode_extension_bits) | Gets the mode extension bits. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Example 


This example demonstrates how to read MPEG audio metadata from an MP3 file.

### See Also
* module [`groupdocs.metadata.formats.mpeg`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`MpegAudioPackage`](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage)
