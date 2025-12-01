---
title: VCardDeliveryAddressingRecordset class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 90
url: /python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/
is_root: false
---

## VCardDeliveryAddressingRecordset class

Represents a set of Delivery Addressing vCard records.
These types are concerned with information related to 
the delivery addressing or label for the vCard object.



**Inheritance:** [`VCardDeliveryAddressingRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset) → 
[`VCardRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecordset) → 
[`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The VCardDeliveryAddressingRecordset type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/count) | Gets the number of metadata properties. |
| [address_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/address_records) | Gets the components of the delivery address of the object. |
| [addresses](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/addresses) | Gets the components of the delivery address of the object. |
| [label_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/label_records) | Gets an array containing the formatted text corresponding to delivery address of the object. |
| [labels](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/labels) | Gets an array containing the formatted text corresponding to delivery address of the object. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.businesscard`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage)
* class [`VCardDeliveryAddressingRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset)
* class [`VCardRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecordset)
