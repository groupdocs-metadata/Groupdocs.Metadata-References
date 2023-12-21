---
title: PsdRootPackage
second_title: GroupDocs.Signature for Java API Reference
description: Represents the root package allowing working with metadata in a Photoshop Document.
type: docs
weight: 211
url: /java/com.groupdocs.metadata.core/psdrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage), [com.groupdocs.metadata.core.ImageRootPackage](../../com.groupdocs.metadata.core/imagerootpackage)

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IXmp](../../com.groupdocs.metadata.core/ixmp), [com.groupdocs.metadata.core.IIptc](../../com.groupdocs.metadata.core/iiptc), [com.groupdocs.metadata.core.IExif](../../com.groupdocs.metadata.core/iexif)
```
public class PsdRootPackage extends ImageRootPackage implements IXmp, IIptc, IExif
```

Represents the root package allowing working with metadata in a Photoshop Document.

**Learn more**

 *  [Working with metadata in PSD images][]
 *  [Working with EXIF metadata][]
 *  [Working with XMP metadata][]
 *  [Working with IPTC IIM metadata][]

This code sample demonstrates how to read the header of a PSD file and extract some information about the PSD layers.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.PsdWithIptc)) {
>      PsdRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getPsdPackage().getChannelCount());
>      System.out.println(root.getPsdPackage().getColorMode());
>      System.out.println(root.getPsdPackage().getCompression());
>      System.out.println(root.getPsdPackage().getPhotoshopVersion());
>      for (PsdLayer layer : root.getPsdPackage().getLayers()) {
>          System.out.println(layer.getName());
>          System.out.println(layer.getBitsPerPixel());
>          System.out.println(layer.getChannelCount());
>          System.out.println(layer.getFlags());
>          System.out.println(layer.getHeight());
>          System.out.println(layer.getWidth());
>          // ...
>      }
>      // ...
>  }
>  
> ```
> ```


[Working with metadata in PSD images]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+PSD+images
[Working with EXIF metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+EXIF+metadata
[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata
[Working with IPTC IIM metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+IPTC+IIM+metadata
## Methods

| Method | Description |
| --- | --- |
| [getXmpPackage()](#getXmpPackage--) | Gets the XMP metadata package. |
| [setXmpPackage(XmpPacketWrapper value)](#setXmpPackage-com.groupdocs.metadata.core.XmpPacketWrapper-) | Sets the XMP metadata package. |
| [getExifPackage()](#getExifPackage--) | Gets the EXIF metadata package. |
| [setExifPackage(ExifPackage value)](#setExifPackage-com.groupdocs.metadata.core.ExifPackage-) | Sets the EXIF metadata package. |
| [getIptcPackage()](#getIptcPackage--) | Gets the IPTC metadata package. |
| [setIptcPackage(IptcRecordSet value)](#setIptcPackage-com.groupdocs.metadata.core.IptcRecordSet-) | Sets the IPTC metadata package. |
| [getImageResourcePackage()](#getImageResourcePackage--) | Gets the Photoshop Image Resource metadata package. |
| [getPsdPackage()](#getPsdPackage--) | Gets the metadata package containing information about the PSD file. |
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

### getIptcPackage() {#getIptcPackage--}
```
public final IptcRecordSet getIptcPackage()
```


Gets the IPTC metadata package.

**Returns:**
[IptcRecordSet](../../com.groupdocs.metadata.core/iptcrecordset) - The IPTC metadata package.

**Learn more**

 *  [Working with IPTC IIM metadata][]


[Working with IPTC IIM metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+IPTC+IIM+metadata
### setIptcPackage(IptcRecordSet value) {#setIptcPackage-com.groupdocs.metadata.core.IptcRecordSet-}
```
public final void setIptcPackage(IptcRecordSet value)
```


Sets the IPTC metadata package.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IptcRecordSet](../../com.groupdocs.metadata.core/iptcrecordset) | The IPTC metadata package.

**Learn more**

 *  [Working with IPTC IIM metadata][]


[Working with IPTC IIM metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+IPTC+IIM+metadata |

### getImageResourcePackage() {#getImageResourcePackage--}
```
public final ImageResourcePackage getImageResourcePackage()
```


Gets the Photoshop Image Resource metadata package. Image resource blocks are the basic building unit of Photoshop native file format.

**Returns:**
[ImageResourcePackage](../../com.groupdocs.metadata.core/imageresourcepackage) - The Image Resource metadata package.
### getPsdPackage() {#getPsdPackage--}
```
public final PsdPackage getPsdPackage()
```


Gets the metadata package containing information about the PSD file.

**Returns:**
[PsdPackage](../../com.groupdocs.metadata.core/psdpackage) - The metadata package containing information about the PSD file.
