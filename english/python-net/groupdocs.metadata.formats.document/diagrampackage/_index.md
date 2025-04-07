---
title: DiagramPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.document/diagrampackage/
is_root: false
weight: 10
---

## DiagramPackage class

Represents a native metadata package in a diagram format.



**Inheritance:** [`DiagramPackage`](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage) → 
[`DocumentPackage`](/metadata/python-net/groupdocs.metadata.formats.document/documentpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The DiagramPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/count) | Gets the number of metadata properties. |
| [alternate_names](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/alternate_names) | Gets or sets the alternate names for the document. Can be updated in VDX and VSX formats only. |
| [build_number_created](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/build_number_created) | Gets the full build number of the instance used to create the document. |
| [build_number_edited](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/build_number_edited) | Gets the build number of the instance last used to edit the document. |
| [category](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/category) | Gets or sets the descriptive text for the type of drawing, such as flowchart or office layout.<br/>This text can also be entered in the Microsoft Visio user interface in the Category box in the Properties dialog box. |
| [company](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/company) | Gets or sets the user-entered information identifying the company creating the drawing or the company the drawing is being created for.<br/>Maximum length is 63 characters. |
| [creator](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/creator) | Gets or sets the person who created or last updated the file.<br/>The maximum length is 63 characters.. |
| [description](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/description) | Gets or sets a descriptive text string for the document.<br/>Use this element to store important information about the document, such as its purpose, recent changes, or pending changes.<br/>The maximum is 191 characters. |
| [hyperlink_base](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/hyperlink_base) | Gets or sets the path to be used for relative hyperlinks (hyperlinks for which the linked file location is described in relation to the Microsoft Visio diagram).<br/>By default, a hyperlink path is relative to the current document unless a different path is specified in this element.<br/>Maximum length is 256 characters. |
| [keywords](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/keywords) | Gets or sets a text string that identifies topics or other important information about the file, such as project name, client name, or version number.<br/>The maximum string length is 63 characters. |
| [language](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/language) | Gets or sets the language of the document.<br/>Can be updated in VSD and VSDX formats only. |
| [manager](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/manager) | Gets or sets a user-entered text string identifying the person in charge of the project or department.<br/>The maximum length is 63 characters. |
| [preview_picture](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/preview_picture) | Gets or sets the preview picture. |
| [subject](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/subject) | Gets or sets a user-defined text string that describes the contents of the document.<br/>Maximum length is 63 characters. |
| [template](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/template) | Gets or sets a string value specifying the file name of the template from which the document was created. |
| [time_created](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/time_created) | Gets or sets a date and time value indicating when the document was created. |
| [time_edited](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/time_edited) | Gets a date and time value indicating when the document was last edited. |
| [time_printed](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/time_printed) | Gets a date and time value indicating when the document was last printed. |
| [time_saved](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/time_saved) | Gets a date and time value indicating when the document was last saved. |
| [title](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/title) | Gets or sets a user-defined text string that serves as a descriptive title for the document.<br/>Maximum length is 63 characters. |


### Methods
| Method | Description |
| :- | :- |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/set/#str-str) | Adds or replaces the metadata property with the specified name. |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/set/#str-bool) | Adds or replaces the metadata property with the specified name. |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/set/#str-float) | Adds or replaces the metadata property with the specified name. |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/set/#str-DateTime) | Adds or replaces the metadata property with the specified name. |
| [contains](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/remove/#str) | Removes a writable metadata property by the specified name. |
| [clear](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/clear/#) | Removes all writable metadata properties from the package. |
| [clear_built_in_properties](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/clear_built_in_properties/#) | Removes all built-in metadata properties. |
| [clear_custom_properties](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage/clear_custom_properties/#) | Removes all custom metadata properties. |



### Remarks 


**Learn more** |
|
 |

### Example 


This code sample demonstrates how to extract built-in metadata properties from a diagram.

### See Also
* module [`groupdocs.metadata.formats.document`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`DiagramPackage`](/metadata/python-net/groupdocs.metadata.formats.document/diagrampackage)
* class [`DocumentPackage`](/metadata/python-net/groupdocs.metadata.formats.document/documentpackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
