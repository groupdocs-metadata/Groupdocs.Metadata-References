---
title: VCardCard class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.businesscard/vcardcard/
is_root: false
weight: 50
---

## VCardCard class

Represents a single card extracted from a VCard file.



**Inheritance:** [`VCardCard`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard) → 
[`VCardRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecordset) → 
[`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The VCardCard type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/count) | Gets the number of metadata properties. |
| [general_recordset](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/general_recordset) | Gets the general records. |
| [identification_recordset](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/identification_recordset) | Gets the identification records. |
| [delivery_addressing_recordset](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/delivery_addressing_recordset) | Gets the delivery addressing records. |
| [communication_recordset](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/communication_recordset) | Gets the communication records. |
| [geographical_recordset](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/geographical_recordset) | Gets the geographical records. |
| [organizational_recordset](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/organizational_recordset) | Gets the organizational records. |
| [explanatory_recordset](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/explanatory_recordset) | Gets the explanatory records. |
| [security_recordset](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/security_recordset) | Gets the security records. |
| [calendar_recordset](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/calendar_recordset) | Gets the calendar records. |
| [extension_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/extension_records) | Gets the private extension records. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [get_available_groups](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/get_available_groups/#) | Gets the available group names. |
| [filter_by_group](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/filter_by_group/#str) | Filters all vCard records by the group name passed as a parameter.<br/>For more information please see the [`VCardCard.get_available_groups`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/get_available_groups) method. |
| [filter_home_tags](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/filter_home_tags/#) | Filters all vCard records marked with the HOME tag. |
| [filter_work_tags](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/filter_work_tags/#) | Filters all vCard records marked with the WORK tag. |
| [filter_preferred](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard/filter_preferred/#) | Filters the preferred records. |



### Remarks 


**Learn more** |
|
 |

### Example 


This example shows how to use vCard property filters.

### See Also
* module [`groupdocs.metadata.formats.businesscard`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage)
* class [`VCardCard`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcard)
* class [`VCardRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecordset)
