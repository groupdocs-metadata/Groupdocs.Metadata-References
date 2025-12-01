---
title: VCardDateTimeRecord class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 80
url: /python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/
is_root: false
---

## VCardDateTimeRecord class

Represents vCard date time record metadata class.



**Inheritance:** [`VCardDateTimeRecord`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord) → 
[`VCardRecord`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord) → 
[`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The VCardDateTimeRecord type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/count) | Gets the number of metadata properties. |
| [group](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/group) | Gets the grouping value. |
| [value_parameters](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/value_parameters) | Gets the value parameters. |
| [pref_parameter](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/pref_parameter) | Gets the preferred parameter. |
| [alt_id_parameter](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/alt_id_parameter) | Gets the alternative representations parameter value. |
| [type_parameters](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/type_parameters) | Gets the type parameter values. |
| [encoding_parameter](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/encoding_parameter) | Gets the encoding parameter value. |
| [language_parameter](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/language_parameter) | Gets the language parameter value. |
| [anonym_parameters](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/anonym_parameters) | Gets the anonymous parameters. |
| [content_type](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/content_type) | Gets the content type of record. |
| [type_name](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/type_name) | Gets the type of the record. |
| [value](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/value) | Gets the record value. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.businesscard`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage)
* class [`VCardDateTimeRecord`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddatetimerecord)
* class [`VCardRecord`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord)
