---
title: MatroskaEbmlHeader
second_title: GroupDocs.Metadata for Java API Reference
description: Represents EBML header metadata in a Matroska video.
type: docs
weight: 116
url: /java/com.groupdocs.metadata.core/matroskaebmlheader/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.MatroskaBasePackage](../../com.groupdocs.metadata.core/matroskabasepackage)
```
public class MatroskaEbmlHeader extends MatroskaBasePackage
```

Represents EBML header metadata in a Matroska video.

**Learn more**

 *  [Working with metadata in Matroska (MKV) files][Working with metadata in Matroska _MKV_ files]


[Working with metadata in Matroska _MKV_ files]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Matroska+%28MKV%29+files
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) | Gets the version of the EBML Writer that has been used to create the file. |
| [getReadVersion()](#getReadVersion--) | Gets the minimum version an EBML parser needs to be compliant with to be able to read the file. |
| [getDocType()](#getDocType--) | Gets the contents of the file. |
| [getDocTypeVersion()](#getDocTypeVersion--) | Gets the version of the  DocType  writer used to create the file. |
| [getDocTypeReadVersion()](#getDocTypeReadVersion--) | Gets the minimum version number a  DocType  parser must be compliant with to read the file. |
### getVersion() {#getVersion--}
```
public final byte getVersion()
```


Gets the version of the EBML Writer that has been used to create the file.

**Returns:**
byte - The version of the EBML Writer that has been used to create the file.
### getReadVersion() {#getReadVersion--}
```
public final byte getReadVersion()
```


Gets the minimum version an EBML parser needs to be compliant with to be able to read the file.

**Returns:**
byte - The minimum version an EBML parser needs to be compliant with to be able to read the file.
### getDocType() {#getDocType--}
```
public final String getDocType()
```


Gets the contents of the file. In the case of a MATROSKA file, its value is 'matroska'.

**Returns:**
java.lang.String - The contents of the file.
### getDocTypeVersion() {#getDocTypeVersion--}
```
public final byte getDocTypeVersion()
```


Gets the version of the  DocType  writer used to create the file.

**Returns:**
byte - The version of the  DocType  writer used to create the file.
### getDocTypeReadVersion() {#getDocTypeReadVersion--}
```
public final byte getDocTypeReadVersion()
```


Gets the minimum version number a  DocType  parser must be compliant with to read the file.

**Returns:**
byte - The minimum version number a  DocType  parser must be compliant with to read the file.
