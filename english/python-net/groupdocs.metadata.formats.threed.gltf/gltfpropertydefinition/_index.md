---
title: GltfPropertyDefinition class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.threed.gltf/gltfpropertydefinition/
is_root: false
weight: 20
---

## GltfPropertyDefinition class

Represents metadata associated with an .glTF file.



**Inheritance:** [`GltfPropertyDefinition`](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfpropertydefinition) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The GltfPropertyDefinition type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfpropertydefinition/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfpropertydefinition/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfpropertydefinition/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfpropertydefinition/count) | Gets the number of metadata properties. |
| [property_name](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfpropertydefinition/property_name) | Gets the property name. |
| [property_type](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfpropertydefinition/property_type) | Gets the property type. |
| [property_value](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfpropertydefinition/property_value) | Gets the property value. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfpropertydefinition/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfpropertydefinition/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfpropertydefinition/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfpropertydefinition/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfpropertydefinition/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfpropertydefinition/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfpropertydefinition/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.threed.gltf`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`GltfPropertyDefinition`](/metadata/python-net/groupdocs.metadata.formats.threed.gltf/gltfpropertydefinition)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
