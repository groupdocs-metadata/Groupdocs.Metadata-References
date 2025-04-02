---
title: VCardRecord class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.businesscard/vcardrecord/
is_root: false
weight: 160
---

## VCardRecord class

Represents abstract vCard record metadata class.



**Inheritance:** [`VCardRecord`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord) → 
[`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The VCardRecord type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/count) | Gets the number of metadata properties. |
| [group](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/group) | Gets the grouping value. |
| [value_parameters](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/value_parameters) | Gets the value parameters. |
| [pref_parameter](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/pref_parameter) | Gets the preferred parameter. |
| [alt_id_parameter](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/alt_id_parameter) | Gets the alternative representations parameter value. |
| [type_parameters](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/type_parameters) | Gets the type parameter values. |
| [encoding_parameter](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/encoding_parameter) | Gets the encoding parameter value. |
| [language_parameter](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/language_parameter) | Gets the language parameter value. |
| [anonym_parameters](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/anonym_parameters) | Gets the anonymous parameters. |
| [content_type](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/content_type) | Gets the content type of record. |
| [type_name](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/type_name) | Gets the type of the record. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.businesscard`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage)
* class [`VCardRecord`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecord)
