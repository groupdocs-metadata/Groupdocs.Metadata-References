---
title: GisPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 30
url: /python-net/groupdocs.metadata.formats.gis/gispackage/
is_root: false
---

## GisPackage class

Represents gis metadata.



**Inheritance:** [`GisPackage`](/metadata/python-net/groupdocs.metadata.formats.gis/gispackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The GisPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.gis/gispackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.gis/gispackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.gis/gispackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.gis/gispackage/count) | Gets the number of metadata properties. |
| [features](/metadata/python-net/groupdocs.metadata.formats.gis/gispackage/features) | Gets an array of [`GisFeature`](/metadata/python-net/groupdocs.metadata.formats.gis/gisfeature). |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.gis/gispackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.gis/gispackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.gis/gispackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.gis/gispackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.gis/gispackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.gis/gispackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.gis/gispackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Example 


The following code snippet shows how to get metadata from a gis file.

### See Also
* module [`groupdocs.metadata.formats.gis`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`GisFeature`](/metadata/python-net/groupdocs.metadata.formats.gis/gisfeature)
* class [`GisPackage`](/metadata/python-net/groupdocs.metadata.formats.gis/gispackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
