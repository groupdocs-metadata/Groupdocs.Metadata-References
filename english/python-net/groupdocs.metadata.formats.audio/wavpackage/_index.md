---
title: WavPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 190
url: /python-net/groupdocs.metadata.formats.audio/wavpackage/
is_root: false
---

## WavPackage class

Represents a native metadata package in a WAV audio file.



**Inheritance:** [`WavPackage`](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The WavPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/__init__/#) | Initializes a new instance of the [`WavPackage`](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/count) | Gets the number of metadata properties. |
| [audio_format](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/audio_format) | Gets the audio format.<br/>PCM = 1 (i.e. Linear quantization). Values other than 1 indicate some form of compression. |
| [number_of_channels](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/number_of_channels) | Gets the number of channels. |
| [sample_rate](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/sample_rate) | Gets the sample rate. |
| [byte_rate](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/byte_rate) | Gets the byte rate. |
| [block_align](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/block_align) | Gets the block align. |
| [bits_per_sample](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/bits_per_sample) | Gets the bits per sample value. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### Example 


This code sample shows how to extract technical audio information from a WAV file.

### See Also
* module [`groupdocs.metadata.formats.audio`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`WavPackage`](/metadata/python-net/groupdocs.metadata.formats.audio/wavpackage)
