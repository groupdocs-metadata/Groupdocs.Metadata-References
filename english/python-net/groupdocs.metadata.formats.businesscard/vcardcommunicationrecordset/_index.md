---
title: VCardCommunicationRecordset class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/
is_root: false
weight: 60
---

## VCardCommunicationRecordset class

Represents a set of Communication vCard records.
These properties describe information about how to communicate with the object the vCard represents.



**Inheritance:** [`VCardCommunicationRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset) → 
[`VCardRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecordset) → 
[`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The VCardCommunicationRecordset type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/count) | Gets the number of metadata properties. |
| [telephone_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/telephone_records) | Gets the telephone numbers for telephony communication with the object. |
| [telephones](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/telephones) | Gets the telephone numbers for telephony communication with the object. |
| [email_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/email_records) | Gets the electronic mail addresses for communication with the object. |
| [emails](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/emails) | Gets the electronic mail addresses for communication with the object. |
| [mailer](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/mailer) | Gets the type of the electronic mail software that is used by the individual associated with the vCard. |
| [impp_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/impp_records) | Gets the URIs for instant messaging and presence protocol communications with the object. |
| [impp_entries](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/impp_entries) | Gets the URIs for instant messaging and presence protocol communications with the object. |
| [language_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/language_records) | Gets the languages that may be used for contacting the object. |
| [languages](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/languages) | Gets the languages that may be used for contacting the object. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.businesscard`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage)
* class [`VCardCommunicationRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset)
* class [`VCardRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecordset)
