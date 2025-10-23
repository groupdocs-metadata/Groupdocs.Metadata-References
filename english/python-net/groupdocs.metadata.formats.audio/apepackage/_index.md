---
title: ApePackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.audio/apepackage/
is_root: false
weight: 10
---

## ApePackage class

Represents an APE v2 metadata package.
Please find more information at [http://wiki.hydrogenaud.io/index.php?title=APE_key](http://wiki.hydrogenaud.io/index.php?title=APE_key).



**Inheritance:** [`ApePackage`](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The ApePackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/count) | Gets the number of metadata properties. |
| [title](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/title) | Gets the title. |
| [subtitle](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/subtitle) | Gets the subtitle. |
| [artist](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/artist) | Gets the artist. |
| [album](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/album) | Gets the album. |
| [debut_album](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/debut_album) | Gets the debut album. |
| [publisher](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/publisher) | Gets the publisher. |
| [conductor](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/conductor) | Gets the conductor. |
| [track](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/track) | Gets the track number. |
| [composer](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/composer) | Gets the composer. |
| [comment](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/comment) | Gets the comment. |
| [copyright](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/copyright) | Gets the copyright. |
| [publication_right](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/publication_right) | Gets the publication right. |
| [file](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/file) | Gets the file. |
| [isbn](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/isbn) | Gets the ISBN number with check digit. See more: https://en.wikipedia.org/wiki/International_Standard_Book_Number. |
| [record_location](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/record_location) | Gets the record location. |
| [genre](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/genre) | Gets the genre. |
| [isrc](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/isrc) | Gets the International Standard Recording Number. |
| [abstract](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/abstract) | Gets the abstract link. |
| [language](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/language) | Gets the language. |
| [bibliography](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/bibliography) | Gets the bibliography. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### Example 


This example demonstrates how to read the APEv2 tag in an MP3 file.

### See Also
* module [`groupdocs.metadata.formats.audio`](..)
* class [`ApePackage`](/metadata/python-net/groupdocs.metadata.formats.audio/apepackage)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
