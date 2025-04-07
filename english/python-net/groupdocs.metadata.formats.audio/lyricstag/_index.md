---
title: LyricsTag class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.audio/lyricstag/
is_root: false
weight: 170
---

## LyricsTag class

Represents Lyrics3 v2.00 metadata.
Please find more information at [http://id3.org/Lyrics3v2]().



**Inheritance:** [`LyricsTag`](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The LyricsTag type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/__init__/#) | Initializes a new instance of the [`LyricsTag`](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/count) | Gets the number of metadata properties. |
| [lyrics](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/lyrics) | Gets or sets the lyrics.<br/>This value is represented by the LYR field. |
| [additional_info](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/additional_info) | Gets or sets the additional information.<br/>This value is represented by the INF field. |
| [author](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/author) | Gets or sets the author.<br/>This value is represented by the AUT field. |
| [album](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/album) | Gets or sets the album name.<br/>This value is represented by the EAL field. |
| [artist](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/artist) | Gets or sets the artist name.<br/>This value is represented by the EAR field. |
| [track](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/track) | Gets or sets the track title.<br/>This value is represented by the ETT field. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [set](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/set/#groupdocs.metadata.formats.audio.LyricsField) | Adds or replaces the specified Lyrics3 field. |
| [remove](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/remove/#str) | Removes the field with the specified id. |
| [get](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/get/#str) | Gets the value of the field with the specified id. |
| [to_list](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/to_list/#) | Creates a list from the package. |



### Remarks 


Lyrics3 v2.00 uses fields to represent information.
The data in a field can consist of ASCII characters in the range 01 to 254 according to the standard.
As the ASCII character map is only defined from 00 to 128 ISO-8859-1 might be assumed. Numerical fields are 5 or 6 characters long, depending on location, and are padded with zeroes.

**Learn more** |
|
 |

### Example 


This code sample shows how to read the Lyrics tag from an MP3 file.

### See Also
* module [`groupdocs.metadata.formats.audio`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`LyricsTag`](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
