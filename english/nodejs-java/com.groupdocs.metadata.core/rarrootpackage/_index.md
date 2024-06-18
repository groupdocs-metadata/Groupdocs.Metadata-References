---
title: RarRootPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents the root package allowing working with metadata in a ZIP archive.
type: docs
weight: 214
url: /nodejs-java/com.groupdocs.metadata.core/rarrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)
```
public class RarRootPackage extends RootMetadataPackage
```

Represents the root package allowing working with metadata in a ZIP archive.

--------------------

> ```
> The following code snippet shows how to get metadata from a ZIP archive.
>  
>  Encoding encoding = Encoding.GetEncoding(866);
>  using (Metadata metadata = new Metadata(Constants.InputRar))
>  {
>      var root = metadata.GetRootPackage<RarRootPackage>();
>      Console.WriteLine(root.RarPackage.TotalEntries);
>      foreach (var file in root.RarPackage.Files)
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
| [getRarPackage()](#getRarPackage--) | Gets the ZIP metadata package. |
### getRarPackage() {#getRarPackage--}
```
public final RarPackage getRarPackage()
```


Gets the ZIP metadata package.

Value: The ZIP metadata package.

--------------------

 **Learn more** 

 *  

**Returns:**
[RarPackage](../../com.groupdocs.metadata.core/rarpackage)
