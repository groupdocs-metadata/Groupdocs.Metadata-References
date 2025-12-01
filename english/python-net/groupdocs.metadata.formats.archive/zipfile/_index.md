---
title: ZipFile class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 100
url: /python-net/groupdocs.metadata.formats.archive/zipfile/
is_root: false
---

## ZipFile class

Represents metadata associated with an archived file or directory.



**Inheritance:** [`ZipFile`](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The ZipFile type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/count) | Gets the number of metadata properties. |
| [compression_method](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/compression_method) | Gets the compression method. |
| [compressed_size](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/compressed_size) | Gets the compressed size in bytes. |
| [uncompressed_size](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/uncompressed_size) | Gets the uncompressed size in bytes. |
| [flags](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/flags) | Gets the ZIP entry flags. |
| [name](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/name) | Gets the entry name. |
| [raw_name](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/raw_name) | Gets an array of bytes representing the name of the entry. |
| [modification_date_time](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/modification_date_time) | Gets the last modification date and time. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.archive`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`ZipFile`](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile)
