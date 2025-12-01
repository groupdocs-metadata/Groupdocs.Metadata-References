---
title: SevenZipPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 50
url: /python-net/groupdocs.metadata.formats.archive/sevenzippackage/
is_root: false
---

## SevenZipPackage class

Represents ZIP archive metadata.



**Inheritance:** [`SevenZipPackage`](/metadata/python-net/groupdocs.metadata.formats.archive/sevenzippackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The SevenZipPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.archive/sevenzippackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.archive/sevenzippackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.archive/sevenzippackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.archive/sevenzippackage/count) | Gets the number of metadata properties. |
| [files](/metadata/python-net/groupdocs.metadata.formats.archive/sevenzippackage/files) | Gets an array of [`ZipFile`](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile) entries inside the ZIP archive. |
| [total_entries](/metadata/python-net/groupdocs.metadata.formats.archive/sevenzippackage/total_entries) | Gets the total number of entries inside the ZIP archive. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.archive/sevenzippackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.archive/sevenzippackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.archive/sevenzippackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.archive/sevenzippackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.archive/sevenzippackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.archive/sevenzippackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.archive/sevenzippackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### Example 


The following code snippet shows how to get metadata from a ZIP archive.

### See Also
* module [`groupdocs.metadata.formats.archive`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`SevenZipPackage`](/metadata/python-net/groupdocs.metadata.formats.archive/sevenzippackage)
* class [`ZipFile`](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile)
