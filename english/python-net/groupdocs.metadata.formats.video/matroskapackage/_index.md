---
title: MatroskaPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 180
url: /python-net/groupdocs.metadata.formats.video/matroskapackage/
is_root: false
---

## MatroskaPackage class

Represents a metadata container in a Matroska video.



**Inheritance:** [`MatroskaPackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage) → 
[`MatroskaBasePackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskabasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The MatroskaPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage/count) | Gets the number of metadata properties. |
| [ebml_header](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage/ebml_header) | Gets the EBML header metadata. |
| [segments](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage/segments) | Gets the segment information metadata. |
| [tracks](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage/tracks) | Gets the track metadata entries. |
| [tags](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage/tags) | Gets the tagging metadata. |
| [content_type](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage/content_type) | Gets the Matroska content type. |
| [subtitle_tracks](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage/subtitle_tracks) | Gets the subtitle metadata entries. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.video`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MatroskaBasePackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskabasepackage)
* class [`MatroskaPackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskapackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
