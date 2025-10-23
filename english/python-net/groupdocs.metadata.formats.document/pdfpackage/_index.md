---
title: PdfPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.document/pdfpackage/
is_root: false
weight: 140
---

## PdfPackage class

Represents native metadata in a PDF document.



**Inheritance:** [`PdfPackage`](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage) → 
[`DocumentPackage`](/metadata/python-net/groupdocs.metadata.formats.document/documentpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The PdfPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/count) | Gets the number of metadata properties. |
| [author](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/author) | Gets or sets the document author. |
| [created_date](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/created_date) | Gets or sets the date of document creation. |
| [creator](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/creator) | Gets the creator of the document. |
| [keywords](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/keywords) | Gets or sets the keywords. |
| [modified_date](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/modified_date) | Gets or sets the date of the last modification. |
| [producer](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/producer) | Gets the document producer. |
| [subject](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/subject) | Gets or sets the subject of the document. |
| [title](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/title) | Gets or sets the title of the document. |
| [trapped_flag](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/trapped_flag) | Gets or sets the trapped flag. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/remove/#System.String) | Removes a writable metadata property by the specified name. |
| [clear](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/clear/#) | Removes all writable metadata properties from the package. |
| [clear_built_in_properties](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/clear_built_in_properties/#) | Removes all built-in metadata properties. |
| [clear_custom_properties](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/clear_custom_properties/#) | Removes all custom metadata properties. |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage/set/#System.String-System.String) | Adds or replaces the metadata property with the specified name. |



### Remarks 


**Learn more** |
|
 |

### Example 


This code snippet demonstrates how to update built-in metadata properties in a PDF document.

### See Also
* module [`groupdocs.metadata.formats.document`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`DocumentPackage`](/metadata/python-net/groupdocs.metadata.formats.document/documentpackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`PdfPackage`](/metadata/python-net/groupdocs.metadata.formats.document/pdfpackage)
