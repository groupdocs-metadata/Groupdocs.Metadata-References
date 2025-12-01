---
title: OpenTypeBaseNameRecord class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 10
url: /python-net/groupdocs.metadata.formats.font/opentypebasenamerecord/
is_root: false
---

## OpenTypeBaseNameRecord class

Represents the base OpenType Name table record class.



**Inheritance:** [`OpenTypeBaseNameRecord`](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The OpenTypeBaseNameRecord type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord/count) | Gets the number of metadata properties. |
| [name_id](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord/name_id) | Gets the name identifier. |
| [platform](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord/platform) | Gets the platform identifier. |
| [value](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord/value) | Gets the string value of record. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.font`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`OpenTypeBaseNameRecord`](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord)
