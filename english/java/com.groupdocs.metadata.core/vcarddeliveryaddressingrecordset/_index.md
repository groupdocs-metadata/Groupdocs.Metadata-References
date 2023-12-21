---
title: VCardDeliveryAddressingRecordset
second_title: GroupDocs.Signature for Java API Reference
description: Represents a set of Delivery Addressing vCard records.
type: docs
weight: 262
url: /java/com.groupdocs.metadata.core/vcarddeliveryaddressingrecordset/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.VCardBasePackage](../../com.groupdocs.metadata.core/vcardbasepackage), [com.groupdocs.metadata.core.VCardRecordset](../../com.groupdocs.metadata.core/vcardrecordset)
```
public class VCardDeliveryAddressingRecordset extends VCardRecordset
```

Represents a set of Delivery Addressing vCard records. These types are concerned with information related to the delivery addressing or label for the vCard object.

**Learn more**

 *  [Working with vCard metadata][]


[Working with vCard metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+vCard+metadata
## Methods

| Method | Description |
| --- | --- |
| [getAddressRecords()](#getAddressRecords--) | Gets the components of the delivery address of the object. |
| [getAddresses()](#getAddresses--) | Gets the components of the delivery address of the object. |
| [getLabelRecords()](#getLabelRecords--) | Gets an array containing the formatted text corresponding to delivery address of the object. |
| [getLabels()](#getLabels--) | Gets an array containing the formatted text corresponding to delivery address of the object. |
### getAddressRecords() {#getAddressRecords--}
```
public final VCardTextRecord[] getAddressRecords()
```


Gets the components of the delivery address of the object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The components of the delivery address of the object.
### getAddresses() {#getAddresses--}
```
public final String[] getAddresses()
```


Gets the components of the delivery address of the object.

**Returns:**
java.lang.String[] - The components of the delivery address of the object.

--------------------

This property is a simplified version of  AddressRecords .
### getLabelRecords() {#getLabelRecords--}
```
public final VCardTextRecord[] getLabelRecords()
```


Gets an array containing the formatted text corresponding to delivery address of the object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - An array containing the formatted text corresponding to delivery address of the object.
### getLabels() {#getLabels--}
```
public final String[] getLabels()
```


Gets an array containing the formatted text corresponding to delivery address of the object.

**Returns:**
java.lang.String[] - An array containing the formatted text corresponding to delivery address of the object.

--------------------

This property is a simplified version of  LabelRecords .
