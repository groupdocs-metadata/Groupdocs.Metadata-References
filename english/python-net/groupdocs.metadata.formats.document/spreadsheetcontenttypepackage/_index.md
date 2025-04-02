---
title: SpreadsheetContentTypePackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/
is_root: false
weight: 260
---

## SpreadsheetContentTypePackage class

Represents a metadata package containing spreadsheet content type properties.



**Inheritance:** [`SpreadsheetContentTypePackage`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The SpreadsheetContentTypePackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/count) | Gets the number of metadata properties. |


### Methods
| Method | Description |
| :- | :- |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/set/#str-str) | Adds or replaces the content type property with the specified name. |
| [set](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/set/#str-str-str) | Adds or replaces the content type property with the specified name. |
| [contains](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/remove/#str) | Removes the content type property with the specified name. |
| [clear](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/clear/#) | Removes all writable metadata properties. |
| [to_list](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/to_list/#) | Creates a list from the package. |



### See Also
* module [`groupdocs.metadata.formats.document`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`SpreadsheetContentTypePackage`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage)
