---
title: GifRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package intended to work with metadata in a GIF image.
type: docs
weight: 74
url: /java/com.groupdocs.metadata.core/gifrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage), [com.groupdocs.metadata.core.ImageRootPackage](../../com.groupdocs.metadata.core/imagerootpackage)

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IXmp](../../com.groupdocs.metadata.core/ixmp)
```
public class GifRootPackage extends ImageRootPackage implements IXmp
```

Represents the root package intended to work with metadata in a GIF image.

**Learn more**

 *  [Working with metadata in GIF images][]
 *  [Working with XMP metadata][]

This code snippet shows how to detect the version of a loaded GIF image and extract some additional file format information.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputGif)) {
>      GifRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getGifImageType().getFileFormat());
>      System.out.println(root.getGifImageType().getVersion());
>      System.out.println(root.getGifImageType().getByteOrder());
>      System.out.println(root.getGifImageType().getMimeType());
>      System.out.println(root.getGifImageType().getExtension());
>      System.out.println(root.getGifImageType().getWidth());
>      System.out.println(root.getGifImageType().getHeight());
>  }
>  
> ```
> ```


[Working with metadata in GIF images]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+GIF+images
[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata
## Methods

| Method | Description |
| --- | --- |
| [getGifImageType()](#getGifImageType--) | Gets the file type metadata package. |
| [getXmpPackage()](#getXmpPackage--) | Gets the XMP metadata package. |
| [setXmpPackage(XmpPacketWrapper value)](#setXmpPackage-com.groupdocs.metadata.core.XmpPacketWrapper-) | Sets the XMP metadata package. |
| [isXmpSupported()](#isXmpSupported--) | Gets a value indicating whether the XMP metadata is supported for this image. |
### getGifImageType() {#getGifImageType--}
```
public final GifImageTypePackage getGifImageType()
```


Gets the file type metadata package.

**Returns:**
[GifImageTypePackage](../../com.groupdocs.metadata.core/gifimagetypepackage) - The file type metadata package.
### getXmpPackage() {#getXmpPackage--}
```
public final XmpPacketWrapper getXmpPackage()
```


Gets the XMP metadata package.

**Returns:**
[XmpPacketWrapper](../../com.groupdocs.metadata.core/xmppacketwrapper) - The XMP metadata package.

**Learn more**

 *  [Working with XMP metadata][]


[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata
### setXmpPackage(XmpPacketWrapper value) {#setXmpPackage-com.groupdocs.metadata.core.XmpPacketWrapper-}
```
public final void setXmpPackage(XmpPacketWrapper value)
```


Sets the XMP metadata package.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.groupdocs.metadata.core/xmppacketwrapper) | The XMP metadata package.

**Learn more**

 *  [Working with XMP metadata][]


[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata |

### isXmpSupported() {#isXmpSupported--}
```
public final boolean isXmpSupported()
```


Gets a value indicating whether the XMP metadata is supported for this image.

**Returns:**
boolean - True if the XMP metadata is supported for this image; otherwise, false.
