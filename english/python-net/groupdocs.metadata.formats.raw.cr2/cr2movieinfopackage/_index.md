---
title: Cr2MovieInfoPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 170
url: /python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/
is_root: false
---

## Cr2MovieInfoPackage class

Represents Canon MakerNotes tags.



**Inheritance:** [`Cr2MovieInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage) → 
[`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Cr2MovieInfoPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/__init__/#) | Initializes a new instance of the [`Cr2MovieInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/count) | Gets the number of metadata properties. |
| [frame_rate](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/frame_rate) | Gets the FrameRate. |
| [frame_count](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/frame_count) | Gets the FrameCount. |
| [frame_count2](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/frame_count2) | Gets the FrameCount2. |
| [frame_rate2](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/frame_rate2) | Gets the FrameRate2. |
| [duration](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/duration) | Gets the Duration. |
| [audio_bitrate](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/audio_bitrate) | Gets the AudioBitrate. |
| [audio_sample_rate](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/audio_sample_rate) | Gets the AudioSampleRate. |
| [audio_channels](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/audio_channels) | Gets the AudioChannels. |
| [video_codec](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/video_codec) | Gets the VideoCodec. |


### Indexer
| Name | Description |
| :- | :- |
| [index] |  |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`to_list(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/to_list/#) | Creates a list from the package. |
| [`remove(self, tag_id)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/remove/#int) | Removes the property with the specified id. |
| [`set(self, tag)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/set/#groupdocs.metadata.formats.raw.tag.rawtag) | Adds or replaces the specified tag. |
| [`clear(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage/clear/#) | Removes all Raw tags stored in the package. |



### See Also
* module [`groupdocs.metadata.formats.raw.cr2`](..)
* class [`Cr2MovieInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2movieinfopackage)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage)
