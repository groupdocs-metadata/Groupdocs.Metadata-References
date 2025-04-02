---
title: PdfInspectionPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/
is_root: false
weight: 130
---

## PdfInspectionPackage class

Contains information about PDF document parts that can be considered as metadata in some cases.



**Inheritance:** [`PdfInspectionPackage`](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The PdfInspectionPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/count) | Gets the number of metadata properties. |
| [annotations](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/annotations) | Gets an array of the annotations. |
| [attachments](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/attachments) | Gets an array of the attachments. |
| [bookmarks](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/bookmarks) | Gets an array of the bookmarks. |
| [fields](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/fields) | Gets an array of the form fields. |
| [digital_signatures](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/digital_signatures) | Gets an array of the digital signatures. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [clear_annotations](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/clear_annotations/#) | Removes all detected annotations from the document. |
| [clear_attachments](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/clear_attachments/#) | Removes all detected attachments from the document. |
| [clear_bookmarks](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/clear_bookmarks/#) | Removes all detected bookmarks from the document. |
| [clear_fields](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/clear_fields/#) | Removes all detected form fields from the document. |
| [clear_digital_signatures](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/clear_digital_signatures/#) | Removes all detected digital signatures from the document. |



### Remarks 


**Learn more** |
|
 |

### Example 


This code sample demonstrates how to remove the inspection properties in a PDF document.

### See Also
* module [`groupdocs.metadata.formats.document`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`PdfInspectionPackage`](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage)
