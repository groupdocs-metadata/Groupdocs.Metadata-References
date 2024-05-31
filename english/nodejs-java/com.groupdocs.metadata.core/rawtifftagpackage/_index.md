---
title: RawTiffTagPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents Tiff tags.
type: docs
weight: 221
url: /nodejs-java/com.groupdocs.metadata.core/rawtifftagpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.RawDictionaryBasePackage](../../com.groupdocs.metadata.core/rawdictionarybasepackage)
```
public final class RawTiffTagPackage extends RawDictionaryBasePackage
```

Represents Tiff tags.
## Methods

| Method | Description |
| --- | --- |
| [getRawIFD1Package()](#getRawIFD1Package--) | Gets the IFD1. |
| [getRawIFD2Package()](#getRawIFD2Package--) | Gets the IFD2. |
| [getRawIFD3Package()](#getRawIFD3Package--) | Gets the IFD3. |
| [getRawExifTagPackage()](#getRawExifTagPackage--) | Gets the Exif tag (Exif IFD Pointer). |
| [getGpsIfdPackage()](#getGpsIfdPackage--) | Gets the GPS tag (GPSInfo IFD Pointer). |
| [getImageWidth()](#getImageWidth--) | Gets the image width. |
| [getImageHeight()](#getImageHeight--) | Gets the image height. |
| [getBitsPerSample()](#getBitsPerSample--) | Gets the bits per sample. |
| [getCompression()](#getCompression--) | Gets compression. |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | Gets PhotometricInterpretation. |
| [getImageDescription()](#getImageDescription--) | Gets a character string giving the title of the image. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Sets a character string giving the title of the image. |
| [getMake()](#getMake--) | Gets the macro mode. |
| [getModel()](#getModel--) | Gets the model. |
| [getStripOffset()](#getStripOffset--) | Gets the StripOffset. |
| [getOrientation()](#getOrientation--) | Gets the orientation. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Gets the SamplesPerPixel. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Gets the RowsPerStrip. |
| [getStripByteCounts()](#getStripByteCounts--) | Gets the strip byte counts. |
| [getXResolution()](#getXResolution--) | Gets the XResolution. |
| [getYResolution()](#getYResolution--) | Gets the YResolution. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Gets the PlanarConfiguration. |
| [getResolutionUnit()](#getResolutionUnit--) | Gets the Resolution Unit. |
| [getTransferFunction()](#getTransferFunction--) | Gets the TransferFunction. |
| [getSoftware()](#getSoftware--) | Gets the Software. |
| [getDateTime()](#getDateTime--) | Gets the DateTime. |
| [getArtist()](#getArtist--) | Gets the Artist. |
| [getWhitePoint()](#getWhitePoint--) | Gets the WhitePoint. |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | Gets the PrimaryChromaticities. |
| [getJpegInterchangeFormat()](#getJpegInterchangeFormat--) | Gets the JpegInterchangeFormat. |
| [getJpegInterchangeFormatLength()](#getJpegInterchangeFormatLength--) | Gets the JpegInterchangeFormatLength. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Gets the YCbCrCoefficients. |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | Gets the YCbCrSubSampling. |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | Gets the YCbCrPositioning. |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | Gets the ReferenceBlackWhite. |
| [getCopyright()](#getCopyright--) | Gets the Copyright. |
| [getEXIF()](#getEXIF--) | Gets the EXIF. |
| [getGpsIfd()](#getGpsIfd--) | Gets the EXIF. |
### getRawIFD1Package() {#getRawIFD1Package--}
```
public final RawIFD1Package getRawIFD1Package()
```


Gets the IFD1.

**Returns:**
[RawIFD1Package](../../com.groupdocs.metadata.core/rawifd1package) - The IFD1.
### getRawIFD2Package() {#getRawIFD2Package--}
```
public final RawIFD2Package getRawIFD2Package()
```


Gets the IFD2.

**Returns:**
[RawIFD2Package](../../com.groupdocs.metadata.core/rawifd2package) - The IFD2.
### getRawIFD3Package() {#getRawIFD3Package--}
```
public final RawIFD3Package getRawIFD3Package()
```


Gets the IFD3.

**Returns:**
[RawIFD3Package](../../com.groupdocs.metadata.core/rawifd3package) - The IFD3.
### getRawExifTagPackage() {#getRawExifTagPackage--}
```
public final RawExifTagPackage getRawExifTagPackage()
```


Gets the Exif tag (Exif IFD Pointer).

**Returns:**
[RawExifTagPackage](../../com.groupdocs.metadata.core/rawexiftagpackage) - The Exif tag (Exif IFD Pointer).
### getGpsIfdPackage() {#getGpsIfdPackage--}
```
public final GpsIfdPackage getGpsIfdPackage()
```


Gets the GPS tag (GPSInfo IFD Pointer).

**Returns:**
[GpsIfdPackage](../../com.groupdocs.metadata.core/gpsifdpackage) - The GPS tag (GPSInfo IFD Pointer).
### getImageWidth() {#getImageWidth--}
```
public final int getImageWidth()
```


Gets the image width.

**Returns:**
int - The image width.
### getImageHeight() {#getImageHeight--}
```
public final int getImageHeight()
```


Gets the image height.

**Returns:**
int - The image height.
### getBitsPerSample() {#getBitsPerSample--}
```
public final int[] getBitsPerSample()
```


Gets the bits per sample.

**Returns:**
int[] - The bits per sample.
### getCompression() {#getCompression--}
```
public final int getCompression()
```


Gets compression.

**Returns:**
int - The compression.
### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public final int getPhotometricInterpretation()
```


Gets PhotometricInterpretation.

**Returns:**
int - The PhotometricInterpretation.
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

### getMake() {#getMake--}
```
public final String getMake()
```


Gets the macro mode.

**Returns:**
java.lang.String - The macro mode.
### getModel() {#getModel--}
```
public final String getModel()
```


Gets the model.

**Returns:**
java.lang.String - The model.
### getStripOffset() {#getStripOffset--}
```
public final long getStripOffset()
```


Gets the StripOffset.

**Returns:**
long - The StripOffset.
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


Gets the orientation.

**Returns:**
int - The orientation.
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public final int getSamplesPerPixel()
```


Gets the SamplesPerPixel.

**Returns:**
int - The SamplesPerPixel.
### getRowsPerStrip() {#getRowsPerStrip--}
```
public final long getRowsPerStrip()
```


Gets the RowsPerStrip.

**Returns:**
long - The RowsPerStrip.
### getStripByteCounts() {#getStripByteCounts--}
```
public final long getStripByteCounts()
```


Gets the strip byte counts.

**Returns:**
long - The strip byte counts.
### getXResolution() {#getXResolution--}
```
public final float getXResolution()
```


Gets the XResolution.

**Returns:**
float - The XResolution.
### getYResolution() {#getYResolution--}
```
public final float getYResolution()
```


Gets the YResolution.

**Returns:**
float - The YResolution.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public final int getPlanarConfiguration()
```


Gets the PlanarConfiguration.

**Returns:**
int - The PlanarConfiguration.
### getResolutionUnit() {#getResolutionUnit--}
```
public final int getResolutionUnit()
```


Gets the Resolution Unit.

**Returns:**
int - The Resolution Unit.
### getTransferFunction() {#getTransferFunction--}
```
public final int[] getTransferFunction()
```


Gets the TransferFunction.

**Returns:**
int[] - The TransferFunction.
### getSoftware() {#getSoftware--}
```
public final String getSoftware()
```


Gets the Software.

**Returns:**
java.lang.String - The Software.
### getDateTime() {#getDateTime--}
```
public final String getDateTime()
```


Gets the DateTime.

**Returns:**
java.lang.String - The DateTime.
### getArtist() {#getArtist--}
```
public final String getArtist()
```


Gets the Artist.

**Returns:**
java.lang.String - The Artist.
### getWhitePoint() {#getWhitePoint--}
```
public final double[] getWhitePoint()
```


Gets the WhitePoint.

**Returns:**
double[] - The WhitePoint.
### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public final double[] getPrimaryChromaticities()
```


Gets the PrimaryChromaticities.

**Returns:**
double[] - The PrimaryChromaticities.
### getJpegInterchangeFormat() {#getJpegInterchangeFormat--}
```
public final long getJpegInterchangeFormat()
```


Gets the JpegInterchangeFormat.

**Returns:**
long - The JpegInterchangeFormat.
### getJpegInterchangeFormatLength() {#getJpegInterchangeFormatLength--}
```
public final long getJpegInterchangeFormatLength()
```


Gets the JpegInterchangeFormatLength.

**Returns:**
long - The JpegInterchangeFormatLength.
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public final double[] getYCbCrCoefficients()
```


Gets the YCbCrCoefficients.

**Returns:**
double[] - The YCbCrCoefficients.
### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public final int[] getYCbCrSubSampling()
```


Gets the YCbCrSubSampling.

**Returns:**
int[] - The YCbCrSubSampling.
### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public final int getYCbCrPositioning()
```


Gets the YCbCrPositioning.

**Returns:**
int - The YCbCrPositioning.
### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public final double[] getReferenceBlackWhite()
```


Gets the ReferenceBlackWhite.

**Returns:**
double[] - The ReferenceBlackWhite.
### getCopyright() {#getCopyright--}
```
public final String getCopyright()
```


Gets the Copyright.

**Returns:**
java.lang.String - The Copyright.
### getEXIF() {#getEXIF--}
```
public final long getEXIF()
```


Gets the EXIF.

**Returns:**
long - The EXIF.
### getGpsIfd() {#getGpsIfd--}
```
public final long getGpsIfd()
```


Gets the EXIF.

**Returns:**
long - The EXIF.
