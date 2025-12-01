---
title: VCardSecurityRecordset class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 190
url: /python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/
is_root: false
---

## VCardSecurityRecordset class

Represents a set of Security vCard records.
These properties are concerned with the security of 
communication pathways or access to the vCard.



**Inheritance:** [`VCardSecurityRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset) → 
[`VCardRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecordset) → 
[`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The VCardSecurityRecordset type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/count) | Gets the number of metadata properties. |
| [access_classification](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/access_classification) | Gets the sensitivity of the information in the vCard. |
| [public_key_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/public_key_records) | Gets the public keys or authentication certificates associated with the object. |
| [public_key_binary_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/public_key_binary_records) | Gets the public keys or authentication certificates associated with the object. |
| [binary_public_keys](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/binary_public_keys) | Gets the public keys or authentication certificates associated with the object. |
| [public_key_uri_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/public_key_uri_records) | Gets the public keys or authentication certificates associated with the object. |
| [uri_public_keys](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/uri_public_keys) | Gets the public keys or authentication certificates associated with the object. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.businesscard`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage)
* class [`VCardRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecordset)
* class [`VCardSecurityRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset)
