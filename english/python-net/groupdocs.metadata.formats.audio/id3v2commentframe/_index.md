---
title: ID3V2CommentFrame class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.audio/id3v2commentframe/
is_root: false
weight: 50
---

## ID3V2CommentFrame class

Represents a COMM frame in an [`ID3V2Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag).



**Inheritance:** [`ID3V2CommentFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe) → 
[`ID3V2TagFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The ID3V2CommentFrame type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/__init__/#groupdocs.metadata.formats.audio.ID3V2EncodingType-str-str-str) | Initializes a new instance of the [`ID3V2CommentFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/count) | Gets the number of metadata properties. |
| [id](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/id) | Gets the id of the frame (four characters matching the pattern [A-Z0-9]). |
| [flags](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/flags) | Gets the frame flags. |
| [data](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/data) | Gets the frame data. |
| [comment_encoding](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/comment_encoding) | Gets the encoding of the comment. |
| [language](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/language) | Gets the language of the comment (3 characters). |
| [short_content_description](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/short_content_description) | Gets the short content description. |
| [text](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/text) | Gets the text of the comment. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


This frame is intended for any kind of full text information that does not fit in any other frame.

**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.audio`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`ID3V2CommentFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2commentframe)
* class [`ID3V2Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag)
* class [`ID3V2TagFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
