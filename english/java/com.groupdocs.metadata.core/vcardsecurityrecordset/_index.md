---
title: VCardSecurityRecordset
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a set of Security vCard records.
type: docs
weight: 274
url: /java/com.groupdocs.metadata.core/vcardsecurityrecordset/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.VCardBasePackage](../../com.groupdocs.metadata.core/vcardbasepackage), [com.groupdocs.metadata.core.VCardRecordset](../../com.groupdocs.metadata.core/vcardrecordset)
```
public class VCardSecurityRecordset extends VCardRecordset
```

Represents a set of Security vCard records. These properties are concerned with the security of communication pathways or access to the vCard.
## Methods

| Method | Description |
| --- | --- |
| [getAccessClassification()](#getAccessClassification--) | Gets the sensitivity of the information in the vCard. |
| [getPublicKeyRecords()](#getPublicKeyRecords--) | Gets the public keys or authentication certificates associated with the object. |
| [getPublicKeyBinaryRecords()](#getPublicKeyBinaryRecords--) | Gets the public keys or authentication certificates associated with the object. |
| [getBinaryPublicKeys()](#getBinaryPublicKeys--) | Gets the public keys or authentication certificates associated with the object. |
| [getPublicKeyUriRecords()](#getPublicKeyUriRecords--) | Gets the public keys or authentication certificates associated with the object. |
| [getUriPublicKeys()](#getUriPublicKeys--) | Gets the public keys or authentication certificates associated with the object. |
### getAccessClassification() {#getAccessClassification--}
```
public final String getAccessClassification()
```


Gets the sensitivity of the information in the vCard.

**Returns:**
java.lang.String - The sensitivity of the information in the vCard.
### getPublicKeyRecords() {#getPublicKeyRecords--}
```
public final VCardRecord[] getPublicKeyRecords()
```


Gets the public keys or authentication certificates associated with the object.

**Returns:**
com.groupdocs.metadata.core.VCardRecord[] - The public keys or authentication certificates associated with the object.
### getPublicKeyBinaryRecords() {#getPublicKeyBinaryRecords--}
```
public final VCardBinaryRecord[] getPublicKeyBinaryRecords()
```


Gets the public keys or authentication certificates associated with the object.

**Returns:**
com.groupdocs.metadata.core.VCardBinaryRecord[] - The public keys or authentication certificates associated with the object.

--------------------

This property is a simplified version of  PublicKeyRecords .
### getBinaryPublicKeys() {#getBinaryPublicKeys--}
```
public final byte[][] getBinaryPublicKeys()
```


Gets the public keys or authentication certificates associated with the object.

**Returns:**
byte[][] - The public keys or authentication certificates associated with the object.

--------------------

This property is a simplified version of  PublicKeyBinaryRecords .
### getPublicKeyUriRecords() {#getPublicKeyUriRecords--}
```
public final VCardTextRecord[] getPublicKeyUriRecords()
```


Gets the public keys or authentication certificates associated with the object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The public keys or authentication certificates associated with the object.

--------------------

This property is a simplified version of  PublicKeyRecords .
### getUriPublicKeys() {#getUriPublicKeys--}
```
public final String[] getUriPublicKeys()
```


Gets the public keys or authentication certificates associated with the object.

**Returns:**
java.lang.String[] - The public keys or authentication certificates associated with the object.

--------------------

This property is a simplified version of  PublicKeyUriRecords .
