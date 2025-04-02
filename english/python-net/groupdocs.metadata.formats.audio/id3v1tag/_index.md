---
title: ID3V1Tag class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.audio/id3v1tag/
is_root: false
weight: 30
---

## ID3V1Tag class

Represents an ID3v1 tag.
Please find more information at [https://en.wikipedia.org/wiki/ID3#ID3v1](https://en.wikipedia.org/wiki/ID3#ID3v1).



**Inheritance:** [`ID3V1Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag) → 
[`ID3Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3tag) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The ID3V1Tag type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/__init__/#) | Initializes a new instance of the [`ID3V1Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/count) | Gets the number of metadata properties. |
| [version](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/version) | Gets the ID3 version. It can be ID3 or ID3v1.1 |
| [artist](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/artist) | Gets or sets the artist. Maximum length is 30 characters. |
| [album](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/album) | Gets or sets the album. Maximum length is 30 characters. |
| [genre_value](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/genre_value) | Gets or sets the genre identifier. |
| [comment](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/comment) | Gets or sets the comment. Maximum length is 30 characters. |
| [title](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/title) | Gets or sets the title. |
| [year](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/year) | Gets or sets the year. Maximum length is 4 characters. |
| [track_number](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/track_number) | Gets or sets the track number. Presented in a ID3v1.1 tag only. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


ID3(v1) tag is a small chunk of extra data at the end of MP3.
Please find more information at [http://id3.org/ID3v1](http://id3.org/ID3v1).

**Learn more** |
|
 |

### Example 


This code sample shows how to read the ID3v1 tag in an MP3 file.

### See Also
* module [`groupdocs.metadata.formats.audio`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`ID3Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3tag)
* class [`ID3V1Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
