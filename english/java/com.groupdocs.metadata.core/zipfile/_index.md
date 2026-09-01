---
title: ZipFile
second_title: GroupDocs.Metadata for Java API Reference
description: Represents metadata associated with an archived file or directory.
type: docs
weight: 350
url: /java/com.groupdocs.metadata.core/zipfile/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class ZipFile extends CustomPackage
```

Represents metadata associated with an archived file or directory.


**Learn more**

* [Working with ZIP archives](../https://docs.groupdocs.com/display/metadatajava/Working+with+ZIP+archives)

<br />


## Methods

| Method | Description |
| --- | --- |
| [getCompressionMethod()](#getCompressionMethod--) | Gets the compression method.
 |
| [getCompressedSize()](#getCompressedSize--) | Gets the compressed size in bytes.
 |
| [getUncompressedSize()](#getUncompressedSize--) | Gets the uncompressed size in bytes.
 |
| [getFlags()](#getFlags--) | Gets the ZIP entry flags.
 |
| [getName()](#getName--) | Gets the entry name.
 |
| [getRawName()](#getRawName--) | Gets an array of bytes representing the name of the entry.
 |
| [getModificationDateTime()](#getModificationDateTime--) | Gets the last modification date and time.
 |
### getCompressionMethod() {#getCompressionMethod--}
```
public final ZipCompressionMethod getCompressionMethod()
```


Gets the compression method.


**Returns:**
[ZipCompressionMethod](../../com.groupdocs.metadata.core/zipcompressionmethod) - The compression method.

### getCompressedSize() {#getCompressedSize--}
```
public final long getCompressedSize()
```


Gets the compressed size in bytes.


**Returns:**
long - The compressed size in bytes.

### getUncompressedSize() {#getUncompressedSize--}
```
public final long getUncompressedSize()
```


Gets the uncompressed size in bytes.


**Returns:**
long - The uncompressed size in bytes.

### getFlags() {#getFlags--}
```
public final int getFlags()
```


Gets the ZIP entry flags.


**Returns:**
int - The ZIP entry flags.

<br />

*** ** * ** ***


Bit 00: encrypted file. 

<br />



Bit 01: compression option. 

<br />



Bit 02: compression option. 

<br />



Bit 03: data descriptor. 

<br />



Bit 04: enhanced deflation. 

<br />



Bit 05: compressed patched data. 

<br />



Bit 06: strong encryption. 

<br />



Bit 07-10: unused. 

<br />



Bit 11: language encoding. 

<br />



Bit 12: reserved. 

<br />



Bit 13: mask header values. 

<br />



Bit 14-15: reserved. 

<br />




<br />


### getName() {#getName--}
```
public final String getName()
```


Gets the entry name.


**Returns:**
java.lang.String - The entry name. It can be a file or directory name.

### getRawName() {#getRawName--}
```
public final byte[] getRawName()
```


Gets an array of bytes representing the name of the entry.


**Returns:**
byte[] - An array of bytes representing the name of the entry.

### getModificationDateTime() {#getModificationDateTime--}
```
public final Date getModificationDateTime()
```


Gets the last modification date and time.


**Returns:**
java.util.Date - The last modification date and time.

