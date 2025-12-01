---
title: FlvHeader class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 130
url: /python-net/groupdocs.metadata.formats.video/flvheader/
is_root: false
---

## FlvHeader class

Represents a FLV video header.



**Inheritance:** [`FlvHeader`](/metadata/python-net/groupdocs.metadata.formats.video/flvheader) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The FlvHeader type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.video/flvheader/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.video/flvheader/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.video/flvheader/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.video/flvheader/count) | Gets the number of metadata properties. |
| [version](/metadata/python-net/groupdocs.metadata.formats.video/flvheader/version) | Gets the file version. |
| [type_flags](/metadata/python-net/groupdocs.metadata.formats.video/flvheader/type_flags) | Gets the FLV type flags. |
| [has_audio_tags](/metadata/python-net/groupdocs.metadata.formats.video/flvheader/has_audio_tags) | Gets a value indicating whether audio tags are present in the file. |
| [has_video_tags](/metadata/python-net/groupdocs.metadata.formats.video/flvheader/has_video_tags) | Gets a value indicating whether video tags are present in the file. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.video/flvheader/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.video/flvheader/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/flvheader/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.video/flvheader/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/flvheader/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/flvheader/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.video/flvheader/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.video`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`FlvHeader`](/metadata/python-net/groupdocs.metadata.formats.video/flvheader)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
