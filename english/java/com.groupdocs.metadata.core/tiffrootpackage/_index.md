---
title: TiffRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package allowing working with metadata in a TIFF image.
type: docs
weight: 241
url: /java/com.groupdocs.metadata.core/tiffrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage), [com.groupdocs.metadata.core.ImageRootPackage](../../com.groupdocs.metadata.core/imagerootpackage)

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IXmp](../../com.groupdocs.metadata.core/ixmp), [com.groupdocs.metadata.core.IExif](../../com.groupdocs.metadata.core/iexif), [com.groupdocs.metadata.core.IIptc](../../com.groupdocs.metadata.core/iiptc)
```
public class TiffRootPackage extends ImageRootPackage implements IXmp, IExif, IIptc
```

Represents the root package allowing working with metadata in a TIFF image.

**Learn more**

 *  [Working with metadata in TIFF images][]
 *  [Working with EXIF metadata][]
 *  [Working with XMP metadata][]
 *  [Working with IPTC IIM metadata][]

This example shows how to extract basic IPTC metadata properties from a TIFF image.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.TiffWithIptc)) {
>      TiffRootPackage root = metadata.getRootPackageGeneric();
>      if (root.getIptcPackage() != null) {
>          if (root.getIptcPackage().getEnvelopeRecord() != null) {
>              System.out.println(root.getIptcPackage().getEnvelopeRecord().getDateSent());
>              System.out.println(root.getIptcPackage().getEnvelopeRecord().getDestination());
>              System.out.println(root.getIptcPackage().getEnvelopeRecord().getFileFormat());
>              System.out.println(root.getIptcPackage().getEnvelopeRecord().getFileFormatVersion());
>              // ...
>          }
>          if (root.getIptcPackage().getApplicationRecord() != null) {
>              System.out.println(root.getIptcPackage().getApplicationRecord().getHeadline());
>              System.out.println(root.getIptcPackage().getApplicationRecord().getByLine());
>              System.out.println(root.getIptcPackage().getApplicationRecord().getByLineTitle());
>              System.out.println(root.getIptcPackage().getApplicationRecord().getCaptionAbstract());
>              System.out.println(root.getIptcPackage().getApplicationRecord().getCity());
>              System.out.println(root.getIptcPackage().getApplicationRecord().getDateCreated());
>              System.out.println(root.getIptcPackage().getApplicationRecord().getReleaseDate());
>              // ...
>          }
>      }
>  }
>  
> ```
> ```


[Working with metadata in TIFF images]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+TIFF+images
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

