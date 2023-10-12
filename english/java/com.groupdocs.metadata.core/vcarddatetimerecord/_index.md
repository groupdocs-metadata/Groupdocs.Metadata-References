---
title: VCardDateTimeRecord
second_title: GroupDocs.Metadata for Java API Reference
description: Represents vCard date time record metadata class.
type: docs
weight: 263
url: /java/com.groupdocs.metadata.core/vcarddatetimerecord/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.VCardBasePackage](../../com.groupdocs.metadata.core/vcardbasepackage), [com.groupdocs.metadata.core.VCardRecord](../../com.groupdocs.metadata.core/vcardrecord)

**All Implemented Interfaces:**
com.groupdocs.metadata.core.IVCardRecord
```
public class VCardDateTimeRecord extends VCardRecord implements IVCardRecord<Date>
```

Represents vCard date time record metadata class.

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
public final Date getValue()
```


Gets the record value.

**Returns:**
java.util.Date - The record value.
