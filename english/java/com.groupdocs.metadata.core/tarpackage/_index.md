---
title: TarPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents ZIP archive metadata.
type: docs
weight: 240
url: /java/com.groupdocs.metadata.core/tarpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class TarPackage extends CustomPackage
```

Represents ZIP archive metadata.

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
>          Console.WriteLine(file.Size);
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
public final TarFile[] getFiles()
```


Gets an array of [ZipFile](../../com.groupdocs.metadata.core/zipfile) entries inside the ZIP archive.

Value: An array of [ZipFile](../../com.groupdocs.metadata.core/zipfile) entries inside the ZIP archive.

**Returns:**
com.groupdocs.metadata.core.TarFile[]
### getTotalEntries() {#getTotalEntries--}
```
public final long getTotalEntries()
```


Gets the total number of entries inside the ZIP archive.

Value: The total number of entries inside the ZIP archive.

**Returns:**
long
