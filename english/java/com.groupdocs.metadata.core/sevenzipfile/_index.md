---
title: SevenZipFile
second_title: GroupDocs.Metadata for Java API Reference
description: Represents metadata associated with an archived file or directory.
type: docs
weight: 227
url: /java/com.groupdocs.metadata.core/sevenzipfile/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class SevenZipFile extends CustomPackage
```

Represents metadata associated with an archived file or directory.

--------------------

 **Learn more** 

 *  
## Methods

| Method | Description |
| --- | --- |
| [getCompressedSize()](#getCompressedSize--) | Gets the compressed size in bytes. |
| [getUncompressedSize()](#getUncompressedSize--) | Gets the uncompressed size in bytes. |
| [getName()](#getName--) | Gets the entry name. |
| [getModificationDateTime()](#getModificationDateTime--) | Gets the last modification date and time. |
### getCompressedSize() {#getCompressedSize--}
```
public final long getCompressedSize()
```


Gets the compressed size in bytes.

Value: The compressed size in bytes.

**Returns:**
long
### getUncompressedSize() {#getUncompressedSize--}
```
public final long getUncompressedSize()
```


Gets the uncompressed size in bytes.

Value: The uncompressed size in bytes.

**Returns:**
long
### getName() {#getName--}
```
public final String getName()
```


Gets the entry name.

Value: The entry name. It can be a file or directory name.

**Returns:**
java.lang.String
### getModificationDateTime() {#getModificationDateTime--}
```
public final Date getModificationDateTime()
```


Gets the last modification date and time.

Value: The last modification date and time.

**Returns:**
java.util.Date
