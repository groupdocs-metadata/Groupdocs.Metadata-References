---
title: SpreadsheetContentTypePackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 260
url: /python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/
is_root: false
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
| [`set(self, property_name, property_value)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/set/#system.string-system.string) | Adds or replaces the content type property with the specified name. |
| [`set(self, property_name, property_value, property_type)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/set/#system.string-system.string-system.string) | Adds or replaces the content type property with the specified name. |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/remove/#system.string) | Removes the content type property with the specified name. |
| [`clear(self)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/clear/#) | Removes all writable metadata properties. |
| [`to_list(self)`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage/to_list/#) | Creates a list from the package. |



### See Also
* module [`groupdocs.metadata.formats.document`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`SpreadsheetContentTypePackage`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetcontenttypepackage)
