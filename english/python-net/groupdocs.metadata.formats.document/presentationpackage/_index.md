---
title: PresentationPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.document/presentationpackage/
is_root: false
weight: 190
---

## PresentationPackage class

Represents a native metadata package in a presentation.



**Inheritance:** [`PresentationPackage`](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage) → 
[`DocumentPackage`](/metadata/python-net/groupdocs.metadata.formats.document/documentpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The PresentationPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/count) | Gets the number of metadata properties. |
| [application_template](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/application_template) | Gets or sets the application template. |
| [author](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/author) | Gets or sets the document's author. |
| [category](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/category) | Gets or sets the category. |
| [comments](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/comments) | Gets or sets the comments. |
| [company](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/company) | Gets or sets the company. |
| [content_status](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/content_status) | Gets or sets the content status. Can be updated in a PPTX document only. |
| [content_type](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/content_type) | Gets or sets the content type. Can be updated in a PPTX document only. |
| [created_time](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/created_time) | Gets or sets the document created date. |
| [keywords](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/keywords) | Gets or sets the keywords. |
| [last_printed_date](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/last_printed_date) | Gets or sets the last printed date. |
| [last_saved_time](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/last_saved_time) | Gets the date and time when the presentation was modified last time. |
| [last_saved_by](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/last_saved_by) | Gets or sets the name of the last author. |
| [manager](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/manager) | Gets or sets the manager. |
| [name_of_application](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/name_of_application) | Gets the name of the application created the document. |
| [revision_number](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/revision_number) | Gets or sets the revision number. |
| [subject](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/subject) | Gets or sets the subject. |
| [title](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/title) | Gets or sets the title of the document. |
| [version](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/version) | Gets the application version. |
| [hyperlink_base](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/hyperlink_base) | Gets or sets the hyperlink base. |
| [presentation_format](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/presentation_format) | Gets the presentation format. |
| [shared_doc](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/shared_doc) | Gets or sets a value indicating whether the presentation is shared between multiple people. Can be updated in a PPTX document only. |
| [total_editing_time](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/total_editing_time) | Gets or sets the total editing time of the document. |


### Methods
| Method | Description |
| :- | :- |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/set/#str-str) | Adds or replaces the metadata property with the specified name. |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/set/#str-bool) | Adds or replaces the metadata property with the specified name. |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/set/#str-DateTime) | Adds or replaces the metadata property with the specified name. |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/set/#str-int) | Adds or replaces the metadata property with the specified name. |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/set/#str-float) | Adds or replaces the metadata property with the specified name. |
| [contains](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/remove/#str) | Removes a writable metadata property by the specified name. |
| [clear](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/clear/#) | Removes all writable metadata properties from the package. |
| [clear_built_in_properties](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/clear_built_in_properties/#) | Removes all built-in metadata properties. |
| [clear_custom_properties](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage/clear_custom_properties/#) | Removes all custom metadata properties. |



### Remarks 


**Learn more** |
|
 |

### Example 


This example demonstrates how to update built-in metadata properties in a presentation.

### See Also
* module [`groupdocs.metadata.formats.document`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`DocumentPackage`](/metadata/python-net/groupdocs.metadata.formats.document/documentpackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`PresentationPackage`](/metadata/python-net/groupdocs.metadata.formats.document/presentationpackage)
