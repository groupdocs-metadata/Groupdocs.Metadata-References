---
title: SevenZipRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package allowing working with metadata in a ZIP archive.
type: docs
weight: 229
url: /java/com.groupdocs.metadata.core/sevenziprootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)
```
public class SevenZipRootPackage extends RootMetadataPackage
```

Represents the root package allowing working with metadata in a ZIP archive.

--------------------

> ```
> The following code snippet shows how to get metadata from a ZIP archive.
>  
>  Encoding encoding = Encoding.GetEncoding(866);
>  using (Metadata metadata = new Metadata(Constants.InputSevenZip))
>  {
>      var root = metadata.GetRootPackage<SevenZipRootPackage>();
>      Console.WriteLine(root.SevenZipPackage.TotalEntries);
>      foreach (var file in root.SevenZipPackage.Files)
>      {
>          Console.WriteLine(file.Name);
>          Console.WriteLine(file.CompressedSize);
>          Console.WriteLine(file.ModificationDateTime);
>          Console.WriteLine(file.UncompressedSize);
>          // Use a specific encoding for the file names
>          Console.WriteLine(encoding.GetString(file.RawName));
>      }
>  }
> ```

--------------------

 **Learn more** 

 *  
## Methods

| Method | Description |
| --- | --- |
| [getSevenZipPackage()](#getSevenZipPackage--) | Gets the ZIP metadata package. |
### getSevenZipPackage() {#getSevenZipPackage--}
```
public final SevenZipPackage getSevenZipPackage()
```


Gets the ZIP metadata package.

Value: The ZIP metadata package.

--------------------

 **Learn more** 

 *  

**Returns:**
[SevenZipPackage](../../com.groupdocs.metadata.core/sevenzippackage)
