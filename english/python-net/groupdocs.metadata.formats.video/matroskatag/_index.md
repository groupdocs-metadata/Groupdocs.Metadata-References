---
title: MatroskaTag class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 240
url: /python-net/groupdocs.metadata.formats.video/matroskatag/
is_root: false
---

## MatroskaTag class

Represents metadata describing Tracks, Editions, Chapters, Attachments, or the Segment as a whole in a Matroska video.



**Inheritance:** [`MatroskaTag`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatag) → 
[`MatroskaBasePackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskabasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The MatroskaTag type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.video/matroskatag/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.video/matroskatag/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.video/matroskatag/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.video/matroskatag/count) | Gets the number of metadata properties. |
| [target_type_value](/metadata/python-net/groupdocs.metadata.formats.video/matroskatag/target_type_value) | Gets the number to indicate the logical level of the target. |
| [target_type](/metadata/python-net/groupdocs.metadata.formats.video/matroskatag/target_type) | Gets an informational string that can be used to display the logical level of the target.<br/>Like "ALBUM", "TRACK", "MOVIE", "CHAPTER", etc. |
| [tag_track_uid](/metadata/python-net/groupdocs.metadata.formats.video/matroskatag/tag_track_uid) | Gets a unique ID to identify the Track(s) the tags belong to. <br/>If the value is 0 at this level, the tags apply to all tracks in the Segment. |
| [simple_tags](/metadata/python-net/groupdocs.metadata.formats.video/matroskatag/simple_tags) | Gets the general information about the target. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatag/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatag/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatag/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatag/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatag/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatag/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatag/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.video`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MatroskaBasePackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskabasepackage)
* class [`MatroskaTag`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatag)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
