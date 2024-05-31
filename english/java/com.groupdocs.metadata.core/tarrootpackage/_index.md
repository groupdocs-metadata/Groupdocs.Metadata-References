---
title: TarRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package allowing working with metadata in a ZIP archive.
type: docs
weight: 241
url: /java/com.groupdocs.metadata.core/tarrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)
```
public class TarRootPackage extends RootMetadataPackage
```

Represents the root package allowing working with metadata in a ZIP archive.

--------------------

> ```
> The following code snippet shows how to get metadata from a ZIP archive.
>  
>  Encoding encoding = Encoding.GetEncoding(866);
>  using (Metadata metadata = new Metadata(Constants.InputTar))
>  {
>      var root = metadata.GetRootPackage<TarRootPackage>();
>      Console.WriteLine(root.TarPackage.TotalEntries);
>      foreach (var file in root.TarPackage.Files)
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
| [getTarPackage()](#getTarPackage--) | Gets the ZIP metadata package. |
### getTarPackage() {#getTarPackage--}
```
public final TarPackage getTarPackage()
```


Gets the ZIP metadata package.

Value: The ZIP metadata package.

--------------------

 **Learn more** 

 *  

**Returns:**
[TarPackage](../../com.groupdocs.metadata.core/tarpackage)
