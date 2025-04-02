---
title: ProjectManagementPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.document/projectmanagementpackage/
is_root: false
weight: 230
---

## ProjectManagementPackage class

Represents a native metadata package in a project management file.



**Inheritance:** [`ProjectManagementPackage`](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage) → 
[`DocumentPackage`](/metadata/python-net/groupdocs.metadata.formats.document/documentpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The ProjectManagementPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/count) | Gets the number of metadata properties. |
| [author](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/author) | Gets or sets the author of the project. |
| [category](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/category) | Gets or sets the category. |
| [comments](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/comments) | Gets or sets the user comments. |
| [company](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/company) | Gets or sets the company. |
| [creation_date](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/creation_date) | Gets or sets the creation date. |
| [hyperlink_base](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/hyperlink_base) | Gets or sets the hyperlink base. |
| [keywords](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/keywords) | Gets or sets the keywords. |
| [last_author](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/last_author) | Gets or sets the last author. |
| [revision](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/revision) | Gets or sets the revision number. |
| [subject](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/subject) | Gets or sets the subject. |
| [title](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/title) | Gets or sets the title. |
| [template](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/template) | Gets or sets the template. |
| [manager](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/manager) | Gets or sets the project manager. |
| [last_saved](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/last_saved) | Gets or sets the date when the project was saved last time. |
| [save_version](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/save_version) | Gets the version of Microsoft Office Project from which a project file was saved. |
| [last_printed](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/last_printed) | Gets or sets the project's last print time. |
| [guid](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/guid) | Gets or sets the id of the project. |


### Methods
| Method | Description |
| :- | :- |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/set/#str-str) | Adds or replaces the metadata property with the specified name. |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/set/#str-float) | Adds or replaces the metadata property with the specified name. |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/set/#str-bool) | Adds or replaces the metadata property with the specified name. |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/set/#str-DateTime) | Adds or replaces the metadata property with the specified name. |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/set/#str-int) | Adds or replaces the metadata property with the specified name. |
| [contains](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/remove/#str) | Removes a writable metadata property by the specified name. |
| [clear](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/clear/#) | Removes all writable metadata properties from the package. |
| [clear_built_in_properties](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/clear_built_in_properties/#) | Removes all built-in metadata properties. |
| [clear_custom_properties](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage/clear_custom_properties/#) | Removes all custom metadata properties. |



### Remarks 


**Learn more** |
|
 |

### Example 


This code sample demonstrates how to update built-in properties in a ProjectManagement document.

### See Also
* module [`groupdocs.metadata.formats.document`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`DocumentPackage`](/metadata/python-net/groupdocs.metadata.formats.document/documentpackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`ProjectManagementPackage`](/metadata/python-net/groupdocs.metadata.formats.document/projectmanagementpackage)
