---
title: FbxPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/
is_root: false
---

## FbxPackage class

Represents .fbx file metadata.



**Inheritance:** [`FbxPackage`](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The FbxPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/count) | Gets the number of metadata properties. |
| [name](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/name) | Gets the node name. |
| [author](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/author) | Gets or sets the author of this asset |
| [comment](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/comment) | Gets or sets the comment of this asset. |
| [application_name](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/application_name) | Gets or sets the application name of this asset |
| [application_vendor](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/application_vendor) | Gets or sets the a application vendor of this asset |
| [application_version](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/application_version) | Gets or sets the application version of this asset |
| [url](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/url) | Gets or sets the url of this asset |
| [nodes](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/nodes) | Gets an array of [`FbxNode`](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxnode) entries inside the Fbx file. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### Example 


The following code snippet shows how to get metadata from a 3D file.

### See Also
* module [`groupdocs.metadata.formats.threed.fbx`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`FbxNode`](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxnode)
* class [`FbxPackage`](/metadata/python-net/groupdocs.metadata.formats.threed.fbx/fbxpackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
