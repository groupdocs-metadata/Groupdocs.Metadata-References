---
title: SevenZipPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents ZIP archive metadata.
type: docs
weight: 228
url: /java/com.groupdocs.metadata.core/sevenzippackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class SevenZipPackage extends CustomPackage
```

Represents ZIP archive metadata.

<br />

*** ** * ** ***

> ```
>  
>   The following code snippet shows how to get metadata from a ZIP archive.
>  
>  
> ```

<br />

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## Methods

| Method | Description |
| --- | --- |
| [getFiles()](#getFiles--) | Gets an array of [ZipFile](../../com.groupdocs.metadata.core/zipfile) entries inside the ZIP archive.
 |
| [getTotalEntries()](#getTotalEntries--) | Gets the total number of entries inside the ZIP archive.
 |
### getFiles() {#getFiles--}
```
public final SevenZipFile[] getFiles()
```


Gets an array of [ZipFile](../../com.groupdocs.metadata.core/zipfile) entries inside the ZIP archive.
Value: An array of [ZipFile](../../com.groupdocs.metadata.core/zipfile) entries inside the ZIP archive.


**Returns:**
com.groupdocs.metadata.core.SevenZipFile[]
### getTotalEntries() {#getTotalEntries--}
```
public final long getTotalEntries()
```


Gets the total number of entries inside the ZIP archive.
Value: The total number of entries inside the ZIP archive.


**Returns:**
long
