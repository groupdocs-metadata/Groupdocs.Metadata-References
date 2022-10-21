---
title: DigitalSignature
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a digital signature used to sign a document.
type: docs
weight: 46
url: /java/com.groupdocs.metadata.core/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public class DigitalSignature extends CustomPackage
```

Represents a digital signature used to sign a document.
## Methods

| Method | Description |
| --- | --- |
| [getComments()](#getComments--) | Gets the signing purpose comment. |
| [isValid()](#isValid--) | Gets a value indicating whether the signature is valid. |
| [getSignTime()](#getSignTime--) | Gets the time the document was signed. |
| [getCertificateSubject()](#getCertificateSubject--) | Gets the subject distinguished name from a certificate. |
| [getCertificateRawData()](#getCertificateRawData--) | Gets the certificate raw data. |
### getComments() {#getComments--}
```
public final String getComments()
```


Gets the signing purpose comment.

**Returns:**
java.lang.String - The signing purpose comment.
### isValid() {#isValid--}
```
public Boolean isValid()
```


Gets a value indicating whether the signature is valid.

**Returns:**
java.lang.Boolean - True if the the signature is valid; otherwise, false. Null indicates that validation is unavailable for the signature.
### getSignTime() {#getSignTime--}
```
public Date getSignTime()
```


Gets the time the document was signed.

**Returns:**
java.util.Date - The time the document was signed.
### getCertificateSubject() {#getCertificateSubject--}
```
public final String getCertificateSubject()
```


Gets the subject distinguished name from a certificate.

**Returns:**
java.lang.String - The subject distinguished name from a certificate.
### getCertificateRawData() {#getCertificateRawData--}
```
public final byte[] getCertificateRawData()
```


Gets the certificate raw data.

**Returns:**
byte[] - The certificate raw data.
