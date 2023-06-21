---
title: DngPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents native DNG metadata.
type: docs
weight: 78
url: /java/com.groupdocs.metadata.core/dngpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class DngPackage extends CustomPackage
```

Represents native DNG metadata.

**Learn more**

 *  [Working with DNG metadata][]


[Working with DNG metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+DNG+metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [DngPackage()](#DngPackage--) | Initializes a new instance of the  Metadata  class. |
## Methods

| Method | Description |
| --- | --- |
| [getCameraManufacturer()](#getCameraManufacturer--) | Gets the camera manufacturer. |
| [getColorsCount()](#getColorsCount--) | Gets the colors. |
| [getDescription()](#getDescription--) | Gets the description of colors (RGBG,RGBE,GMCY, or GBTG). |
| [getDngVersion()](#getDngVersion--) | Gets the DNG version. |
| [getFilters()](#getFilters--) | Gets the Bit mask describing the order of color pixels in the matrix. |
| [isFoveon()](#isFoveon--) | Gets the is foveon matrix. |
| [getModel()](#getModel--) | Gets the camera model. |
| [getRawCount()](#getRawCount--) | Gets the number of RAW images in file (0 means that the file has not been recognized). |
| [getSoftware()](#getSoftware--) | Gets the software. |
| [getTranslationCfaDng()](#getTranslationCfaDng--) | Gets the translation array for CFA mosaic DNG format. |
| [getAperture()](#getAperture--) | Gets the aperture. |
| [getArtist()](#getArtist--) | Gets the author of image. |
| [getFocalLength()](#getFocalLength--) | Gets the length of the focal. |
| [getGpsData()](#getGpsData--) | Gets the GPS data. |
| [getIsoSpeed()](#getIsoSpeed--) | Gets the ISO sensitivity. |
| [getShotOrder()](#getShotOrder--) | Gets serial number of image. |
| [getShutterSpeed()](#getShutterSpeed--) | Gets the shutter speed. |
| [getTimestamp()](#getTimestamp--) | Gets the date of shooting. |
### DngPackage() {#DngPackage--}
```
public DngPackage()
```


Initializes a new instance of the  Metadata  class.

### getCameraManufacturer() {#getCameraManufacturer--}
```
public final String getCameraManufacturer()
```


Gets the camera manufacturer.

**Returns:**
java.lang.String - The make.
### getColorsCount() {#getColorsCount--}
```
public final int getColorsCount()
```


Gets the colors.

**Returns:**
int - The colors.
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Gets the description of colors (RGBG,RGBE,GMCY, or GBTG).

**Returns:**
java.lang.String - The cdesc.
### getDngVersion() {#getDngVersion--}
```
public final long getDngVersion()
```


Gets the DNG version.

**Returns:**
long - The DNG version.
### getFilters() {#getFilters--}
```
public final long getFilters()
```


Gets the Bit mask describing the order of color pixels in the matrix.

**Returns:**
long - The filters.
### isFoveon() {#isFoveon--}
```
public final long isFoveon()
```


Gets the is foveon matrix.

**Returns:**
long - The is foveon.
### getModel() {#getModel--}
```
public final String getModel()
```


Gets the camera model.

**Returns:**
java.lang.String - The model.
### getRawCount() {#getRawCount--}
```
public final long getRawCount()
```


Gets the number of RAW images in file (0 means that the file has not been recognized).

**Returns:**
long - The raw count.
### getSoftware() {#getSoftware--}
```
public final String getSoftware()
```


Gets the software.

**Returns:**
java.lang.String - The software.
### getTranslationCfaDng() {#getTranslationCfaDng--}
```
public final String[] getTranslationCfaDng()
```


Gets the translation array for CFA mosaic DNG format.

**Returns:**
java.lang.String[] - The xtrans.
### getAperture() {#getAperture--}
```
public final float getAperture()
```


Gets the aperture.

**Returns:**
float - The aperture.
### getArtist() {#getArtist--}
```
public final String getArtist()
```


Gets the author of image.

**Returns:**
java.lang.String - The artist.
### getFocalLength() {#getFocalLength--}
```
public final float getFocalLength()
```


Gets the length of the focal.

**Returns:**
float - The length of the focal.
### getGpsData() {#getGpsData--}
```
public final long[] getGpsData()
```


Gets the GPS data.

**Returns:**
long[] - The GPS data.
### getIsoSpeed() {#getIsoSpeed--}
```
public final float getIsoSpeed()
```


Gets the ISO sensitivity.

**Returns:**
float - The ISO speed.
### getShotOrder() {#getShotOrder--}
```
public final long getShotOrder()
```


Gets serial number of image.

**Returns:**
long - The shot order.
### getShutterSpeed() {#getShutterSpeed--}
```
public final float getShutterSpeed()
```


Gets the shutter speed.

**Returns:**
float - The shutter.
### getTimestamp() {#getTimestamp--}
```
public final long getTimestamp()
```


Gets the date of shooting.

**Returns:**
long - The timestamp.
