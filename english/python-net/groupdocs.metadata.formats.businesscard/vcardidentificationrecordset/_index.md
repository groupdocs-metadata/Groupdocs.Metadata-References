---
title: VCardIdentificationRecordset class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/
is_root: false
weight: 130
---

## VCardIdentificationRecordset class

Represents a set of Identification vCard records.
These types are used to capture information associated with 
the identification and naming of the entity associated with the vCard.



**Inheritance:** [`VCardIdentificationRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset) → 
[`VCardRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecordset) → 
[`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The VCardIdentificationRecordset type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/count) | Gets the number of metadata properties. |
| [formatted_name_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/formatted_name_records) | Gets an array containing the formatted text corresponding to the name of the object. |
| [formatted_names](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/formatted_names) | Gets an array containing the formatted text corresponding to the name of the object. |
| [name_record](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/name_record) | Gets the components of the name of the object. |
| [name](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/name) | Gets the components of the name of the object. |
| [nickname_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/nickname_records) | Gets an array containing the text corresponding to the nickname of the object. |
| [nicknames](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/nicknames) | Gets an array containing the text corresponding to the nickname of the object. |
| [photo_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photo_records) | Gets an array containing the image or photograph information that annotates some aspects of the object. |
| [photo_binary_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photo_binary_records) | Gets an array containing the image or photograph information represented as binary data that annotates some aspects of the object. |
| [binary_photos](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/binary_photos) | Gets an array containing the image or photograph information represented as binary data that annotates some aspects of the object. |
| [photo_uri_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photo_uri_records) | Gets an array containing the image or photograph information represented by URIs that annotates some aspects of the object. |
| [uri_photos](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/uri_photos) | Gets an array containing the image or photograph information represented by URIs that annotates some aspects of the object. |
| [birthdate_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdate_records) | Gets an array containing the birth date of the object in different representations. |
| [birthdate_date_time_record](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdate_date_time_record) | Gets the birth date of the object. |
| [date_time_birthdate](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/date_time_birthdate) | Gets the birth date of the object. |
| [birthdate_text_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdate_text_records) | Gets an array containing the birth date of the object in different text representations. |
| [text_birthdates](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/text_birthdates) | Gets an array containing the birth date of the object in different text representations. |
| [anniversary_record](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversary_record) | Gets the date of marriage, or equivalent, of the object. |
| [anniversary_date_time_record](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversary_date_time_record) | Gets the date of marriage represented as a single date-and-or-time value. |
| [date_time_anniversary](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/date_time_anniversary) | Gets the date of marriage represented as a single date-and-or-time value. |
| [anniversary_text_record](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversary_text_record) | Gets the date of marriage represented as a single text value. |
| [text_anniversary](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/text_anniversary) | Gets the date of marriage represented as a single text value. |
| [gender_record](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/gender_record) | Gets the components of the sex and gender identity of the object. |
| [gender](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/gender) | Gets the components of the sex and gender identity of the object. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.businesscard`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage)
* class [`VCardIdentificationRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset)
* class [`VCardRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecordset)
