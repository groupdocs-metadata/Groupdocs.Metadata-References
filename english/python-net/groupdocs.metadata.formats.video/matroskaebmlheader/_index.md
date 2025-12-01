---
title: MatroskaEbmlHeader class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 170
url: /python-net/groupdocs.metadata.formats.video/matroskaebmlheader/
is_root: false
---

## MatroskaEbmlHeader class

Represents EBML header metadata in a Matroska video.



**Inheritance:** [`MatroskaEbmlHeader`](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader) → 
[`MatroskaBasePackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskabasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The MatroskaEbmlHeader type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader/count) | Gets the number of metadata properties. |
| [version](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader/version) | Gets the version of the EBML Writer that has been used to create the file. |
| [read_version](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader/read_version) | Gets the minimum version an EBML parser needs to be compliant with to be able to read the file. |
| [doc_type](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader/doc_type) | Gets the contents of the file. In the case of a MATROSKA file, its value is 'matroska'. |
| [doc_type_version](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader/doc_type_version) | Gets the version of the [`MatroskaEbmlHeader.doc_type`](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader#doc_type) writer used to create the file. |
| [doc_type_read_version](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader/doc_type_read_version) | Gets the minimum version number a [`MatroskaEbmlHeader.doc_type`](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader#doc_type) parser must be compliant with to read the file. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.video`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MatroskaBasePackage`](/metadata/python-net/groupdocs.metadata.formats.video/matroskabasepackage)
* class [`MatroskaEbmlHeader`](/metadata/python-net/groupdocs.metadata.formats.video/matroskaebmlheader)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
