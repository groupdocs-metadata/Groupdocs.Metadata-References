---
title: CmsSigner
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents CMS per-signer information.
type: docs
weight: 39
url: /nodejs-java/com.groupdocs.metadata.core/cmssigner/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public class CmsSigner extends CustomPackage
```

Represents CMS per-signer information.
## Methods

| Method | Description |
| --- | --- |
| [getSignerIdentifier()](#getSignerIdentifier--) | Gets the signer's certificate (and thereby the signer's public key) raw data. |
| [getDigestAlgorithm()](#getDigestAlgorithm--) | Gets the message digest algorithm, and any associated parameters, used by the signer. |
| [getSignedAttributes()](#getSignedAttributes--) | Gets the collection of attributes that are signed. |
| [getSignatureAlgorithm()](#getSignatureAlgorithm--) | Gets the signature algorithm, and any associated parameters, used by the signer to generate the digital signature. |
| [getSignatureValue()](#getSignatureValue--) | Gets the result of digital signature generation, using the message digest and the signer's private key. |
| [getUnsignedAttributes()](#getUnsignedAttributes--) | Gets the collection of attributes that are not signed. |
| [getSigningTime()](#getSigningTime--) | Gets the time at which the signer (purportedly) performed the signing process. |
### getSignerIdentifier() {#getSignerIdentifier--}
```
public final byte[] getSignerIdentifier()
```


Gets the signer's certificate (and thereby the signer's public key) raw data.

**Returns:**
byte[] - The signer's certificate (and thereby the signer's public key) raw data.
### getDigestAlgorithm() {#getDigestAlgorithm--}
```
public final Oid getDigestAlgorithm()
```


Gets the message digest algorithm, and any associated parameters, used by the signer.

**Returns:**
[Oid](../../com.groupdocs.metadata.core/oid) - The message digest algorithm, and any associated parameters, used by the signer.
### getSignedAttributes() {#getSignedAttributes--}
```
public final CmsAttribute[] getSignedAttributes()
```


Gets the collection of attributes that are signed.

**Returns:**
com.groupdocs.metadata.core.CmsAttribute[] - The collection of attributes that are signed.
### getSignatureAlgorithm() {#getSignatureAlgorithm--}
```
public final Oid getSignatureAlgorithm()
```


Gets the signature algorithm, and any associated parameters, used by the signer to generate the digital signature.

**Returns:**
[Oid](../../com.groupdocs.metadata.core/oid) - The signature algorithm, and any associated parameters, used by the signer to generate the digital signature.
### getSignatureValue() {#getSignatureValue--}
```
public final String getSignatureValue()
```


Gets the result of digital signature generation, using the message digest and the signer's private key.

**Returns:**
java.lang.String - The result of digital signature generation, using the message digest and the signer's private key.
### getUnsignedAttributes() {#getUnsignedAttributes--}
```
public final CmsAttribute[] getUnsignedAttributes()
```


Gets the collection of attributes that are not signed.

**Returns:**
com.groupdocs.metadata.core.CmsAttribute[] - The collection of attributes that are not signed.
### getSigningTime() {#getSigningTime--}
```
public final Date getSigningTime()
```


Gets the time at which the signer (purportedly) performed the signing process.

**Returns:**
java.util.Date - The time at which the signer (purportedly) performed the signing process.
