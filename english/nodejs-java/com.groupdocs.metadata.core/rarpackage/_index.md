---
title: RarPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents ZIP archive metadata.
type: docs
weight: 213
url: /nodejs-java/com.groupdocs.metadata.core/rarpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class RarPackage extends CustomPackage
```

Represents ZIP archive metadata.

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
| [getFiles()](#getFiles--) | Gets an array of [ZipFile](../../com.groupdocs.metadata.core/zipfile) entries inside the ZIP archive. |
| [getTotalEntries()](#getTotalEntries--) | Gets the total number of entries inside the ZIP archive. |
### getFiles() {#getFiles--}
```
public final RarFile[] getFiles()
```


Gets an array of [ZipFile](../../com.groupdocs.metadata.core/zipfile) entries inside the ZIP archive.

Value: An array of [ZipFile](../../com.groupdocs.metadata.core/zipfile) entries inside the ZIP archive.

**Returns:**
com.groupdocs.metadata.core.RarFile[]
### getTotalEntries() {#getTotalEntries--}
```
public final long getTotalEntries()
```


Gets the total number of entries inside the ZIP archive.

Value: The total number of entries inside the ZIP archive.

**Returns:**
long
