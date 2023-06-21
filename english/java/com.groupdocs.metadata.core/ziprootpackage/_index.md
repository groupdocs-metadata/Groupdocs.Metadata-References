---
title: ZipRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package allowing working with metadata in a ZIP archive.
type: docs
weight: 345
url: /java/com.groupdocs.metadata.core/ziprootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)
```
public class ZipRootPackage extends RootMetadataPackage
```

Represents the root package allowing working with metadata in a ZIP archive.

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
| [getZipPackage()](#getZipPackage--) | Gets the ZIP metadata package. |
### getZipPackage() {#getZipPackage--}
```
public final ZipPackage getZipPackage()
```


Gets the ZIP metadata package.

**Returns:**
[ZipPackage](../../com.groupdocs.metadata.core/zippackage) - The ZIP metadata package.
