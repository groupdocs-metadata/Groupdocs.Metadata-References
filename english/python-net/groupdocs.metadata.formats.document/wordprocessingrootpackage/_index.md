---
title: WordProcessingRootPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/
is_root: false
weight: 380
---

## WordProcessingRootPackage class

Represents the root package allowing working with metadata in a word processing document.



**Inheritance:** [`WordProcessingRootPackage`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage) → 
[`RootMetadataPackage`](/metadata/python-net/groupdocs.metadata.common/rootmetadatapackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The WordProcessingRootPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/count) | Gets the number of metadata properties. |
| [file_type](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/file_type) | Gets the file type metadata package. |
| [dublin_core_package](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/dublin_core_package) | Gets the Dublin Core metadata package extracted from the document. |
| [inspection_package](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/inspection_package) | Gets a metadata package containing inspection results for the document.<br/>The package contains information about document parts that can be considered as metadata in some cases. |
| [document_statistics](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/document_statistics) | Gets the document statistics package. |
| [document_properties](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/document_properties) |  |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [update_document_statistics](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/update_document_statistics/#) | Recalculates count of pages, paragraphs, words, lines, characters in the document and updates appropriate metadata packages. |



### Remarks 


**Learn more** |
|
 |

### Example 


This code sample demonstrates how to read built-in metadata properties of a WordProcessing document.

### See Also
* module [`groupdocs.metadata.formats.document`](..)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RootMetadataPackage`](/metadata/python-net/groupdocs.metadata.common/rootmetadatapackage)
* class [`WordProcessingRootPackage`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage)
