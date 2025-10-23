---
title: MP3RootPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.audio/mp3rootpackage/
is_root: false
weight: 180
---

## MP3RootPackage class

Represents the root package allowing working with metadata in an MP3 audio.



**Inheritance:** [`MP3RootPackage`](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage) → 
[`RootMetadataPackage`](/metadata/python-net/groupdocs.metadata.common/rootmetadatapackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The MP3RootPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/count) | Gets the number of metadata properties. |
| [file_type](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/file_type) | Gets the file type metadata package. |
| [mpeg_audio_package](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/mpeg_audio_package) | Gets the MPEG audio metadata package. |
| [id3v1](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/id3v1) | Gets or sets the ID3v1 metadata tag.<br/>Please find more information at [http://id3.org/ID3v1](http://id3.org/ID3v1). |
| [id3v2](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/id3v2) | Gets or sets the ID3v2 metadata tag. |
| [lyrics_3v2](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/lyrics_3v2) | Gets or sets the Lyrics3v2 metadata tag. |
| [ape_v2](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/ape_v2) | Gets the APE v2 metadata. |
| [xmp_package](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/xmp_package) | Gets or sets the XMP metadata package. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_ape_v2](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/remove_ape_v2/#) | Removes the APEv2 audio tag. |



### Remarks 


**Learn more** |
|
 |
 |

### See Also
* module [`groupdocs.metadata.formats.audio`](..)
* class [`MP3RootPackage`](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RootMetadataPackage`](/metadata/python-net/groupdocs.metadata.common/rootmetadatapackage)
