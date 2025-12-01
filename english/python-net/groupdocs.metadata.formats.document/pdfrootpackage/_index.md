---
title: PdfRootPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 150
url: /python-net/groupdocs.metadata.formats.document/pdfrootpackage/
is_root: false
---

## PdfRootPackage class

Represents the root package allowing working with metadata in a PDF document.



**Inheritance:** [`PdfRootPackage`](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage) → 
[`RootMetadataPackage`](/metadata/python-net/groupdocs.metadata.common/rootmetadatapackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The PdfRootPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage/count) | Gets the number of metadata properties. |
| [file_type](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage/file_type) | Gets the file type metadata package. |
| [inspection_package](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage/inspection_package) | Gets a metadata package containing inspection results for the document.<br/>The package contains information about document parts that can be considered as metadata in some cases. |
| [document_statistics](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage/document_statistics) | Gets the document statistics package. |
| [xmp_package](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage/xmp_package) | Gets or sets the XMP metadata package. |
| [document_properties](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage/document_properties) |  |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |
 |

### Example 


This code sample shows how to extract built-in metadata properties from a PDF document.

### See Also
* module [`groupdocs.metadata.formats.document`](..)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`PdfRootPackage`](/metadata/python-net/groupdocs.metadata.formats.document/pdfrootpackage)
* class [`RootMetadataPackage`](/metadata/python-net/groupdocs.metadata.common/rootmetadatapackage)
