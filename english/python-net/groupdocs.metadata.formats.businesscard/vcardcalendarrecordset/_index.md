---
title: VCardCalendarRecordset class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/
is_root: false
weight: 40
---

## VCardCalendarRecordset class

Represents a set of Calendar vCard records.



**Inheritance:** [`VCardCalendarRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset) → 
[`VCardRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecordset) → 
[`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The VCardCalendarRecordset type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/count) | Gets the number of metadata properties. |
| [busy_time_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/busy_time_records) | Gets the URIs for the busy time associated with the object. |
| [busy_time_entries](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/busy_time_entries) | Gets the URIs for the busy time associated with the object. |
| [calendar_address_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendar_address_records) | Gets the calendar user addresses to which a scheduling request should be sent for the object represented by the vCard. |
| [calendar_addresses](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendar_addresses) | Gets the calendar user addresses to which a scheduling request should be sent for the object represented by the vCard. |
| [calendar_uri_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendar_uri_records) | Gets the URIs for the calendar associated with the object represented by the vCard. |
| [uri_calendar_entries](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/uri_calendar_entries) | Gets the URIs for the calendar associated with the object represented by the vCard. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.businesscard`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage)
* class [`VCardCalendarRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset)
* class [`VCardRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecordset)
