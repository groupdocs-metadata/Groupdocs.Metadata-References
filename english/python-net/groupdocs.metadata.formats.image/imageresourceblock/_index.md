---
title: ImageResourceBlock class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 100
url: /python-net/groupdocs.metadata.formats.image/imageresourceblock/
is_root: false
---

## ImageResourceBlock class

Represents a Photoshop Image Resource block.


Image resource blocks are the basic building unit of several file formats, including Photoshop's native file format, JPEG, and TIFF. 
Image resources are used to store non-pixel data associated with images, such as pen tool paths.



**Inheritance:** [`ImageResourceBlock`](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceblock) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The ImageResourceBlock type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceblock/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceblock/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceblock/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceblock/count) | Gets the number of metadata properties. |
| [signature](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceblock/signature) | Gets the image resource block signature. |
| [id](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceblock/id) | Gets the unique identifier for the resource. |
| [name](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceblock/name) | Gets the image resource block name. |
| [data](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceblock/data) | Gets the resource data. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceblock/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceblock/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceblock/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceblock/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceblock/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceblock/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceblock/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.image`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`ImageResourceBlock`](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceblock)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
