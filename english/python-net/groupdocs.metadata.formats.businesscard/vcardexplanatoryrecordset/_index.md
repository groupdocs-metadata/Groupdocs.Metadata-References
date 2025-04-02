---
title: VCardExplanatoryRecordset class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/
is_root: false
weight: 100
---

## VCardExplanatoryRecordset class

Represents a set of Explanatory vCard records.
These properties are concerned with additional explanations, 
such as that related to informational notes or revisions specific to the vCard.



**Inheritance:** [`VCardExplanatoryRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset) → 
[`VCardRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecordset) → 
[`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The VCardExplanatoryRecordset type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/count) | Gets the number of metadata properties. |
| [category_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/category_records) | Gets the application category information about the vCard, also known as "tags". |
| [categories](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/categories) | Gets the application category information about the vCard, also known as "tags". |
| [note_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/note_records) | Gets the supplemental information or comments that are associated with the vCard. |
| [notes](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/notes) | Gets the supplemental information or comments that are associated with the vCard. |
| [product_identifier_record](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/product_identifier_record) | Gets the identifier of the product that created the vCard object. |
| [product_identifier](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/product_identifier) | Gets the identifier of the product that created the vCard object. |
| [revision](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/revision) | Gets the revision information about the current vCard. |
| [sort_string](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/sort_string) | Gets the family name or given name text to be used for national-language-specific sorting of the [`VCardIdentificationRecordset.formatted_names`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset#formatted_names) and [`VCardIdentificationRecordset.name`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset#name) types. |
| [sound_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/sound_records) | Gets the digital sound content information that annotates some aspects of the vCard. |
| [sound_binary_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/sound_binary_records) | Gets the digital sound content information that annotates some aspects of the vCard. |
| [binary_sounds](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/binary_sounds) | Gets the digital sound content information that annotates some aspects of the vCard. |
| [sound_uri_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/sound_uri_records) | Gets the digital sound content information that annotates some aspects of the vCard. |
| [uri_sounds](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/uri_sounds) | Gets the digital sound content information that annotates some aspects of the vCard. |
| [uid_record](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/uid_record) | Gets the value that represents a globally unique identifier corresponding to the individual or resource associated with the vCard. |
| [uid](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/uid) | Gets the value that represents a globally unique identifier corresponding to the individual or resource associated with the vCard. |
| [pid_identifier_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/pid_identifier_records) | Gets the global meaning of the local PID source identifier. |
| [pid_identifiers](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/pid_identifiers) | Gets the global meaning of the local PID source identifier. |
| [url_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/url_records) | Gets an array of URLs pointing to websites that represent the person in some way. |
| [urls](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/urls) | Gets an array of URLs pointing to websites that represent the person in some way. |
| [version](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/version) | Gets the version of the vCard specification. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.businesscard`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage)
* class [`VCardExplanatoryRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset)
* class [`VCardRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecordset)
