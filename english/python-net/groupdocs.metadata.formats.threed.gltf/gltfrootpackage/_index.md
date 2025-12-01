---
title: GltfRootPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 40
url: /python-net/groupdocs.metadata.formats.threed.gltf/gltfrootpackage/
is_root: false
---

## GltfRootPackage class

Represents .glTF file metadata.



**Inheritance:** [`GltfRootPackage`](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfrootpackage) → 
[`RootMetadataPackage`](/metadata/python-net/groupdocs.metadata.common/rootmetadatapackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The GltfRootPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfrootpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfrootpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfrootpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfrootpackage/count) | Gets the number of metadata properties. |
| [file_type](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfrootpackage/file_type) | Gets the file type metadata package. |
| [gltf_package](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfrootpackage/gltf_package) | Gets the Gltf metadata package. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfrootpackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfrootpackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfrootpackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfrootpackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfrootpackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfrootpackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfrootpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### Example 


The following code snippet shows how to get metadata from a 3D file.

### See Also
* module [`groupdocs.metadata.formats.threed.gltf`](..)
* class [`GltfRootPackage`](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfrootpackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RootMetadataPackage`](/metadata/python-net/groupdocs.metadata.common/rootmetadatapackage)
