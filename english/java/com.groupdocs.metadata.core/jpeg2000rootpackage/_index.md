---
title: Jpeg2000RootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package intended to work with metadata in a JPEG2000 image.
type: docs
weight: 141
url: /java/com.groupdocs.metadata.core/jpeg2000rootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage), [com.groupdocs.metadata.core.ImageRootPackage](../../com.groupdocs.metadata.core/imagerootpackage)

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IXmp](../../com.groupdocs.metadata.core/ixmp), [com.groupdocs.metadata.core.IExif](../../com.groupdocs.metadata.core/iexif)
```
public class Jpeg2000RootPackage extends ImageRootPackage implements IXmp, IExif
```

Represents the root package intended to work with metadata in a JPEG2000 image.

**Learn more**

 *  [Working with metadata in JPEG2000 images][]
 *  [Working with XMP metadata][]

This code snippet demonstrates how to read JPEG2000 image comments.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputJpeg2000)) {
>      Jpeg2000RootPackage root = metadata.getRootPackageGeneric();
>      if (root.getJpeg2000Package().getComments() != null) {
>          for (String comment : root.getJpeg2000Package().getComments()) {
>              System.out.println(comment);
>          }
>      }
>  }
>  
> ```
> ```


[Working with metadata in JPEG2000 images]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+JPEG2000+images
[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata
## Methods

| Method | Description |
| --- | --- |
| [getXmpPackage()](#getXmpPackage--) | Gets the XMP metadata package. |
| [setXmpPackage(XmpPacketWrapper value)](#setXmpPackage-com.groupdocs.metadata.core.XmpPacketWrapper-) | Sets the XMP metadata package. |
| [getExifPackage()](#getExifPackage--) | Gets the EXIF metadata package. |
| [setExifPackage(ExifPackage value)](#setExifPackage-com.groupdocs.metadata.core.ExifPackage-) | Sets the EXIF metadata package. |
| [getJpeg2000Package()](#getJpeg2000Package--) | Gets the JPEG2000 native metadata package. |
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

### getExifPackage() {#getExifPackage--}
```
public final ExifPackage getExifPackage()
```


Gets the EXIF metadata package.

**Returns:**
[ExifPackage](../../com.groupdocs.metadata.core/exifpackage) - The EXIF metadata package.

**Learn more**

 *  [Working with EXIF metadata][]


[Working with EXIF metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+EXIF+metadata
### setExifPackage(ExifPackage value) {#setExifPackage-com.groupdocs.metadata.core.ExifPackage-}
```
public final void setExifPackage(ExifPackage value)
```


Sets the EXIF metadata package.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ExifPackage](../../com.groupdocs.metadata.core/exifpackage) | The EXIF metadata package.

**Learn more**

 *  [Working with EXIF metadata][]


[Working with EXIF metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+EXIF+metadata |

### getJpeg2000Package() {#getJpeg2000Package--}
```
public final Jpeg2000Package getJpeg2000Package()
```


Gets the JPEG2000 native metadata package.

**Returns:**
[Jpeg2000Package](../../com.groupdocs.metadata.core/jpeg2000package) - The JPEG2000 native metadata package.
