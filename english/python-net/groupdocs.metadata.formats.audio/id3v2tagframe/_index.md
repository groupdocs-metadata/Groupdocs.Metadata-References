---
title: ID3V2TagFrame class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 100
url: /python-net/groupdocs.metadata.formats.audio/id3v2tagframe/
is_root: false
---

## ID3V2TagFrame class

Represents a generic frame in an [`ID3V2Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag).



**Inheritance:** [`ID3V2TagFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The ID3V2TagFrame type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self, frame_id, data)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/__init__/#system.string-bytes) | Initializes a new instance of the [`ID3V2TagFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/count) | Gets the number of metadata properties. |
| [id](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/id) | Gets the id of the frame (four characters matching the pattern [A-Z0-9]). |
| [flags](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/flags) | Gets the frame flags. |
| [data](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/data) | Gets the frame data. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.audio`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`ID3V2Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag)
* class [`ID3V2TagFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
