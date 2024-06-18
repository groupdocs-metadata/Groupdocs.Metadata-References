---
title: VCardBinaryRecord
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents vCard binary record metadata class.
type: docs
weight: 265
url: /nodejs-java/com.groupdocs.metadata.core/vcardbinaryrecord/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.VCardBasePackage](../../com.groupdocs.metadata.core/vcardbasepackage), [com.groupdocs.metadata.core.VCardRecord](../../com.groupdocs.metadata.core/vcardrecord)

**All Implemented Interfaces:**
com.groupdocs.metadata.core.IVCardRecord
```
public class VCardBinaryRecord extends VCardRecord implements IVCardRecord<byte[]>
```

Represents vCard binary record metadata class.

**Learn more**

 *  [Working with vCard metadata][]


[Working with vCard metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+vCard+metadata
## Methods

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Gets the content type of record. |
| [getValue()](#getValue--) | Gets the record value. |
### getContentType() {#getContentType--}
```
public VCardContentType getContentType()
```


Gets the content type of record.

**Returns:**
[VCardContentType](../../com.groupdocs.metadata.core/vcardcontenttype) - The content type of record.
### getValue() {#getValue--}
```
public final byte[] getValue()
```


Gets the record value.

**Returns:**
byte[] - The record value.
