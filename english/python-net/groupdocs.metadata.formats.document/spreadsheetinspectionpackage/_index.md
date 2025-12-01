---
title: SpreadsheetInspectionPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 280
url: /python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/
is_root: false
---

## SpreadsheetInspectionPackage class

Contains information about spreadsheet parts that can be considered as metadata in some cases.



**Inheritance:** [`SpreadsheetInspectionPackage`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The SpreadsheetInspectionPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/count) | Gets the number of metadata properties. |
| [comments](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/comments) | Gets an array of the user comments. |
| [hidden_sheets](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/hidden_sheets) | Gets an array of the hidden sheets. |
| [digital_signatures](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/digital_signatures) | Gets an array of digital signatures presented in the document. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`clear_comments(self)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/clear_comments/#) | Removes all detected user comments from the spreadsheet. |
| [`clear_hidden_sheets(self)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/clear_hidden_sheets/#) | Removes all detected hidden sheets from the spreadsheet. |
| [`clear_digital_signatures(self)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/clear_digital_signatures/#) | Removes all detected digital signatures from the spreadsheet. |



### Remarks 


**Learn more** |
|
 |

### Example 


This code sample shows hot to remove inspection properties from a spreadsheet.

### See Also
* module [`groupdocs.metadata.formats.document`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`SpreadsheetInspectionPackage`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage)
