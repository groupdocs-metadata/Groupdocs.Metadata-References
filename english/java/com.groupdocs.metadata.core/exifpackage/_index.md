---
title: ExifPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents an EXIF metadata package Exchangeable Image File Format.
type: docs
weight: 99
url: /java/com.groupdocs.metadata.core/exifpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.ExifDictionaryBasePackage](../../com.groupdocs.metadata.core/exifdictionarybasepackage)
```
public class ExifPackage extends ExifDictionaryBasePackage
```

Represents an EXIF metadata package (Exchangeable Image File Format).

**Learn more**

 *  [Working with EXIF metadata][]

This code sample demonstrates how to update common EXIF properties.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputJpeg)) {
>      IExif root = (IExif) metadata.getRootPackage();
>      // Set the EXIF package if it's missing
>      if (root.getExifPackage() == null) {
>          root.setExifPackage(new ExifPackage());
>      }
>      root.getExifPackage().setCopyright("Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.");
>      root.getExifPackage().setImageDescription("test image");
>      root.getExifPackage().setSoftware("GroupDocs.Metadata");
>      // ...
>      root.getExifPackage().getExifIfdPackage().setBodySerialNumber("test");
>      root.getExifPackage().getExifIfdPackage().setCameraOwnerName("GroupDocs");
>      root.getExifPackage().getExifIfdPackage().setUserComment("test comment");
>      // ...
>      metadata.save(Constants.OutputJpeg);
>  }
>  
> ```
> ```


