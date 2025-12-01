---
title: WordProcessingInspectionPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 350
url: /python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/
is_root: false
---

## WordProcessingInspectionPackage class

Contains information about document parts that can be considered as metadata in some cases.



**Inheritance:** [`WordProcessingInspectionPackage`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The WordProcessingInspectionPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/count) | Gets the number of metadata properties. |
| [comments](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/comments) | Gets an array of the user comments. |
| [fields](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/fields) | Gets an array of document fields. |
| [hidden_text](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/hidden_text) | Gets an array of hidden text fragments extracted from the document. |
| [digital_signatures](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/digital_signatures) | Gets an array of digital signatures presented in the document. |
| [revisions](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/revisions) | Gets an array of digital signatures presented in the document. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`clear_comments(self)`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clear_comments/#) | Removes all detected user comments from the document. |
| [`clear_fields(self)`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clear_fields/#) | Removes all detected fields from the document. |
| [`clear_hidden_text(self)`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clear_hidden_text/#) | Removes all hidden text fragments from the document. |
| [`accept_all_revisions(self)`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/accept_all_revisions/#) | Accepts all detected revisions in the document. |
| [`reject_all_revisions(self)`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/reject_all_revisions/#) | Rejects all detected revisions in the document. |



### Remarks 


**Learn more** |
|
 |

### Example 


This code sample shows how to update inspection properties in a WordProcessing document.

### See Also
* module [`groupdocs.metadata.formats.document`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`WordProcessingInspectionPackage`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage)
