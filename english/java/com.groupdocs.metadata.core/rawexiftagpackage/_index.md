---
title: RawExifTagPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents Exif tags.
type: docs
weight: 215
url: /java/com.groupdocs.metadata.core/rawexiftagpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.RawDictionaryBasePackage](../../com.groupdocs.metadata.core/rawdictionarybasepackage)
```
public abstract class RawExifTagPackage extends RawDictionaryBasePackage
```

Represents Exif tags.
## Methods

| Method | Description |
| --- | --- |
| [getRawMakerNotePackage()](#getRawMakerNotePackage--) | Gets the Manufacturer notes (MakerNote). |
| [getInteroperabilityIFDPointerPackage()](#getInteroperabilityIFDPointerPackage--) | Gets the Interoperability tag (Interoperability IFD Pointer). |
| [getInteroperabilityIFDPointer()](#getInteroperabilityIFDPointer--) | Gets the Interoperability tag (Interoperability IFD Pointer). |
| [getExposureTime()](#getExposureTime--) | Gets the Exposure time. |
| [getFNumber()](#getFNumber--) | Gets the F number. |
| [getExposureProgram()](#getExposureProgram--) | Gets the Exposure program. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Gets the Spectral sensitivity. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Gets the Photographic Sensitivity. |
| [getOECF()](#getOECF--) | Gets the Optoelectric conversion factor. |
| [getSensitivityType()](#getSensitivityType--) | Gets the Sensitivity Type. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Gets the Standard Output Sensitivity. |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Gets the Recommended ExposureIndexs. |
| [getISOSpeed()](#getISOSpeed--) | Gets the ISO Speed. |
| [getISOSpeedLatitudeyyy()](#getISOSpeedLatitudeyyy--) | Gets the ISO Speed Latitude yyy. |
| [getISOSpeedLatitudezzz()](#getISOSpeedLatitudezzz--) | Gets the ISO Speed Latitude zzz. |
| [getExifVersion()](#getExifVersion--) | Gets the ExifVersion. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Gets the Date and time of original data generation. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Gets the Date and time of digital data generation. |
| [getOffsetTime()](#getOffsetTime--) | Gets the Offset data of DateTime. |
| [getOffsetTimeOriginal()](#getOffsetTimeOriginal--) | Gets the Offset data of DateTimeOriginal. |
| [getOffsetTimeDigitized()](#getOffsetTimeDigitized--) | Gets the Offset data of DateTimeDigitized. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Gets the Meaning of each component. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Gets the Shutter speed. |
| [getApertureValue()](#getApertureValue--) | Gets the Aperture. |
| [getBrightnessValue()](#getBrightnessValue--) | Gets the Brightness. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Gets the Exposure bias. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Gets the Maximum lens aperture. |
| [getSubjectDistance()](#getSubjectDistance--) | Gets the Subject distance. |
| [getMeteringMode()](#getMeteringMode--) | Gets the Metering mode. |
| [getLightSource()](#getLightSource--) | Gets the Light source. |
| [getFlash()](#getFlash--) | Gets the Flash. |
| [getFocalLength()](#getFocalLength--) | Gets the Lens focal length. |
| [getSubjectArea()](#getSubjectArea--) | Gets the Subject area. |
| [getUserComment()](#getUserComment--) | Gets the User comments. |
| [getSubSecTime()](#getSubSecTime--) | Gets the DateTime subseconds. |
| [getSubSecTimeOriginal()](#getSubSecTimeOriginal--) | Gets the DateTimeOriginal subseconds. |
| [getSubSecTimeDigitized()](#getSubSecTimeDigitized--) | Gets the DateTimeDigitized subseconds. |
| [getTemperature()](#getTemperature--) | Gets the Temperature. |
| [getHumidity()](#getHumidity--) | Gets the Humidity. |
| [getPressure()](#getPressure--) | Gets the Pressure. |
| [getWaterDepth()](#getWaterDepth--) | Gets the WaterDepth. |
| [getAcceleration()](#getAcceleration--) | Gets the Acceleration. |
| [getCameraElevationAngle()](#getCameraElevationAngle--) | Gets the Camera elevation angle. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Gets the Temperature. |
| [getColorSpace()](#getColorSpace--) | Gets the Color space information . |
| [getPixelXDimension()](#getPixelXDimension--) | Gets the Valid image width. |
| [getPixelYDimension()](#getPixelYDimension--) | Gets the Valid image height. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | Gets the Related audio file. |
| [getFlashEnergy()](#getFlashEnergy--) | Gets the Flash energy. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Gets the Spatial frequency response. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Gets Focal plane X resolution. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Gets the Focal plane Y resolution. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Gets the Focal plane resolution unit. |
| [getSubjectLocation()](#getSubjectLocation--) | Gets the Subject location. |
| [getExposureIndex()](#getExposureIndex--) | Gets the Exposure index. |
| [getSensingMethod()](#getSensingMethod--) | Gets the Sensing method. |
| [getFileSource()](#getFileSource--) | Gets the File source. |
| [getSceneType()](#getSceneType--) | Gets the Scene Type. |
| [getCFAPattern()](#getCFAPattern--) | Gets the CFA pattern. |
| [getCustomRendered()](#getCustomRendered--) | Gets the Custom image processing. |
| [getExposureMode()](#getExposureMode--) | Gets the Exposure mode. |
| [getWhiteBalance()](#getWhiteBalance--) | Gets the White balance. |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Gets the Digital zoom ratio. |
| [getFocalLengthIn35mmFilm()](#getFocalLengthIn35mmFilm--) | Gets the Focal length in 35 mm film. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Gets the Scene capture type. |
| [getGainControl()](#getGainControl--) | Gets the Gain control. |
| [getContrast()](#getContrast--) | Gets the Contrast. |
| [getSaturation()](#getSaturation--) | Gets the Saturation. |
| [getSharpness()](#getSharpness--) | Gets the Sharpness. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Gets the Device settings description. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Gets the Subject distance range. |
| [getImageUniqueID()](#getImageUniqueID--) | Gets the Unique image ID. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Gets the Camera Owner Name. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Gets the Body Serial Number. |
| [getLensSpecification()](#getLensSpecification--) | Gets the Lens Specification. |
| [getLensModel()](#getLensModel--) | Gets the Lens Model. |
| [getLensMake()](#getLensMake--) | Gets the Lens Make. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Gets the Lens Serial Number. |
| [getCompositeImage()](#getCompositeImage--) | Gets the Composite image. |
| [getSourceImageNumberOfCompositeImage()](#getSourceImageNumberOfCompositeImage--) | Gets the Source image number of composite image. |
| [getSourceExposureTimesOfCompositeImage()](#getSourceExposureTimesOfCompositeImage--) | Gets the Source exposure times of composite image. |
| [getGamma()](#getGamma--) | Gets the Gamma. |
| [getMakerNote()](#getMakerNote--) | Gets the Standard Output Sensitivity. |
### getRawMakerNotePackage() {#getRawMakerNotePackage--}
```
public RawMakerNotePackage getRawMakerNotePackage()
```


Gets the Manufacturer notes (MakerNote).

**Returns:**
[RawMakerNotePackage](../../com.groupdocs.metadata.core/rawmakernotepackage) - The Manufacturer notes (MakerNote).
### getInteroperabilityIFDPointerPackage() {#getInteroperabilityIFDPointerPackage--}
```
public final InteroperabilityIFDPointerPackage getInteroperabilityIFDPointerPackage()
```


Gets the Interoperability tag (Interoperability IFD Pointer).

**Returns:**
[InteroperabilityIFDPointerPackage](../../com.groupdocs.metadata.core/interoperabilityifdpointerpackage) - The Interoperability tag (Interoperability IFD Pointer).
### getInteroperabilityIFDPointer() {#getInteroperabilityIFDPointer--}
```
public final long getInteroperabilityIFDPointer()
```


Gets the Interoperability tag (Interoperability IFD Pointer).

**Returns:**
long - The Interoperability tag (Interoperability IFD Pointer).
### getExposureTime() {#getExposureTime--}
```
public final float getExposureTime()
```


Gets the Exposure time.

**Returns:**
float - The Exposure time.
### getFNumber() {#getFNumber--}
```
public final float getFNumber()
```


Gets the F number.

**Returns:**
float - The F number.
### getExposureProgram() {#getExposureProgram--}
```
public final int getExposureProgram()
```


Gets the Exposure program.

**Returns:**
int - The Exposure program.
### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public final String getSpectralSensitivity()
```


Gets the Spectral sensitivity.

**Returns:**
java.lang.String - The Spectral sensitivity.
### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public final int getPhotographicSensitivity()
```


Gets the Photographic Sensitivity.

**Returns:**
int - The Photographic Sensitivity.
### getOECF() {#getOECF--}
```
public final byte[] getOECF()
```


Gets the Optoelectric conversion factor.

**Returns:**
byte[] - The Optoelectric conversion factor.
### getSensitivityType() {#getSensitivityType--}
```
public final int getSensitivityType()
```


Gets the Sensitivity Type.

**Returns:**
int - The Sensitivity Type.
### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public final long getStandardOutputSensitivity()
```


Gets the Standard Output Sensitivity.

**Returns:**
long - The Standard Output Sensitivity.
### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public final long getRecommendedExposureIndex()
```


Gets the Recommended ExposureIndexs.

**Returns:**
long - The Recommended ExposureIndex.
### getISOSpeed() {#getISOSpeed--}
```
public final long getISOSpeed()
```


Gets the ISO Speed.

**Returns:**
long - The ISO Speed.
### getISOSpeedLatitudeyyy() {#getISOSpeedLatitudeyyy--}
```
public final long getISOSpeedLatitudeyyy()
```


Gets the ISO Speed Latitude yyy.

**Returns:**
long - The ISO Speed Latitude yyy.
### getISOSpeedLatitudezzz() {#getISOSpeedLatitudezzz--}
```
public final long getISOSpeedLatitudezzz()
```


Gets the ISO Speed Latitude zzz.

**Returns:**
long - The ISO Speed Latitude zzz.
### getExifVersion() {#getExifVersion--}
```
public final byte[] getExifVersion()
```


Gets the ExifVersion.

**Returns:**
byte[] - The ExifVersion.
### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public final String getDateTimeOriginal()
```


Gets the Date and time of original data generation.

**Returns:**
java.lang.String - The Date and time of original data generation.
### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public final String getDateTimeDigitized()
```


Gets the Date and time of digital data generation.

**Returns:**
java.lang.String - The Date and time of digital data generation.
### getOffsetTime() {#getOffsetTime--}
```
public final String getOffsetTime()
```


Gets the Offset data of DateTime.

**Returns:**
java.lang.String - The Offset data of DateTime.
### getOffsetTimeOriginal() {#getOffsetTimeOriginal--}
```
public final String getOffsetTimeOriginal()
```


Gets the Offset data of DateTimeOriginal.

**Returns:**
java.lang.String - The Offset data of DateTimeOriginal.
### getOffsetTimeDigitized() {#getOffsetTimeDigitized--}
```
public final String getOffsetTimeDigitized()
```


Gets the Offset data of DateTimeDigitized.

**Returns:**
java.lang.String - The Offset data of DateTimeDigitized.
### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public final byte[] getComponentsConfiguration()
```


Gets the Meaning of each component.

**Returns:**
byte[] - The Meaning of each component.
### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public final float getShutterSpeedValue()
```


Gets the Shutter speed.

**Returns:**
float - The Shutter speed.
### getApertureValue() {#getApertureValue--}
```
public final float getApertureValue()
```


Gets the Aperture.

**Returns:**
float - The Aperture.
### getBrightnessValue() {#getBrightnessValue--}
```
public final float getBrightnessValue()
```


Gets the Brightness.

**Returns:**
float - The Brightness.
### getExposureBiasValue() {#getExposureBiasValue--}
```
public final float getExposureBiasValue()
```


Gets the Exposure bias.

**Returns:**
float - The Exposure bias.
### getMaxApertureValue() {#getMaxApertureValue--}
```
public final float getMaxApertureValue()
```


Gets the Maximum lens aperture.

**Returns:**
float - The Maximum lens aperture.
### getSubjectDistance() {#getSubjectDistance--}
```
public final float getSubjectDistance()
```


Gets the Subject distance.

**Returns:**
float - The Subject distance.
### getMeteringMode() {#getMeteringMode--}
```
public final int getMeteringMode()
```


Gets the Metering mode.

**Returns:**
int - The Metering mode.
### getLightSource() {#getLightSource--}
```
public final int getLightSource()
```


Gets the Light source.

**Returns:**
int - The Light source.
### getFlash() {#getFlash--}
```
public final int getFlash()
```


Gets the Flash.

**Returns:**
int - The Flash.
### getFocalLength() {#getFocalLength--}
```
public final float getFocalLength()
```


Gets the Lens focal length.

**Returns:**
float - The Lens focal length.
### getSubjectArea() {#getSubjectArea--}
```
public final int getSubjectArea()
```


Gets the Subject area.

**Returns:**
int - The Subject area.
### getUserComment() {#getUserComment--}
```
public final byte[] getUserComment()
```


Gets the User comments.

**Returns:**
byte[] - The User comments.
### getSubSecTime() {#getSubSecTime--}
```
public final String getSubSecTime()
```


Gets the DateTime subseconds.

**Returns:**
java.lang.String - The DateTime subseconds.
### getSubSecTimeOriginal() {#getSubSecTimeOriginal--}
```
public final String getSubSecTimeOriginal()
```


Gets the DateTimeOriginal subseconds.

**Returns:**
java.lang.String - The DateTimeOriginal subseconds.
### getSubSecTimeDigitized() {#getSubSecTimeDigitized--}
```
public final String getSubSecTimeDigitized()
```


Gets the DateTimeDigitized subseconds.

**Returns:**
java.lang.String - The DateTimeDigitized subseconds.
### getTemperature() {#getTemperature--}
```
public final float getTemperature()
```


Gets the Temperature.

**Returns:**
float - The Temperature.
### getHumidity() {#getHumidity--}
```
public final float getHumidity()
```


Gets the Humidity.

**Returns:**
float - The Humidity.
### getPressure() {#getPressure--}
```
public final float getPressure()
```


Gets the Pressure.

**Returns:**
float - The Pressure.
### getWaterDepth() {#getWaterDepth--}
```
public final float getWaterDepth()
```


Gets the WaterDepth.

**Returns:**
float - The WaterDepth.
### getAcceleration() {#getAcceleration--}
```
public final float getAcceleration()
```


Gets the Acceleration.

**Returns:**
float - The Acceleration.
### getCameraElevationAngle() {#getCameraElevationAngle--}
```
public final float getCameraElevationAngle()
```


Gets the Camera elevation angle.

**Returns:**
float - The Camera elevation angle.
### getFlashpixVersion() {#getFlashpixVersion--}
```
public final byte[] getFlashpixVersion()
```


Gets the Temperature.

**Returns:**
byte[] - The Temperature.
### getColorSpace() {#getColorSpace--}
```
public final int getColorSpace()
```


Gets the Color space information .

**Returns:**
int - The Color space information .
### getPixelXDimension() {#getPixelXDimension--}
```
public final long getPixelXDimension()
```


Gets the Valid image width.

**Returns:**
long - The Valid image width.
### getPixelYDimension() {#getPixelYDimension--}
```
public final long getPixelYDimension()
```


Gets the Valid image height.

**Returns:**
long - The Valid image height.
### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public final String getRelatedSoundFile()
```


Gets the Related audio file.

**Returns:**
java.lang.String - The Related audio file.
### getFlashEnergy() {#getFlashEnergy--}
```
public final float getFlashEnergy()
```


Gets the Flash energy.

**Returns:**
float - The Flash energy.
### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public final byte[] getSpatialFrequencyResponse()
```


Gets the Spatial frequency response.

**Returns:**
byte[] - The Spatial frequency response.
### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public final float getFocalPlaneXResolution()
```


Gets Focal plane X resolution.

**Returns:**
float - The Focal plane X resolution.
### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public final float getFocalPlaneYResolution()
```


Gets the Focal plane Y resolution.

**Returns:**
float - The Focal plane Y resolution.
### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public final int getFocalPlaneResolutionUnit()
```


Gets the Focal plane resolution unit.

**Returns:**
int - The Focal plane resolution unit.
### getSubjectLocation() {#getSubjectLocation--}
```
public final int getSubjectLocation()
```


Gets the Subject location.

**Returns:**
int - The Subject location.
### getExposureIndex() {#getExposureIndex--}
```
public final float getExposureIndex()
```


Gets the Exposure index.

**Returns:**
float - The Exposure index.
### getSensingMethod() {#getSensingMethod--}
```
public final int getSensingMethod()
```


Gets the Sensing method.

**Returns:**
int - The Sensing method.
### getFileSource() {#getFileSource--}
```
public final byte[] getFileSource()
```


Gets the File source.

**Returns:**
byte[] - The File source.
### getSceneType() {#getSceneType--}
```
public final byte[] getSceneType()
```


Gets the Scene Type.

**Returns:**
byte[] - The Scene Type.
### getCFAPattern() {#getCFAPattern--}
```
public final byte[] getCFAPattern()
```


Gets the CFA pattern.

**Returns:**
byte[] - The CFA pattern.
### getCustomRendered() {#getCustomRendered--}
```
public final int getCustomRendered()
```


Gets the Custom image processing.

**Returns:**
int - The Custom image processing.
### getExposureMode() {#getExposureMode--}
```
public final int getExposureMode()
```


Gets the Exposure mode.

**Returns:**
int - The Exposure mode.
### getWhiteBalance() {#getWhiteBalance--}
```
public final int getWhiteBalance()
```


Gets the White balance.

**Returns:**
int - The White balance.
### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public final float getDigitalZoomRatio()
```


Gets the Digital zoom ratio.

**Returns:**
float - The Digital zoom ratio.
### getFocalLengthIn35mmFilm() {#getFocalLengthIn35mmFilm--}
```
public final int getFocalLengthIn35mmFilm()
```


Gets the Focal length in 35 mm film.

**Returns:**
int - The Focal length in 35 mm film.
### getSceneCaptureType() {#getSceneCaptureType--}
```
public final int getSceneCaptureType()
```


Gets the Scene capture type.

**Returns:**
int - The Scene capture type.
### getGainControl() {#getGainControl--}
```
public final float getGainControl()
```


Gets the Gain control.

**Returns:**
float - The Gain control.
### getContrast() {#getContrast--}
```
public final int getContrast()
```


Gets the Contrast.

**Returns:**
int - The Contrast.
### getSaturation() {#getSaturation--}
```
public final int getSaturation()
```


Gets the Saturation.

**Returns:**
int - The Saturation.
### getSharpness() {#getSharpness--}
```
public final int getSharpness()
```


Gets the Sharpness.

**Returns:**
int - The Sharpness.
### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public final byte[] getDeviceSettingDescription()
```


Gets the Device settings description.

**Returns:**
byte[] - The Device settings description.
### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public final int getSubjectDistanceRange()
```


Gets the Subject distance range.

**Returns:**
int - The Subject distance range.
### getImageUniqueID() {#getImageUniqueID--}
```
public final String getImageUniqueID()
```


Gets the Unique image ID.

**Returns:**
java.lang.String - The Unique image ID.
### getCameraOwnerName() {#getCameraOwnerName--}
```
public final String getCameraOwnerName()
```


Gets the Camera Owner Name.

**Returns:**
java.lang.String - The Camera Owner Name.
### getBodySerialNumber() {#getBodySerialNumber--}
```
public final String getBodySerialNumber()
```


Gets the Body Serial Number.

**Returns:**
java.lang.String - The Body Serial Number.
### getLensSpecification() {#getLensSpecification--}
```
public final double[] getLensSpecification()
```


Gets the Lens Specification.

**Returns:**
double[] - The Lens Specification.
### getLensModel() {#getLensModel--}
```
public final String getLensModel()
```


Gets the Lens Model.

**Returns:**
java.lang.String - The Lens Model.
### getLensMake() {#getLensMake--}
```
public final String getLensMake()
```


Gets the Lens Make.

**Returns:**
java.lang.String - The Lens Make.
### getLensSerialNumber() {#getLensSerialNumber--}
```
public final String getLensSerialNumber()
```


Gets the Lens Serial Number.

**Returns:**
java.lang.String - The Lens Serial Number.
### getCompositeImage() {#getCompositeImage--}
```
public final int getCompositeImage()
```


Gets the Composite image.

**Returns:**
int - The Composite image.
### getSourceImageNumberOfCompositeImage() {#getSourceImageNumberOfCompositeImage--}
```
public final int getSourceImageNumberOfCompositeImage()
```


Gets the Source image number of composite image.

**Returns:**
int - The Source image number of composite image.
### getSourceExposureTimesOfCompositeImage() {#getSourceExposureTimesOfCompositeImage--}
```
public final byte[] getSourceExposureTimesOfCompositeImage()
```


Gets the Source exposure times of composite image.

**Returns:**
byte[] - The Source exposure times of composite image.
### getGamma() {#getGamma--}
```
public final float getGamma()
```


Gets the Gamma.

**Returns:**
float - The Gamma.
### getMakerNote() {#getMakerNote--}
```
public final long getMakerNote()
```


Gets the Standard Output Sensitivity.

**Returns:**
long - The Standard Output Sensitivity.
