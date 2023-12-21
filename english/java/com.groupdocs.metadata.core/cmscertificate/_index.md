---
title: CmsCertificate
second_title: GroupDocs.Signature for Java API Reference
description: Represents a CMS certificate.
type: docs
weight: 36
url: /java/com.groupdocs.metadata.core/cmscertificate/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public class CmsCertificate extends CustomPackage
```

Represents a CMS certificate.
## Methods

| Method | Description |
| --- | --- |
| [getNotAfter()](#getNotAfter--) | Gets the date in local time after which a certificate is no longer valid. |
| [getNotBefore()](#getNotBefore--) | Gets the date in local time on which a certificate becomes valid. |
| [getRawData()](#getRawData--) | Gets the raw data of this certificate. |
### getNotAfter() {#getNotAfter--}
```
public final Date getNotAfter()
```


Gets the date in local time after which a certificate is no longer valid.

**Returns:**
java.util.Date - The date in local time after which a certificate is no longer valid.
### getNotBefore() {#getNotBefore--}
```
public final Date getNotBefore()
```


Gets the date in local time on which a certificate becomes valid.

**Returns:**
java.util.Date - The date in local time on which a certificate becomes valid.
### getRawData() {#getRawData--}
```
public final byte[] getRawData()
```


Gets the raw data of this certificate.

**Returns:**
byte[] - The raw data of this certificate.
