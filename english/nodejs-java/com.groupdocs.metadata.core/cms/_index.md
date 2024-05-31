---
title: Cms
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a digital sign created with Cryptographic Message Syntax CMS - IETFs standard for cryptographically protected messages.
type: docs
weight: 34
url: /nodejs-java/com.groupdocs.metadata.core/cms/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.DigitalSignature](../../com.groupdocs.metadata.core/digitalsignature)
```
public class Cms extends DigitalSignature
```

Represents a digital sign created with Cryptographic Message Syntax (CMS) - IETF's standard for cryptographically protected messages. CMS is based on the syntax of PKCS \#7, specified in RFC 5652. Please see  https://tools.ietf.org/html/rfc5652  for more information.
## Methods

| Method | Description |
| --- | --- |
| [getDigestAlgorithms()](#getDigestAlgorithms--) | Gets the array of message-digest algorithm identifiers. |
| [getEncapsulatedContent()](#getEncapsulatedContent--) | Gets the signed content, consisting of a content type identifier and the content itself. |
| [getCertificates()](#getCertificates--) | Gets the collection of certificates. |
| [getSigners()](#getSigners--) | Gets the collection of per-signer information packages. |
| [getSignTime()](#getSignTime--) | Gets the time at which the signer (purportedly) performed the signing process. |
### getDigestAlgorithms() {#getDigestAlgorithms--}
```
public final Oid[] getDigestAlgorithms()
```


Gets the array of message-digest algorithm identifiers. There may be any number of elements in the collection, including zero.

**Returns:**
com.groupdocs.metadata.core.Oid[] - The array of message-digest algorithm identifiers.
### getEncapsulatedContent() {#getEncapsulatedContent--}
```
public final CmsEncapsulatedContent getEncapsulatedContent()
```


Gets the signed content, consisting of a content type identifier and the content itself.

**Returns:**
[CmsEncapsulatedContent](../../com.groupdocs.metadata.core/cmsencapsulatedcontent) - The signed content, consisting of a content type identifier and the content itself.
### getCertificates() {#getCertificates--}
```
public final CmsCertificate[] getCertificates()
```


Gets the collection of certificates.

**Returns:**
com.groupdocs.metadata.core.CmsCertificate[] - The collection of certificates.

--------------------

It is intended that the set of certificates be sufficient to contain certification paths from a recognized "root" or "top-level certification authority" to all of the signers in the SignerInfo field.
### getSigners() {#getSigners--}
```
public final CmsSigner[] getSigners()
```


Gets the collection of per-signer information packages.

**Returns:**
com.groupdocs.metadata.core.CmsSigner[] - The collection of per-signer information packages.

--------------------

There may be any number of elements in the collection, including zero.
### getSignTime() {#getSignTime--}
```
public Date getSignTime()
```


Gets the time at which the signer (purportedly) performed the signing process.

**Returns:**
java.util.Date - The time at which the signer (purportedly) performed the signing process.
