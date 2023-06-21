---
title: IExif
second_title: GroupDocs.Metadata for Java API Reference
description: Defines base operations intended to work with EXIF metadata.
type: docs
weight: 350
url: /java/com.groupdocs.metadata.core/iexif/
---```
public interface IExif
```

Defines base operations intended to work with EXIF metadata.

**Learn more**

 *  [Working with EXIF metadata][]

This code sample demonstrates how to extract basic EXIF metadata properties.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.TiffWithExif)) {
>      IExif root = (IExif) metadata.getRootPackage();
>      if (root.getExifPackage() != null) {
>          System.out.println(root.getExifPackage().getArtist());
>          System.out.println(root.getExifPackage().getCopyright());
>          System.out.println(root.getExifPackage().getImageDescription());
>          System.out.println(root.getExifPackage().getMake());
>          System.out.println(root.getExifPackage().getModel());
>          System.out.println(root.getExifPackage().getSoftware());
>          System.out.println(root.getExifPackage().getImageWidth());
>          System.out.println(root.getExifPackage().getImageLength());
>          // ...
>          System.out.println(root.getExifPackage().getExifIfdPackage().getBodySerialNumber());
>          System.out.println(root.getExifPackage().getExifIfdPackage().getCameraOwnerName());
>          System.out.println(root.getExifPackage().getExifIfdPackage().getUserComment());
>          // ...
>          System.out.println(root.getExifPackage().getGpsPackage().getAltitude());
>          System.out.println(root.getExifPackage().getGpsPackage().getLatitudeRef());
>          System.out.println(root.getExifPackage().getGpsPackage().getLongitudeRef());
>          // ...
>      }
>  }
>  
> ```
> ```


[Working with EXIF metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+EXIF+metadata
## Methods

| Method | Description |
| --- | --- |
| [getExifPackage()](#getExifPackage--) | Gets the EXIF metadata package associated with the file. |
| [setExifPackage(ExifPackage value)](#setExifPackage-com.groupdocs.metadata.core.ExifPackage-) | Sets the EXIF metadata package associated with the file. |
### getExifPackage() {#getExifPackage--}
```
public abstract ExifPackage getExifPackage()
```


Gets the EXIF metadata package associated with the file.

**Returns:**
[ExifPackage](../../com.groupdocs.metadata.core/exifpackage) - The EXIF metadata package associated with the file.
### setExifPackage(ExifPackage value) {#setExifPackage-com.groupdocs.metadata.core.ExifPackage-}
```
public abstract void setExifPackage(ExifPackage value)
```


Sets the EXIF metadata package associated with the file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ExifPackage](../../com.groupdocs.metadata.core/exifpackage) | The EXIF metadata package associated with the file. |

