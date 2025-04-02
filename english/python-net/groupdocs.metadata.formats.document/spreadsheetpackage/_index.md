---
title: SpreadsheetPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.document/spreadsheetpackage/
is_root: false
weight: 290
---

## SpreadsheetPackage class

Represents a native metadata package in a spreadsheet.



**Inheritance:** [`SpreadsheetPackage`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage) → 
[`DocumentPackage`](/metadata/python-net/groupdocs.metadata.formats.document/documentpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The SpreadsheetPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/count) | Gets the number of metadata properties. |
| [language](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/language) | Gets or sets the document language. |
| [author](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/author) | Gets or sets the document author. |
| [category](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/category) | Gets or sets the category. |
| [comments](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/comments) | Gets or sets the comments. |
| [company](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/company) | Gets or sets the company. |
| [content_status](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/content_status) | Gets or sets the content status. |
| [content_type](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/content_type) | Gets or sets the content type. |
| [created_time](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/created_time) | Gets or sets the document created date. |
| [total_editing_time](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/total_editing_time) | Gets or sets the total editing time in minutes. |
| [hyperlink_base](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/hyperlink_base) | Gets or sets the hyperlink base. |
| [keywords](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/keywords) | Gets or sets the keywords. |
| [last_saved_time](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/last_saved_time) | Gets or sets the time of the last saving in UTC. |
| [last_printed_date](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/last_printed_date) | Gets or sets the last printed date in UTC. |
| [last_saved_by](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/last_saved_by) | Gets or sets the name of the last author. |
| [manager](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/manager) | Gets or sets the manager. |
| [name_of_application](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/name_of_application) | Gets or sets the name of application. |
| [revision](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/revision) | Gets or sets the document revision number. |
| [subject](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/subject) | Gets or sets the subject. |
| [template](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/template) | Gets or sets the document template name. |
| [title](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/title) | Gets or sets the title of the document. |
| [version](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/version) | Gets or sets the version number of the application that created the document. |
| [content_type_properties](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/content_type_properties) | Gets the metadata package containing the content type properties. |


### Methods
| Method | Description |
| :- | :- |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/set/#str-str) | Adds or replaces the metadata property with the specified name. |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/set/#str-bool) | Adds or replaces the metadata property with the specified name. |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/set/#str-DateTime) | Adds or replaces the metadata property with the specified name. |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/set/#str-int) | Adds or replaces the metadata property with the specified name. |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/set/#str-float) | Adds or replaces the metadata property with the specified name. |
| [contains](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/remove/#str) | Removes a writable metadata property by the specified name. |
| [clear](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/clear/#) | Removes all writable metadata properties from the package. |
| [clear_built_in_properties](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/clear_built_in_properties/#) | Removes all built-in metadata properties. |
| [clear_custom_properties](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage/clear_custom_properties/#) | Removes all custom metadata properties. |



### Remarks 


**Learn more** |
|
 |

### Example 


This example shows how to update built-in metadata properties in a spreadsheet.

### See Also
* module [`groupdocs.metadata.formats.document`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`DocumentPackage`](/metadata/python-net/groupdocs.metadata.formats.document/documentpackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`SpreadsheetPackage`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetpackage)