[Working with EXIF metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+EXIF+metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [ExifPackage()](#ExifPackage--) | Initializes a new instance of the  ExifPackage  class. |
## Methods

| Method | Description |
| --- | --- |
| [getGpsPackage()](#getGpsPackage--) | Gets the GPS data. |
| [getExifIfdPackage()](#getExifIfdPackage--) | Gets the EXIF IFD data. |
| [getThumbnail()](#getThumbnail--) | Gets the image thumbnail represented as an array of bytes. |
| [getArtist()](#getArtist--) | Gets the name of the camera owner, photographer or image creator. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Sets the name of the camera owner, photographer or image creator. |
| [getCopyright()](#getCopyright--) | Gets the copyright notice. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Sets the copyright notice. |
| [getDateTime()](#getDateTime--) | Gets the date and time of image creation. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Sets the date and time of image creation. |
| [getImageDescription()](#getImageDescription--) | Gets a character string giving the title of the image. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Sets a character string giving the title of the image. |
| [getImageLength()](#getImageLength--) | Gets the number of rows of image data. |
| [setImageLength(int value)](#setImageLength-int-) | Sets the number of rows of image data. |
| [getImageWidth()](#getImageWidth--) | Gets the number of columns of image data, equal to the number of pixels per row. |
| [setImageWidth(int value)](#setImageWidth-int-) | Sets the number of columns of image data, equal to the number of pixels per row. |
| [getOrientation()](#getOrientation--) | Gets or sets the orientation. |
| [setOrientation(int value)](#setOrientation-int-) | Gets or sets the orientation. |
| [getMake()](#getMake--) | Gets the manufacturer of the recording equipment. |
| [setMake(String value)](#setMake-java.lang.String-) | Sets the manufacturer of the recording equipment. |
| [getModel()](#getModel--) | Gets the model name or model number of the equipment. |
| [setModel(String value)](#setModel-java.lang.String-) | Sets the model name or model number of the equipment. |
| [getSoftware()](#getSoftware--) | Gets the name and version of the software or firmware of the camera or image input device used to generate the image. |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | Sets the name and version of the software or firmware of the camera or image input device used to generate the image. |
### ExifPackage() {#ExifPackage--}
```
public ExifPackage()
```


Initializes a new instance of the  ExifPackage  class.

### getGpsPackage() {#getGpsPackage--}
```
public final ExifGpsPackage getGpsPackage()
```


Gets the GPS data.

**Returns:**
[ExifGpsPackage](../../com.groupdocs.metadata.core/exifgpspackage) - The GPS data.
### getExifIfdPackage() {#getExifIfdPackage--}
```
public final ExifIfdPackage getExifIfdPackage()
```


Gets the EXIF IFD data.

**Returns:**
[ExifIfdPackage](../../com.groupdocs.metadata.core/exififdpackage) - The EXIF IFD data.
### getThumbnail() {#getThumbnail--}
```
public final byte[] getThumbnail()
```


Gets the image thumbnail represented as an array of bytes.

**Returns:**
byte[] - The image thumbnail represented as an array of bytes.

--------------------

This feature is not available in trial mode.
### getArtist() {#getArtist--}
```
public final String getArtist()
```


Gets the name of the camera owner, photographer or image creator.

**Returns:**
java.lang.String - The name of the camera owner, photographer or image creator.
### setArtist(String value) {#setArtist-java.lang.String-}
```
public final void setArtist(String value)
```


Sets the name of the camera owner, photographer or image creator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the camera owner, photographer or image creator. |

### getCopyright() {#getCopyright--}
```
public final String getCopyright()
```


Gets the copyright notice.

**Returns:**
java.lang.String - The copyright notice.
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public final void setCopyright(String value)
```


Sets the copyright notice.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The copyright notice. |

### getDateTime() {#getDateTime--}
```
public final String getDateTime()
```


Gets the date and time of image creation. In the EXIF standard, it is the date and time the file was changed.

**Returns:**
java.lang.String - The date and time of image creation.
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public final void setDateTime(String value)
```


Sets the date and time of image creation. In the EXIF standard, it is the date and time the file was changed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The date and time of image creation. |

### getImageDescription() {#getImageDescription--}
```
public final String getImageDescription()
```


Gets a character string giving the title of the image. It may be a comment such as "1988 company picnic" or the like.

**Returns:**
java.lang.String - The image description.
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public final void setImageDescription(String value)
```


Sets a character string giving the title of the image. It may be a comment such as "1988 company picnic" or the like.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The image description. |

### getImageLength() {#getImageLength--}
```
public final int getImageLength()
```


Gets the number of rows of image data.

**Returns:**
int - The number of rows of image data.
### setImageLength(int value) {#setImageLength-int-}
```
public final void setImageLength(int value)
```


Sets the number of rows of image data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The number of rows of image data. |

### getImageWidth() {#getImageWidth--}
```
public final int getImageWidth()
```


Gets the number of columns of image data, equal to the number of pixels per row.

**Returns:**
int - The number of columns of image data, equal to the number of pixels per row.
### setImageWidth(int value) {#setImageWidth-int-}
```
public final void setImageWidth(int value)
```


Sets the number of columns of image data, equal to the number of pixels per row.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The number of columns of image data, equal to the number of pixels per row. |

### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


Gets or sets the orientation.

Value: The orientation.

**Returns:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


Gets or sets the orientation.

Value: The orientation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMake() {#getMake--}
```
public final String getMake()
```


Gets the manufacturer of the recording equipment. This is the manufacturer of the DSC, scanner, video digitizer or other equipment that generated the image.

**Returns:**
java.lang.String - The manufacturer of the recording equipment.
### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Sets the manufacturer of the recording equipment. This is the manufacturer of the DSC, scanner, video digitizer or other equipment that generated the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The manufacturer of the recording equipment. |

### getModel() {#getModel--}
```
public final String getModel()
```


Gets the model name or model number of the equipment. This is the model name or number of the DSC, scanner, video digitizer or other equipment that generated the image.

**Returns:**
java.lang.String - The model name or model number of the equipment.
### setModel(String value) {#setModel-java.lang.String-}
```
public final void setModel(String value)
```


Sets the model name or model number of the equipment. This is the model name or number of the DSC, scanner, video digitizer or other equipment that generated the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The model name or model number of the equipment. |

### getSoftware() {#getSoftware--}
```
public final String getSoftware()
```


Gets the name and version of the software or firmware of the camera or image input device used to generate the image.

**Returns:**
java.lang.String - The name and version of the software or firmware of the camera or image input device used to generate the image.
### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public final void setSoftware(String value)
```


Sets the name and version of the software or firmware of the camera or image input device used to generate the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name and version of the software or firmware of the camera or image input device used to generate the image. |

