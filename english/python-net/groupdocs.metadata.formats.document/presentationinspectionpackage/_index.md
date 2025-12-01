---
title: PresentationInspectionPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 180
url: /python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/
is_root: false
---

## PresentationInspectionPackage class

Contains information about presentation parts that can be considered as metadata in some cases.



**Inheritance:** [`PresentationInspectionPackage`](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The PresentationInspectionPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/count) | Gets the number of metadata properties. |
| [hidden_slides](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/hidden_slides) | Gets an array of the hidden slides. |
| [comments](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/comments) | Gets an array of the comments. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`clear_comments(self)`](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/clear_comments/#) | Removes all detected user comments from the presentation. |
| [`clear_hidden_slides(self)`](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/clear_hidden_slides/#) | Removes all detected hidden slides from the presentation. |



### Remarks 


**Learn more** |
|
 |

### Example 


This code sample demonstrates how to clean inspection properties in a presentation.

### See Also
* module [`groupdocs.metadata.formats.document`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`PresentationInspectionPackage`](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage)
