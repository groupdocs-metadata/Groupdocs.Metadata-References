---
title: ZipPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents ZIP archive metadata.
type: docs
weight: 351
url: /nodejs-java/com.groupdocs.metadata.core/zippackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class ZipPackage extends CustomPackage
```

Represents ZIP archive metadata.

**Learn more**

 *  [Working with ZIP archives][]

The following code snippet shows how to get metadata from a ZIP archive.

> ```
> ```
> 
>  Charset charset = Charset.forName("cp866");
>  try (Metadata metadata = new Metadata(Constants.InputZip)) {
>      ZipRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getZipPackage().getComment());
>      System.out.println(root.getZipPackage().getTotalEntries());
>      for (ZipFile file : root.getZipPackage().getFiles()) {
>          System.out.println(file.getName());
>          System.out.println(file.getCompressedSize());
>          System.out.println(file.getCompressionMethod());
>          System.out.println(file.getFlags());
>          System.out.println(file.getModificationDateTime());
>          System.out.println(file.getUncompressedSize());
>          // Use a specific encoding for the file names
>          System.out.println(new String(file.getRawName(), charset));
>      }
>  }
>  
> ```
> ```


[Working with ZIP archives]: https://docs.groupdocs.com/display/metadatajava/Working+with+ZIP+archives
## Methods

| Method | Description |
| --- | --- |
| [getComment()](#getComment--) | Gets the ZIP archive comment created by a user. |
| [setComment(String value)](#setComment-java.lang.String-) | Sets the ZIP archive comment created by a user. |
| [getFiles()](#getFiles--) | Gets an array of  ZipFile  entries inside the ZIP archive. |
| [getTotalEntries()](#getTotalEntries--) | Gets the total number of entries inside the ZIP archive. |
### getComment() {#getComment--}
```
public final String getComment()
```


Gets the ZIP archive comment created by a user.

**Returns:**
java.lang.String - The user's comment.
### setComment(String value) {#setComment-java.lang.String-}
```
public final void setComment(String value)
```


Sets the ZIP archive comment created by a user.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The user's comment. |

### getFiles() {#getFiles--}
```
public final ZipFile[] getFiles()
```


Gets an array of  ZipFile  entries inside the ZIP archive.

**Returns:**
com.groupdocs.metadata.core.ZipFile[] - An array of  ZipFile  entries inside the ZIP archive.
### getTotalEntries() {#getTotalEntries--}
```
public final long getTotalEntries()
```


Gets the total number of entries inside the ZIP archive.

**Returns:**
long - The total number of entries inside the ZIP archive.
