---
title: JpegRootPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents the root package allowing working with metadata in a JPEG image.
type: docs
weight: 141
url: /nodejs-java/com.groupdocs.metadata.core/jpegrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage), [com.groupdocs.metadata.core.ImageRootPackage](../../com.groupdocs.metadata.core/imagerootpackage)

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IXmp](../../com.groupdocs.metadata.core/ixmp), [com.groupdocs.metadata.core.IExif](../../com.groupdocs.metadata.core/iexif), [com.groupdocs.metadata.core.IIptc](../../com.groupdocs.metadata.core/iiptc)
```
public class JpegRootPackage extends ImageRootPackage implements IXmp, IExif, IIptc
```

Represents the root package allowing working with metadata in a JPEG image.

**Learn more**

 *  [Working with metadata in JPEG images][]
 *  [Working with EXIF metadata][]
 *  [Working with XMP metadata][]
 *  [Working with IPTC IIM metadata][]


[Working with metadata in JPEG images]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+JPEG+images
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
| [getMakerNotePackage()](#getMakerNotePackage--) | Gets the MakerNote metadata package. |
| [removeImageResourcePackage()](#removeImageResourcePackage--) | Removes Photoshop Image Resource metadata package. |
| [detectBarcodeTypes()](#detectBarcodeTypes--) | Extracts the types of the barcodes presented in the image. |
| [sanitize()](#sanitize--) | Removes writable metadata properties from the package. |
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
### getMakerNotePackage() {#getMakerNotePackage--}
```
public final MakerNotePackage getMakerNotePackage()
```


Gets the MakerNote metadata package.

**Returns:**
[MakerNotePackage](../../com.groupdocs.metadata.core/makernotepackage) - The MakerNote metadata package.
### removeImageResourcePackage() {#removeImageResourcePackage--}
```
public final void removeImageResourcePackage()
```


Removes Photoshop Image Resource metadata package.

### detectBarcodeTypes() {#detectBarcodeTypes--}
```
public final String[] detectBarcodeTypes()
```


Extracts the types of the barcodes presented in the image.

**Returns:**
java.lang.String[] - An array of barcode types.
### sanitize() {#sanitize--}
```
public int sanitize()
```


Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well.

**Returns:**
int - The number of affected properties.
