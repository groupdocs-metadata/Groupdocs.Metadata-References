---
title: BmpRootPackage
second_title: GroupDocs.Signature for Java API Reference
description: Represents the root package intended to work with metadata in a BMP image.
type: docs
weight: 28
url: /java/com.groupdocs.metadata.core/bmprootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage), [com.groupdocs.metadata.core.ImageRootPackage](../../com.groupdocs.metadata.core/imagerootpackage)
```
public class BmpRootPackage extends ImageRootPackage
```

Represents the root package intended to work with metadata in a BMP image.

**Learn more**

 *  [Working with BMP metadata][]

This code sample shows how to read the header of a BMP file.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputBmp)) {
>      BmpRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getBmpHeader().getBitsPerPixel());
>      System.out.println(root.getBmpHeader().getColorsImportant());
>      System.out.println(root.getBmpHeader().getHeaderSize());
>      System.out.println(root.getBmpHeader().getImageSize());
>      System.out.println(root.getBmpHeader().getPlanes());
>  }
>  
> ```
> ```


[Working with BMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+BMP+metadata
## Methods

| Method | Description |
| --- | --- |
| [getBmpHeader()](#getBmpHeader--) | Gets the BMP header metadata package. |
### getBmpHeader() {#getBmpHeader--}
```
public final BmpHeaderPackage getBmpHeader()
```


Gets the BMP header metadata package.

**Returns:**
[BmpHeaderPackage](../../com.groupdocs.metadata.core/bmpheaderpackage) - The BMP header metadata package.
