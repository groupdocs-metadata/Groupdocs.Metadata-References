---
title: ID3V2AttachedPictureFrame class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 40
url: /python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/
is_root: false
---

## ID3V2AttachedPictureFrame class

Represents an APIC frame in an [`ID3V2Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag).



**Inheritance:** [`ID3V2AttachedPictureFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe) → 
[`ID3V2TagFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The ID3V2AttachedPictureFrame type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self, encoding, mime_type, picture_type, description, picture_data)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/__init__/#groupdocs.metadata.formats.audio.id3v2encodingtype-system.string-groupdocs.metadata.formats.audio.id3v2attachedpicturetype-system.string-bytes) | Initializes a new instance of the [`ID3V2AttachedPictureFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe) class. |
| [`__init__(self, picture_type, description, picture_data)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/__init__/#groupdocs.metadata.formats.audio.id3v2attachedpicturetype-system.string-bytes) | Initializes a new instance of the [`ID3V2AttachedPictureFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe) class. |
| [`__init__(self, picture_data)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/__init__/#bytes) | Initializes a new instance of the [`ID3V2AttachedPictureFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/count) | Gets the number of metadata properties. |
| [id](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/id) | Gets the id of the frame (four characters matching the pattern [A-Z0-9]). |
| [flags](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/flags) | Gets the frame flags. |
| [data](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/data) | Gets the frame data. |
| [description_encoding](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/description_encoding) | Gets the encoding used to encode the picture description. |
| [mime_type](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/mime_type) | Gets the MIME type of the picture. |
| [attached_picture_type](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/attached_picture_type) | Gets the type of the picture. |
| [description](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/description) | Gets the picture description.<br/>The description has a maximum length of 64 characters, but may be empty. |
| [picture_data](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/picture_data) | Gets the picture data. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.audio`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`ID3V2AttachedPictureFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe)
* class [`ID3V2Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag)
* class [`ID3V2TagFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
