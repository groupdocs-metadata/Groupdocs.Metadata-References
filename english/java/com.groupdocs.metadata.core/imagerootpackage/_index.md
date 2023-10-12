---
title: ImageRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Provides a base abstract class for all image root packages.
type: docs
weight: 129
url: /java/com.groupdocs.metadata.core/imagerootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)
```
public abstract class ImageRootPackage extends RootMetadataPackage
```

Provides a base abstract class for all image root packages.

This code sample demonstrates how to extract common image properties such as width and height, MIME type, byte order, etc.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputPng)) {
>      ImageRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getImageType().getFileFormat());
>      System.out.println(root.getImageType().getByteOrder());
>      System.out.println(root.getImageType().getMimeType());
>      System.out.println(root.getImageType().getExtension());
>      System.out.println(root.getImageType().getWidth());
>      System.out.println(root.getImageType().getHeight());
>  }
>  
> ```
> ```
## Methods

| Method | Description |
| --- | --- |
| [getImageType()](#getImageType--) | Gets the file type metadata package. |
### getImageType() {#getImageType--}
```
public final ImageTypePackage getImageType()
```


Gets the file type metadata package.

**Returns:**
[ImageTypePackage](../../com.groupdocs.metadata.core/imagetypepackage) - The file type metadata package.
