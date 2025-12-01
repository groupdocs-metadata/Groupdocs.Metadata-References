---
title: ID3V2TextFrame class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 120
url: /python-net/groupdocs.metadata.formats.audio/id3v2textframe/
is_root: false
---

## ID3V2TextFrame class

Represents a text frame in an [`ID3V2Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag).
Almost all frames starting with the T character fall into this category. There is only one exception, which is the TXXX frame represented by the [`ID3V2UserDefinedFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedframe) class.



**Inheritance:** [`ID3V2TextFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe) → 
[`ID3V2TagFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The ID3V2TextFrame type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self, id, encoding, value)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe/__init__/#system.string-groupdocs.metadata.formats.audio.id3v2encodingtype-system.string) | Initializes a new instance of the [`ID3V2TextFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe/count) | Gets the number of metadata properties. |
| [id](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe/id) | Gets the id of the frame (four characters matching the pattern [A-Z0-9]). |
| [flags](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe/flags) | Gets the frame flags. |
| [data](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe/data) | Gets the frame data. |
| [text_encoding](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe/text_encoding) | Gets the text encoding. |
| [text](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe/text) | Gets the text value. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.audio`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`ID3V2Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag)
* class [`ID3V2TagFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe)
* class [`ID3V2TextFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2textframe)
* class [`ID3V2UserDefinedFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedframe)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
