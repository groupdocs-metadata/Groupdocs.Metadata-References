---
title: TiffTagID
second_title: GroupDocs.Metadata for Java API Reference
description: Defines ids of TIFF tags.
type: docs
weight: 251
url: /java/com.groupdocs.metadata.core/tifftagid/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public final class TiffTagID implements IEnumValue
```

Defines ids of TIFF tags.
## Fields

| Field | Description |
| --- | --- |
| [GpsVersionID](#GpsVersionID) | Indicates the version of GPSInfoIFD. |
| [GpsLatitudeRef](#GpsLatitudeRef) | Indicates whether the latitude is north or south latitude. |
| [GpsLatitude](#GpsLatitude) | Indicates the latitude. |
| [GpsLongitudeRef](#GpsLongitudeRef) | Indicates whether the longitude is east or west longitude. |
| [GpsLongitude](#GpsLongitude) | Indicates the longitude. |
| [GpsAltitudeRef](#GpsAltitudeRef) | Indicates the altitude used as the reference altitude. |
| [GpsAltitude](#GpsAltitude) | Indicates the altitude based on the reference in GPSAltitudeRef. |
| [GpsTimeStamp](#GpsTimeStamp) | Indicates the time as UTC (Coordinated Universal Time). |
| [GpsSatellites](#GpsSatellites) | ndicates the GPS satellites used for measurements. |
| [GpsStatus](#GpsStatus) | Indicates the status of the GPS receiver when the image is recorded. |
| [GpsMeasureMode](#GpsMeasureMode) | Indicates the GPS measurement mode. |
| [GpsDop](#GpsDop) | Indicates the GPS DOP (data degree of precision). |
| [GpsSpeedRef](#GpsSpeedRef) | Indicates the unit used to express the GPS receiver speed of movement |
| [GpsSpeed](#GpsSpeed) | Indicates the speed of GPS receiver movement. |
| [GpsTrackRef](#GpsTrackRef) | Indicates the reference for giving the direction of GPS receiver movement. |
| [GpsTrack](#GpsTrack) | Indicates the direction of GPS receiver movement. |
| [GpsImgDirectionRef](#GpsImgDirectionRef) | Indicates the reference for giving the direction of the image when it is captured. |
| [GpsImgDirection](#GpsImgDirection) | Indicates the direction of the image when it was captured. |
| [GpsMapDatum](#GpsMapDatum) | Indicates the geodetic survey data used by the GPS receiver. |
| [GpsDestLatitudeRef](#GpsDestLatitudeRef) | Indicates whether the latitude of the destination point is north or south latitude. |
| [GpsDestLatitude](#GpsDestLatitude) | Indicates the latitude of the destination point. |
| [GpsDestLongitudeRef](#GpsDestLongitudeRef) | Indicates whether the longitude of the destination point is east or west longitude. |
| [GpsDestLongitude](#GpsDestLongitude) | Indicates the longitude of the destination point. |
| [GpsDestBearingRef](#GpsDestBearingRef) | Indicates the reference used for giving the bearing to the destination point. |
| [GpsDestBearing](#GpsDestBearing) | Indicates the bearing to the destination point. |
| [GpsDestDistanceRef](#GpsDestDistanceRef) | Indicates the unit used to express the distance to the destination point. |
| [GpsDestDistance](#GpsDestDistance) | Indicates the distance to the destination point. |
| [GpsProcessingMethod](#GpsProcessingMethod) | A character string recording the name of the method used for location finding. |
| [GpsAreaInformation](#GpsAreaInformation) | A character string recording the name of the GPS area. |
| [GpsDateStamp](#GpsDateStamp) | A character string recording date and time information relative to UTC (Coordinated Universal Time). |
| [GpsDifferential](#GpsDifferential) | Indicates whether differential correction is applied to the GPS receiver. |
| [GpsHPositioningError](#GpsHPositioningError) | This tag indicates horizontal positioning errors in meters. |
| [NewSubfileType](#NewSubfileType) | A general indication of the kind of data contained in this sub-file. |
| [SubfileType](#SubfileType) | A general indication of the kind of data contained in this subfile. |
| [ImageWidth](#ImageWidth) | The number of columns in the image, i.e., the number of pixels per scan line. |
| [ImageLength](#ImageLength) | The number of rows (sometimes described as scan lines) in the image. |
| [BitsPerSample](#BitsPerSample) | Number of bits per component. |
| [Compression](#Compression) | Compression scheme used on the image data. |
| [PhotometricInterpretation](#PhotometricInterpretation) | The color space of the image data. |
| [Threshholding](#Threshholding) | For black and white TIFF files that represent shades of gray, the technique used to convert from gray to black and white pixels. |
| [CellWidth](#CellWidth) | The width of the dithering or halftoning matrix used to create a dithered or halftoned bi-level file. |
| [CellLength](#CellLength) | The length of the dithering or halftoning matrix used to create a dithered or halftoned bi-level file. |
| [FillOrder](#FillOrder) | The logical order of bits within a byte. |
| [DocumentName](#DocumentName) | The name of the document from which this image was scanned. |
| [ImageDescription](#ImageDescription) | A string that describes the subject of the image. |
| [Make](#Make) | The scanner manufacturer. |
| [Model](#Model) | The scanner model name or number. |
| [StripOffsets](#StripOffsets) | For each strip, the byte offset of that strip. |
| [Orientation](#Orientation) | The orientation of the image with respect to the rows and columns. |
| [SamplesPerPixel](#SamplesPerPixel) | The number of components per pixel. |
| [RowsPerStrip](#RowsPerStrip) | The number of rows per strip. |
| [StripByteCounts](#StripByteCounts) | For each strip, the number of bytes in the strip after compression. |
| [MinSampleValue](#MinSampleValue) | The minimum component value used. |
| [MaxSampleValue](#MaxSampleValue) | The maximum component value used. |
| [XResolution](#XResolution) | The number of pixels per ResolutionUnit in the ImageWidth direction. |
| [YResolution](#YResolution) | The number of pixels per ResolutionUnit in the ImageLength direction. |
| [PlanarConfiguration](#PlanarConfiguration) | How the components of each pixel are stored. |
| [PageName](#PageName) | The name of the page from which this image was scanned. |
| [XPosition](#XPosition) | X position of the image. |
| [YPosition](#YPosition) | Y position of the image. |
| [FreeOffsets](#FreeOffsets) | For each string of contiguous unused bytes in a TIFF file, the byte offset of the string. |
| [FreeByteCounts](#FreeByteCounts) | For each string of contiguous unused bytes in a TIFF file, the number of bytes in the string. |
| [GrayResponseUnit](#GrayResponseUnit) | The precision of the information contained in the GrayResponseCurve. |
| [GrayResponseCurve](#GrayResponseCurve) | For grayscale data, the optical density of each possible pixel value. |
| [T4Options](#T4Options) | T4-encoding options. |
| [T6Options](#T6Options) | T6-encoding options. |
| [ResolutionUnit](#ResolutionUnit) | The unit of measurement for XResolution and YResolution. |
| [PageNumber](#PageNumber) | The page number of the page from which this image was scanned. |
| [TransferFunction](#TransferFunction) | Describes a transfer function for the image in tabular style. |
| [Software](#Software) | Name and version number of the software package(s) used to create the image. |
| [DateTime](#DateTime) | Date and time of image creation. |
| [Artist](#Artist) | Person who created the image. |
| [HostComputer](#HostComputer) | The computer and/or operating system in use at the time of image creation. |
| [Predictor](#Predictor) | This section defines a Predictor that greatly improves compression ratios for some images. |
| [WhitePoint](#WhitePoint) | The chromaticity of the white point of the image. |
| [PrimaryChromaticities](#PrimaryChromaticities) | The chromaticities of the primaries of the image. |
| [ColorMap](#ColorMap) | A color map for palette color images. |
| [HalftoneHints](#HalftoneHints) | The purpose of the HalftoneHints field is to convey to the halftone function the range of gray levels within a colorimetrically-specified image that should retain tonal detail. |
| [TileWidth](#TileWidth) | The tile width in pixels. |
| [TileLength](#TileLength) | The tile length (height) in pixels. |
| [TileOffsets](#TileOffsets) | For each tile, the byte offset of that tile, as compressed and stored on disk. |
| [TileByteCounts](#TileByteCounts) | For each tile, the number of (compressed) bytes in that tile. |
| [InkSet](#InkSet) | The set of inks used in a separated (PhotometricInterpretation=5) image. |
| [InkNames](#InkNames) | The name of each ink used in a separated (PhotometricInterpretation=5) image, written as a list of concatenated, NUL-terminated ASCII strings. |
| [NumberOfInks](#NumberOfInks) | The number of inks. |
| [DotRange](#DotRange) | The component values that correspond to a 0% dot and 100% dot. |
| [ExtraSamples](#ExtraSamples) | Description of extra components. |
| [SampleFormat](#SampleFormat) | This field specifies how to interpret each data sample in a pixel. |
| [SMinSampleValue](#SMinSampleValue) | This field specifies the minimum sample value. |
| [SMaxSampleValue](#SMaxSampleValue) | This new field specifies the maximum sample value. |
| [TransferRange](#TransferRange) | Expands the range of the TransferFunction. |
| [JpegProc](#JpegProc) | This Field indicates the JPEG process used to produce the compressed data. |
| [JpegInterchangeFormat](#JpegInterchangeFormat) | This Field indicates whether a JPEG interchange format bitstream is present in the TIFF file. |
| [JpegInterchangeFormatLength](#JpegInterchangeFormatLength) | This Field indicates the length in bytes of the JPEG interchange format bitstream |
| [JpegRestartInterval](#JpegRestartInterval) | This Field indicates the length of the restart interval used in the compressed image data. |
| [JpegLosslessPredictors](#JpegLosslessPredictors) | This Field points to a list of lossless predictor-selection values, one per component. |
| [JpegPointTransforms](#JpegPointTransforms) | This Field points to a list of point transform values, one per component. |
| [JpegQTables](#JpegQTables) | This Field points to a list of offsets to the quantization tables, one per component. |
| [JpegDCTables](#JpegDCTables) | This Field points to a list of offsets to the DC Huffman tables or the lossless Huffman tables, one per component. |
| [JpegACTables](#JpegACTables) | This Field points to a list of offsets to the Huffman AC tables, one per component. |
| [YCbCrCoefficients](#YCbCrCoefficients) | The matrix cofficients for transformation from RGB to YCbCr image data. |
| [YCbCrSubSampling](#YCbCrSubSampling) | The sampling ratio of chrominance components in relation to the luminance component. |
| [YCbCrPositioning](#YCbCrPositioning) | Specifies the positioning of subsampled chrominance components relative to luminance samples. |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | Specifies a pair of headroom and footroom image data values (codes) for each pixel component. |
| [Copyright](#Copyright) | Copyright notice. |
| [UserComment](#UserComment) | Keywords or comments on the image; complements ImageDescription. |
| [Xmp](#Xmp) | Pointer to the XMP metadata. |
| [ImageID](#ImageID) | OPI-related. |
| [Iptc](#Iptc) | IPTC (International Press Telecommunications Council) metadata. |
| [Photoshop](#Photoshop) | Collection of Photoshop 'Image Resource Blocks'. |
| [ImageLayer](#ImageLayer) | Image layer. |
| [IccProfile](#IccProfile) | Color profile data. |
| [ExifIfd](#ExifIfd) | Pointer to collection of all EXIF Metadata. |
| [GpsIfd](#GpsIfd) | Pointer to GPS data. |
| [Makernotes](#Makernotes) | Pointer to makernotes data. |
| [InteroperabilityIfd](#InteroperabilityIfd) | Exif-related Interoperability IFD. |
| [CameraOwnerName](#CameraOwnerName) | Camera owner name as ASCII string. |
| [BodySerialNumber](#BodySerialNumber) | Camera body serial number as ASCII string. |
| [CfaPattern](#CfaPattern) | ndicates the color filter array (CFA) geometric pattern of the image sensor when a one-chip color area sensor is used. |
| [ExifVersion](#ExifVersion) | The version of the EXIF standard supported. |
| [ComponentsConfiguration](#ComponentsConfiguration) | Information specific to the compressed data. |
| [FlashpixVersion](#FlashpixVersion) | The Flashpix format version supported by a FPXR file. |
| [ColorSpace](#ColorSpace) | The color space information tag (ColorSpace) is always recorded as the color space specifier. |
| [PixelXDimension](#PixelXDimension) | Information specific to compressed data. |
| [PixelYDimension](#PixelYDimension) | Information specific to compressed data. |
| [SceneCaptureType](#SceneCaptureType) | This tag indicates the type of scene that was shot. |
| [Gamma](#Gamma) | Indicates the value of coefficient gamma. |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | Information specific to compressed data. |
| [RelatedSoundFile](#RelatedSoundFile) | This tag is used to record the name of an audio file related to the image data. |
| [DateTimeOriginal](#DateTimeOriginal) | The date and time when the original image data was generated. |
| [DateTimeDigitized](#DateTimeDigitized) | The date and time when the image was stored as digital data. |
| [OffsetTime](#OffsetTime) | A tag used to record the offset from UTC (the time difference from Universal Time Coordinated including daylight saving time) of the time of DateTime tag. |
| [OffsetTimeOriginal](#OffsetTimeOriginal) | A tag used to record the offset from UTC (the time difference from Universal Time Coordinated including daylight saving time) of the time of DateTimeOriginal tag. |
| [OffsetTimeDigitized](#OffsetTimeDigitized) | A tag used to record the offset from UTC (the time difference from Universal Time Coordinated including daylight saving time) of the time of DateTimeDigitized tag. |
| [SubsecTime](#SubsecTime) | A tag used to record fractions of seconds for the DateTime tag. |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | A tag used to record fractions of seconds for the DateTimeOriginal tag. |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | A tag used to record fractions of seconds for the DateTimeDigitized tag. |
| [ExposureTime](#ExposureTime) | Exposure time, given in seconds (sec). |
| [FNumber](#FNumber) | The F number. |
| [ExposureProgram](#ExposureProgram) | The class of the program used by the camera to set exposure when the picture is taken. |
| [SpectralSensitivity](#SpectralSensitivity) | Indicates the spectral sensitivity of each channel of the camera used. |
| [PhotographicSensitivity](#PhotographicSensitivity) | This tag indicates the sensitivity of the camera or input device when the image was shot. |
| [Oecf](#Oecf) | Indicates the Opto-Electric Conversion Function (OECF) specified in ISO 14524. |
| [SensitivityType](#SensitivityType) | The SensitivityType tag indicates which one of the parameters of ISO12232 is the PhotographicSensitivity tag. |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | This tag indicates the standard output sensitivity value of a camera or input device defined in ISO 12232. |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | This tag indicates the recommended exposure index value of a camera or input device defined in ISO 12232. |
| [IsoSpeed](#IsoSpeed) | This tag indicates the ISO speed value of a camera or input device that is defined in ISO 12232. |
| [ISOSpeedLatitudeYyy](#ISOSpeedLatitudeYyy) | This tag indicates the ISO speed latitude yyy value of a camera or input device that is defined in ISO 12232. |
| [ISOSpeedLatitudeZzz](#ISOSpeedLatitudeZzz) | This tag indicates the ISO speed latitude zzz value of a camera or input device that is defined in ISO 12232. |
| [ShutterSpeedValue](#ShutterSpeedValue) | Shutter speed. |
| [ApertureValue](#ApertureValue) | The lens aperture. |
| [BrightnessValue](#BrightnessValue) | The value of brightness. |
| [ExposureBiasValue](#ExposureBiasValue) | The exposure bias. |
| [MaxApertureValue](#MaxApertureValue) | The smallest F number of the lens. |
| [SubjectDistance](#SubjectDistance) | The distance to the subject, given in meters. |
| [MeteringMode](#MeteringMode) | The metering mode. |
| [LightSource](#LightSource) | The kind of light source. |
| [Flash](#Flash) | This tag indicates the status of flash when the image was shot. |
| [SubjectArea](#SubjectArea) | This tag indicates the location and area of the main subject in the overall scene. |
| [FocalLength](#FocalLength) | The actual focal length of the lens, in mm. |
| [FlashEnergy](#FlashEnergy) | Indicates the strobe energy at the time the image is captured, as measured in Beam Candle Power Seconds (BCPS). |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | This tag records the camera or input device spatial frequency table and SFR values in the direction of image width, image height, and diagonal direction, as specified in ISO 12233. |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | Indicates the number of pixels in the image width (X) direction per FocalPlaneResolutionUnit on the camera focal plane. |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | Indicates the number of pixels in the image height (Y) direction per FocalPlaneResolutionUnit on the camera focal plane. |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | Indicates the unit for measuring FocalPlaneXResolution and FocalPlaneYResolution. |
| [SubjectLocation](#SubjectLocation) | Indicates the location of the main subject in the scene. |
| [ExposureIndex](#ExposureIndex) | Indicates the exposure index selected on the camera or input device at the time the image is captured. |
| [SensingMethod](#SensingMethod) | Indicates the image sensor type on the camera or input device. |
| [FileSource](#FileSource) | Indicates the image source. |
| [SceneType](#SceneType) | Indicates the type of scene. |
| [CustomRendered](#CustomRendered) | This tag indicates the use of special processing on image data, such as rendering geared to output. |
| [ExposureMode](#ExposureMode) | This tag indicates the exposure mode set when the image was shot. |
| [WhiteBalance](#WhiteBalance) | This tag indicates the white balance mode set when the image was shot. |
| [DigitalZoomRatio](#DigitalZoomRatio) | This tag indicates the digital zoom ratio when the image was shot. |
| [FocalLengthIn35mmFilm](#FocalLengthIn35mmFilm) | This tag indicates the equivalent focal length assuming a 35mm film camera, in mm. |
| [GainControl](#GainControl) | This tag indicates the degree of overall image gain adjustment. |
| [Contrast](#Contrast) | This tag indicates the direction of contrast processing applied by the camera when the image was shot. |
| [Saturation](#Saturation) | This tag indicates the direction of saturation processing applied by the camera when the image was shot. |
| [Sharpness](#Sharpness) | This tag indicates the direction of sharpness processing applied by the camera when the image was shot. |
| [DeviceSettingDescription](#DeviceSettingDescription) | This tag indicates information on the picture-taking conditions of a particular camera model. |
| [SubjectDistanceRange](#SubjectDistanceRange) | This tag indicates the distance to the subject. |
| [CompositeImage](#CompositeImage) | This tag indicates whether the recorded image is a composite image\* or not. |
| [SourceImageNumberOfCompositeImage](#SourceImageNumberOfCompositeImage) | This tag indicates the number of the source images (tentatively recorded images) captured for a composite Image. |
| [SourceExposureTimesOfCompositeImage](#SourceExposureTimesOfCompositeImage) | For a composite image, this tag records the parameters relating exposure time of the exposures for generating the said composite image, such as respective exposure times of captured source images (tentatively recorded images). |
| [Temperature](#Temperature) | Temperature as the ambient situation at the shot, for example the room temperature where the photographer was holding the camera. |
| [Humidity](#Humidity) | Humidity as the ambient situation at the shot, for example the room humidity where the photographer was holding the camera. |
| [Pressure](#Pressure) | Pressure as the ambient situation at the shot, for example the room atmospfere where the photographer was holding the camera or the water pressure under the sea. |
| [WaterDepth](#WaterDepth) | Water depth as the ambient situation at the shot, for example the water depth of the camera at underwater photography. |
| [Acceleration](#Acceleration) | Acceleration (a scalar regardless of direction) as the ambient situation at the shot, for example the driving acceleration of the vehicle which the photographer rode on at the shot. |
| [CameraElevationAngle](#CameraElevationAngle) | Elevation/depression. |
| [ImageUniqueID](#ImageUniqueID) | This tag indicates an identifier assigned uniquely to each image. |
| [LensSpecification](#LensSpecification) | This tag notes minimum focal length, maximum focal length, minimum F number in the minimum focal length, and minimum F number in the maximum focal length, which are specification information for the lens that was used in photography. |
| [LensMake](#LensMake) | This tag records the lens manufacturer as an ASCII string. |
| [LensModel](#LensModel) | This tag records the lens\\u2019s model name and model number as an ASCII string. |
| [LensSerialNumber](#LensSerialNumber) | This tag records the serial number of the interchangeable lens that was used in photography as an ASCII string. |
## Methods

| Method | Description |
| --- | --- |
| [getByRawValue(int rawValue)](#getByRawValue-int-) |  |
| [getFirst()](#getFirst--) |  |
| [getAllValues()](#getAllValues--) |  |
| [values()](#values--) |  |
| [getEnumValueByRawValue(int rawValue)](#getEnumValueByRawValue-int-) |  |
| [getEnumValueByName(String name)](#getEnumValueByName-java.lang.String-) |  |
| [getRawValueType()](#getRawValueType--) |  |
| [getRawValue()](#getRawValue--) |  |
| [name()](#name--) |  |
| [equals(Object o)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### GpsVersionID {#GpsVersionID}
```
public static final TiffTagID GpsVersionID
```


Indicates the version of GPSInfoIFD.

### GpsLatitudeRef {#GpsLatitudeRef}
```
public static final TiffTagID GpsLatitudeRef
```


Indicates whether the latitude is north or south latitude.

### GpsLatitude {#GpsLatitude}
```
public static final TiffTagID GpsLatitude
```


Indicates the latitude.

### GpsLongitudeRef {#GpsLongitudeRef}
```
public static final TiffTagID GpsLongitudeRef
```


Indicates whether the longitude is east or west longitude.

### GpsLongitude {#GpsLongitude}
```
public static final TiffTagID GpsLongitude
```


Indicates the longitude.

### GpsAltitudeRef {#GpsAltitudeRef}
```
public static final TiffTagID GpsAltitudeRef
```


Indicates the altitude used as the reference altitude.

### GpsAltitude {#GpsAltitude}
```
public static final TiffTagID GpsAltitude
```


Indicates the altitude based on the reference in GPSAltitudeRef.

### GpsTimeStamp {#GpsTimeStamp}
```
public static final TiffTagID GpsTimeStamp
```


Indicates the time as UTC (Coordinated Universal Time).

### GpsSatellites {#GpsSatellites}
```
public static final TiffTagID GpsSatellites
```


ndicates the GPS satellites used for measurements.

### GpsStatus {#GpsStatus}
```
public static final TiffTagID GpsStatus
```


Indicates the status of the GPS receiver when the image is recorded.

### GpsMeasureMode {#GpsMeasureMode}
```
public static final TiffTagID GpsMeasureMode
```


Indicates the GPS measurement mode.

### GpsDop {#GpsDop}
```
public static final TiffTagID GpsDop
```


Indicates the GPS DOP (data degree of precision).

### GpsSpeedRef {#GpsSpeedRef}
```
public static final TiffTagID GpsSpeedRef
```


Indicates the unit used to express the GPS receiver speed of movement

### GpsSpeed {#GpsSpeed}
```
public static final TiffTagID GpsSpeed
```


Indicates the speed of GPS receiver movement.

### GpsTrackRef {#GpsTrackRef}
```
public static final TiffTagID GpsTrackRef
```


Indicates the reference for giving the direction of GPS receiver movement.

### GpsTrack {#GpsTrack}
```
public static final TiffTagID GpsTrack
```


Indicates the direction of GPS receiver movement.

### GpsImgDirectionRef {#GpsImgDirectionRef}
```
public static final TiffTagID GpsImgDirectionRef
```


Indicates the reference for giving the direction of the image when it is captured.

### GpsImgDirection {#GpsImgDirection}
```
public static final TiffTagID GpsImgDirection
```


Indicates the direction of the image when it was captured.

### GpsMapDatum {#GpsMapDatum}
```
public static final TiffTagID GpsMapDatum
```


Indicates the geodetic survey data used by the GPS receiver.

### GpsDestLatitudeRef {#GpsDestLatitudeRef}
```
public static final TiffTagID GpsDestLatitudeRef
```


Indicates whether the latitude of the destination point is north or south latitude.

### GpsDestLatitude {#GpsDestLatitude}
```
public static final TiffTagID GpsDestLatitude
```


Indicates the latitude of the destination point.

### GpsDestLongitudeRef {#GpsDestLongitudeRef}
```
public static final TiffTagID GpsDestLongitudeRef
```


Indicates whether the longitude of the destination point is east or west longitude.

### GpsDestLongitude {#GpsDestLongitude}
```
public static final TiffTagID GpsDestLongitude
```


Indicates the longitude of the destination point.

### GpsDestBearingRef {#GpsDestBearingRef}
```
public static final TiffTagID GpsDestBearingRef
```


Indicates the reference used for giving the bearing to the destination point.

### GpsDestBearing {#GpsDestBearing}
```
public static final TiffTagID GpsDestBearing
```


Indicates the bearing to the destination point.

### GpsDestDistanceRef {#GpsDestDistanceRef}
```
public static final TiffTagID GpsDestDistanceRef
```


Indicates the unit used to express the distance to the destination point.

### GpsDestDistance {#GpsDestDistance}
```
public static final TiffTagID GpsDestDistance
```


Indicates the distance to the destination point.

### GpsProcessingMethod {#GpsProcessingMethod}
```
public static final TiffTagID GpsProcessingMethod
```


A character string recording the name of the method used for location finding.

### GpsAreaInformation {#GpsAreaInformation}
```
public static final TiffTagID GpsAreaInformation
```


A character string recording the name of the GPS area.

### GpsDateStamp {#GpsDateStamp}
```
public static final TiffTagID GpsDateStamp
```


A character string recording date and time information relative to UTC (Coordinated Universal Time).

### GpsDifferential {#GpsDifferential}
```
public static final TiffTagID GpsDifferential
```


Indicates whether differential correction is applied to the GPS receiver.

### GpsHPositioningError {#GpsHPositioningError}
```
public static final TiffTagID GpsHPositioningError
```


This tag indicates horizontal positioning errors in meters.

### NewSubfileType {#NewSubfileType}
```
public static final TiffTagID NewSubfileType
```


A general indication of the kind of data contained in this sub-file.

### SubfileType {#SubfileType}
```
public static final TiffTagID SubfileType
```


A general indication of the kind of data contained in this subfile. This field is deprecated. The NewSubfileType field should be used instead

### ImageWidth {#ImageWidth}
```
public static final TiffTagID ImageWidth
```


The number of columns in the image, i.e., the number of pixels per scan line.

### ImageLength {#ImageLength}
```
public static final TiffTagID ImageLength
```


The number of rows (sometimes described as scan lines) in the image.

### BitsPerSample {#BitsPerSample}
```
public static final TiffTagID BitsPerSample
```


Number of bits per component.

### Compression {#Compression}
```
public static final TiffTagID Compression
```


Compression scheme used on the image data.

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final TiffTagID PhotometricInterpretation
```


The color space of the image data.

### Threshholding {#Threshholding}
```
public static final TiffTagID Threshholding
```


For black and white TIFF files that represent shades of gray, the technique used to convert from gray to black and white pixels.

### CellWidth {#CellWidth}
```
public static final TiffTagID CellWidth
```


The width of the dithering or halftoning matrix used to create a dithered or halftoned bi-level file.

### CellLength {#CellLength}
```
public static final TiffTagID CellLength
```


The length of the dithering or halftoning matrix used to create a dithered or halftoned bi-level file.

### FillOrder {#FillOrder}
```
public static final TiffTagID FillOrder
```


The logical order of bits within a byte.

### DocumentName {#DocumentName}
```
public static final TiffTagID DocumentName
```


The name of the document from which this image was scanned.

### ImageDescription {#ImageDescription}
```
public static final TiffTagID ImageDescription
```


A string that describes the subject of the image.

### Make {#Make}
```
public static final TiffTagID Make
```


The scanner manufacturer.

### Model {#Model}
```
public static final TiffTagID Model
```


The scanner model name or number.

### StripOffsets {#StripOffsets}
```
public static final TiffTagID StripOffsets
```


For each strip, the byte offset of that strip.

### Orientation {#Orientation}
```
public static final TiffTagID Orientation
```


The orientation of the image with respect to the rows and columns.

### SamplesPerPixel {#SamplesPerPixel}
```
public static final TiffTagID SamplesPerPixel
```


The number of components per pixel.

### RowsPerStrip {#RowsPerStrip}
```
public static final TiffTagID RowsPerStrip
```


The number of rows per strip.

### StripByteCounts {#StripByteCounts}
```
public static final TiffTagID StripByteCounts
```


For each strip, the number of bytes in the strip after compression.

### MinSampleValue {#MinSampleValue}
```
public static final TiffTagID MinSampleValue
```


The minimum component value used.

### MaxSampleValue {#MaxSampleValue}
```
public static final TiffTagID MaxSampleValue
```


The maximum component value used.

### XResolution {#XResolution}
```
public static final TiffTagID XResolution
```


The number of pixels per ResolutionUnit in the ImageWidth direction.

### YResolution {#YResolution}
```
public static final TiffTagID YResolution
```


The number of pixels per ResolutionUnit in the ImageLength direction.

### PlanarConfiguration {#PlanarConfiguration}
```
public static final TiffTagID PlanarConfiguration
```


How the components of each pixel are stored.

### PageName {#PageName}
```
public static final TiffTagID PageName
```


The name of the page from which this image was scanned.

### XPosition {#XPosition}
```
public static final TiffTagID XPosition
```


X position of the image.

### YPosition {#YPosition}
```
public static final TiffTagID YPosition
```


Y position of the image.

### FreeOffsets {#FreeOffsets}
```
public static final TiffTagID FreeOffsets
```


For each string of contiguous unused bytes in a TIFF file, the byte offset of the string.

### FreeByteCounts {#FreeByteCounts}
```
public static final TiffTagID FreeByteCounts
```


For each string of contiguous unused bytes in a TIFF file, the number of bytes in the string.

### GrayResponseUnit {#GrayResponseUnit}
```
public static final TiffTagID GrayResponseUnit
```


The precision of the information contained in the GrayResponseCurve.

### GrayResponseCurve {#GrayResponseCurve}
```
public static final TiffTagID GrayResponseCurve
```


For grayscale data, the optical density of each possible pixel value.

### T4Options {#T4Options}
```
public static final TiffTagID T4Options
```


T4-encoding options.

### T6Options {#T6Options}
```
public static final TiffTagID T6Options
```


T6-encoding options.

### ResolutionUnit {#ResolutionUnit}
```
public static final TiffTagID ResolutionUnit
```


The unit of measurement for XResolution and YResolution.

### PageNumber {#PageNumber}
```
public static final TiffTagID PageNumber
```


The page number of the page from which this image was scanned.

### TransferFunction {#TransferFunction}
```
public static final TiffTagID TransferFunction
```


Describes a transfer function for the image in tabular style. Pixel components can be gamma-compensated, companded, non-uniformly quantized, or coded in some other way. The TransferFunction maps the pixel components from a non-linear BitsPerSample (e.g. 8-bit) form into a 16-bit linear form without a perceptible loss of accuracy.

### Software {#Software}
```
public static final TiffTagID Software
```


Name and version number of the software package(s) used to create the image.

### DateTime {#DateTime}
```
public static final TiffTagID DateTime
```


Date and time of image creation.

### Artist {#Artist}
```
public static final TiffTagID Artist
```


Person who created the image.

### HostComputer {#HostComputer}
```
public static final TiffTagID HostComputer
```


The computer and/or operating system in use at the time of image creation.

### Predictor {#Predictor}
```
public static final TiffTagID Predictor
```


This section defines a Predictor that greatly improves compression ratios for some images.

### WhitePoint {#WhitePoint}
```
public static final TiffTagID WhitePoint
```


The chromaticity of the white point of the image.

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final TiffTagID PrimaryChromaticities
```


The chromaticities of the primaries of the image.

### ColorMap {#ColorMap}
```
public static final TiffTagID ColorMap
```


A color map for palette color images.

### HalftoneHints {#HalftoneHints}
```
public static final TiffTagID HalftoneHints
```


The purpose of the HalftoneHints field is to convey to the halftone function the range of gray levels within a colorimetrically-specified image that should retain tonal detail.

### TileWidth {#TileWidth}
```
public static final TiffTagID TileWidth
```


The tile width in pixels. This is the number of columns in each tile.

### TileLength {#TileLength}
```
public static final TiffTagID TileLength
```


The tile length (height) in pixels. This is the number of rows in each tile.

### TileOffsets {#TileOffsets}
```
public static final TiffTagID TileOffsets
```


For each tile, the byte offset of that tile, as compressed and stored on disk. The offset is specified with respect to the beginning of the TIFF file. Note that this implies that each tile has a location independent of the locations of other tiles.

### TileByteCounts {#TileByteCounts}
```
public static final TiffTagID TileByteCounts
```


For each tile, the number of (compressed) bytes in that tile.

### InkSet {#InkSet}
```
public static final TiffTagID InkSet
```


The set of inks used in a separated (PhotometricInterpretation=5) image.

### InkNames {#InkNames}
```
public static final TiffTagID InkNames
```


The name of each ink used in a separated (PhotometricInterpretation=5) image, written as a list of concatenated, NUL-terminated ASCII strings.

### NumberOfInks {#NumberOfInks}
```
public static final TiffTagID NumberOfInks
```


The number of inks. Usually equal to SamplesPerPixel, unless there are extra samples.

### DotRange {#DotRange}
```
public static final TiffTagID DotRange
```


The component values that correspond to a 0% dot and 100% dot. DotRange[0] corresponds to a 0% dot, and DotRange[1] corresponds to a 100% dot.

### ExtraSamples {#ExtraSamples}
```
public static final TiffTagID ExtraSamples
```


Description of extra components.

### SampleFormat {#SampleFormat}
```
public static final TiffTagID SampleFormat
```


This field specifies how to interpret each data sample in a pixel.

### SMinSampleValue {#SMinSampleValue}
```
public static final TiffTagID SMinSampleValue
```


This field specifies the minimum sample value.

### SMaxSampleValue {#SMaxSampleValue}
```
public static final TiffTagID SMaxSampleValue
```


This new field specifies the maximum sample value.

### TransferRange {#TransferRange}
```
public static final TiffTagID TransferRange
```


Expands the range of the TransferFunction.

### JpegProc {#JpegProc}
```
public static final TiffTagID JpegProc
```


This Field indicates the JPEG process used to produce the compressed data.

### JpegInterchangeFormat {#JpegInterchangeFormat}
```
public static final TiffTagID JpegInterchangeFormat
```


This Field indicates whether a JPEG interchange format bitstream is present in the TIFF file.

### JpegInterchangeFormatLength {#JpegInterchangeFormatLength}
```
public static final TiffTagID JpegInterchangeFormatLength
```


This Field indicates the length in bytes of the JPEG interchange format bitstream

### JpegRestartInterval {#JpegRestartInterval}
```
public static final TiffTagID JpegRestartInterval
```


This Field indicates the length of the restart interval used in the compressed image data.

### JpegLosslessPredictors {#JpegLosslessPredictors}
```
public static final TiffTagID JpegLosslessPredictors
```


This Field points to a list of lossless predictor-selection values, one per component.

### JpegPointTransforms {#JpegPointTransforms}
```
public static final TiffTagID JpegPointTransforms
```


This Field points to a list of point transform values, one per component.

### JpegQTables {#JpegQTables}
```
public static final TiffTagID JpegQTables
```


This Field points to a list of offsets to the quantization tables, one per component.

### JpegDCTables {#JpegDCTables}
```
public static final TiffTagID JpegDCTables
```


This Field points to a list of offsets to the DC Huffman tables or the lossless Huffman tables, one per component.

### JpegACTables {#JpegACTables}
```
public static final TiffTagID JpegACTables
```


This Field points to a list of offsets to the Huffman AC tables, one per component.

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final TiffTagID YCbCrCoefficients
```


The matrix cofficients for transformation from RGB to YCbCr image data.

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final TiffTagID YCbCrSubSampling
```


The sampling ratio of chrominance components in relation to the luminance component.

### YCbCrPositioning {#YCbCrPositioning}
```
public static final TiffTagID YCbCrPositioning
```


Specifies the positioning of subsampled chrominance components relative to luminance samples.

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final TiffTagID ReferenceBlackWhite
```


Specifies a pair of headroom and footroom image data values (codes) for each pixel component.

### Copyright {#Copyright}
```
public static final TiffTagID Copyright
```


Copyright notice.

### UserComment {#UserComment}
```
public static final TiffTagID UserComment
```


Keywords or comments on the image; complements ImageDescription.

### Xmp {#Xmp}
```
public static final TiffTagID Xmp
```


Pointer to the XMP metadata.

### ImageID {#ImageID}
```
public static final TiffTagID ImageID
```


OPI-related.

### Iptc {#Iptc}
```
public static final TiffTagID Iptc
```


IPTC (International Press Telecommunications Council) metadata. Often times, the data type is incorrectly specified as LONG.

### Photoshop {#Photoshop}
```
public static final TiffTagID Photoshop
```


Collection of Photoshop 'Image Resource Blocks'.

### ImageLayer {#ImageLayer}
```
public static final TiffTagID ImageLayer
```


Image layer.

### IccProfile {#IccProfile}
```
public static final TiffTagID IccProfile
```


Color profile data.

### ExifIfd {#ExifIfd}
```
public static final TiffTagID ExifIfd
```


Pointer to collection of all EXIF Metadata. EXIF uses field names rather than tags to indicate the field content.

### GpsIfd {#GpsIfd}
```
public static final TiffTagID GpsIfd
```


Pointer to GPS data.

### Makernotes {#Makernotes}
```
public static final TiffTagID Makernotes
```


Pointer to makernotes data.

### InteroperabilityIfd {#InteroperabilityIfd}
```
public static final TiffTagID InteroperabilityIfd
```


Exif-related Interoperability IFD.

### CameraOwnerName {#CameraOwnerName}
```
public static final TiffTagID CameraOwnerName
```


Camera owner name as ASCII string.

### BodySerialNumber {#BodySerialNumber}
```
public static final TiffTagID BodySerialNumber
```


Camera body serial number as ASCII string.

### CfaPattern {#CfaPattern}
```
public static final TiffTagID CfaPattern
```


ndicates the color filter array (CFA) geometric pattern of the image sensor when a one-chip color area sensor is used. It does not apply to all sensing methods.

### ExifVersion {#ExifVersion}
```
public static final TiffTagID ExifVersion
```


The version of the EXIF standard supported.

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final TiffTagID ComponentsConfiguration
```


Information specific to the compressed data. The channels of each component are arranged in order from the 1st component to the 4th.

### FlashpixVersion {#FlashpixVersion}
```
public static final TiffTagID FlashpixVersion
```


The Flashpix format version supported by a FPXR file. If the FPXR function supports Flashpix format Ver. 1.0, this is indicated similarly to ExifVersion by recording "0100" as 4-byte ASCII.

### ColorSpace {#ColorSpace}
```
public static final TiffTagID ColorSpace
```


The color space information tag (ColorSpace) is always recorded as the color space specifier. Normally sRGB (=1) is used to define the color space based on the PC monitor conditions and environment. If a color space other than sRGB is used, Uncalibrated (=FFFF.H) is set.

### PixelXDimension {#PixelXDimension}
```
public static final TiffTagID PixelXDimension
```


Information specific to compressed data. When a compressed file is recorded, the valid width of the meaningful image shall be recorded in this tag, whether or not there is padding data or a restart marker.

### PixelYDimension {#PixelYDimension}
```
public static final TiffTagID PixelYDimension
```


Information specific to compressed data. When a compressed file is recorded, the valid height of the meaningful image shall be recorded in this tag, whether or not there is padding data or a restart marker.

### SceneCaptureType {#SceneCaptureType}
```
public static final TiffTagID SceneCaptureType
```


This tag indicates the type of scene that was shot. It may also be used to record the mode in which the image was shot.

### Gamma {#Gamma}
```
public static final TiffTagID Gamma
```


Indicates the value of coefficient gamma.

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final TiffTagID CompressedBitsPerPixel
```


Information specific to compressed data. The compression mode used for a compressed image is indicated in unit bits per pixel.

### RelatedSoundFile {#RelatedSoundFile}
```
public static final TiffTagID RelatedSoundFile
```


This tag is used to record the name of an audio file related to the image data. The only relational information recorded here is the Exif audio file name and extension (an ASCII string consisting of 8 characters + '.' + 3 characters).

### DateTimeOriginal {#DateTimeOriginal}
```
public static final TiffTagID DateTimeOriginal
```


The date and time when the original image data was generated. For a DSC the date and time the picture was taken are recorded. The format is "YYYY:MM:DD HH:MM:SS" with time shown in 24-hour format, and the date and time separated by one blank character.

### DateTimeDigitized {#DateTimeDigitized}
```
public static final TiffTagID DateTimeDigitized
```


The date and time when the image was stored as digital data. If, for example, an image was captured by DSC and at the same time the file was recorded, then the DateTimeOriginal and DateTimeDigitized will have the same contents. The format is "YYYY:MM:DD HH:MM:SS" with time shown in 24-hour format, and the date and time separated by one blank character.

### OffsetTime {#OffsetTime}
```
public static final TiffTagID OffsetTime
```


A tag used to record the offset from UTC (the time difference from Universal Time Coordinated including daylight saving time) of the time of DateTime tag. The format when recording the offset is "±HH:MM". The part of "±" shall be recorded as "+" or "-".

### OffsetTimeOriginal {#OffsetTimeOriginal}
```
public static final TiffTagID OffsetTimeOriginal
```


A tag used to record the offset from UTC (the time difference from Universal Time Coordinated including daylight saving time) of the time of DateTimeOriginal tag. The format when recording the offset is "±HH:MM". The part of "±" shall be recorded as "+" or "-".

### OffsetTimeDigitized {#OffsetTimeDigitized}
```
public static final TiffTagID OffsetTimeDigitized
```


A tag used to record the offset from UTC (the time difference from Universal Time Coordinated including daylight saving time) of the time of DateTimeDigitized tag. The format when recording the offset is "±HH:MM". The part of "±" shall be recorded as "+" or "-".

### SubsecTime {#SubsecTime}
```
public static final TiffTagID SubsecTime
```


A tag used to record fractions of seconds for the DateTime tag.

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final TiffTagID SubsecTimeOriginal
```


A tag used to record fractions of seconds for the DateTimeOriginal tag.

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final TiffTagID SubsecTimeDigitized
```


A tag used to record fractions of seconds for the DateTimeDigitized tag.

### ExposureTime {#ExposureTime}
```
public static final TiffTagID ExposureTime
```


Exposure time, given in seconds (sec).

### FNumber {#FNumber}
```
public static final TiffTagID FNumber
```


The F number.

### ExposureProgram {#ExposureProgram}
```
public static final TiffTagID ExposureProgram
```


The class of the program used by the camera to set exposure when the picture is taken.

### SpectralSensitivity {#SpectralSensitivity}
```
public static final TiffTagID SpectralSensitivity
```


Indicates the spectral sensitivity of each channel of the camera used. The tag value is an ASCII string compatible with the standard developed by the ASTM Technical committee.

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final TiffTagID PhotographicSensitivity
```


This tag indicates the sensitivity of the camera or input device when the image was shot.

### Oecf {#Oecf}
```
public static final TiffTagID Oecf
```


Indicates the Opto-Electric Conversion Function (OECF) specified in ISO 14524. OECF is the relationship between the camera optical input and the image values.

### SensitivityType {#SensitivityType}
```
public static final TiffTagID SensitivityType
```


The SensitivityType tag indicates which one of the parameters of ISO12232 is the PhotographicSensitivity tag. Although it is an optional tag, it should be recorded when a PhotographicSensitivity tag is recorded.

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final TiffTagID StandardOutputSensitivity
```


This tag indicates the standard output sensitivity value of a camera or input device defined in ISO 12232. When recording this tag, the PhotographicSensitivity and SensitivityType tags shall also be recorded.

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final TiffTagID RecommendedExposureIndex
```


This tag indicates the recommended exposure index value of a camera or input device defined in ISO 12232. When recording this tag, the PhotographicSensitivity and SensitivityType tags shall also be recorded.

### IsoSpeed {#IsoSpeed}
```
public static final TiffTagID IsoSpeed
```


This tag indicates the ISO speed value of a camera or input device that is defined in ISO 12232. When recording this tag, the PhotographicSensitivity and SensitivityType tags shall also be recorded.

### ISOSpeedLatitudeYyy {#ISOSpeedLatitudeYyy}
```
public static final TiffTagID ISOSpeedLatitudeYyy
```


This tag indicates the ISO speed latitude yyy value of a camera or input device that is defined in ISO 12232.

### ISOSpeedLatitudeZzz {#ISOSpeedLatitudeZzz}
```
public static final TiffTagID ISOSpeedLatitudeZzz
```


This tag indicates the ISO speed latitude zzz value of a camera or input device that is defined in ISO 12232.

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final TiffTagID ShutterSpeedValue
```


Shutter speed. The unit is the APEX (Additive System of Photographic Exposure) setting.

### ApertureValue {#ApertureValue}
```
public static final TiffTagID ApertureValue
```


The lens aperture. The unit is the APEX value.

### BrightnessValue {#BrightnessValue}
```
public static final TiffTagID BrightnessValue
```


The value of brightness. The unit is the APEX value.

### ExposureBiasValue {#ExposureBiasValue}
```
public static final TiffTagID ExposureBiasValue
```


The exposure bias. The unit is the APEX value.

### MaxApertureValue {#MaxApertureValue}
```
public static final TiffTagID MaxApertureValue
```


The smallest F number of the lens. The unit is the APEX value.

### SubjectDistance {#SubjectDistance}
```
public static final TiffTagID SubjectDistance
```


The distance to the subject, given in meters.

### MeteringMode {#MeteringMode}
```
public static final TiffTagID MeteringMode
```


The metering mode.

### LightSource {#LightSource}
```
public static final TiffTagID LightSource
```


The kind of light source.

### Flash {#Flash}
```
public static final TiffTagID Flash
```


This tag indicates the status of flash when the image was shot. Bit 0 indicates the flash firing status, bits 1 and 2 indicate the flash return status, bits 3 and 4 indicate the flash mode, bit 5 indicates whether the flash function is present, and bit 6 indicates "red eye" mode.

### SubjectArea {#SubjectArea}
```
public static final TiffTagID SubjectArea
```


This tag indicates the location and area of the main subject in the overall scene.

### FocalLength {#FocalLength}
```
public static final TiffTagID FocalLength
```


The actual focal length of the lens, in mm. Conversion is not made to the focal length of a 35 mm film camera.

### FlashEnergy {#FlashEnergy}
```
public static final TiffTagID FlashEnergy
```


Indicates the strobe energy at the time the image is captured, as measured in Beam Candle Power Seconds (BCPS).

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final TiffTagID SpatialFrequencyResponse
```


This tag records the camera or input device spatial frequency table and SFR values in the direction of image width, image height, and diagonal direction, as specified in ISO 12233.

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final TiffTagID FocalPlaneXResolution
```


Indicates the number of pixels in the image width (X) direction per FocalPlaneResolutionUnit on the camera focal plane.

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final TiffTagID FocalPlaneYResolution
```


Indicates the number of pixels in the image height (Y) direction per FocalPlaneResolutionUnit on the camera focal plane.

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final TiffTagID FocalPlaneResolutionUnit
```


Indicates the unit for measuring FocalPlaneXResolution and FocalPlaneYResolution. This value is the same as the ResolutionUnit.

### SubjectLocation {#SubjectLocation}
```
public static final TiffTagID SubjectLocation
```


Indicates the location of the main subject in the scene. The value of this tag represents the pixel at the center of the main subject relative to the left edge, prior to rotation processing as per the Rotation tag. The first value indicates the X column number and second indicates the Y row number.

### ExposureIndex {#ExposureIndex}
```
public static final TiffTagID ExposureIndex
```


Indicates the exposure index selected on the camera or input device at the time the image is captured.

### SensingMethod {#SensingMethod}
```
public static final TiffTagID SensingMethod
```


Indicates the image sensor type on the camera or input device.

### FileSource {#FileSource}
```
public static final TiffTagID FileSource
```


Indicates the image source. If a DSC recorded the image, this tag value always shall be set to 3.

### SceneType {#SceneType}
```
public static final TiffTagID SceneType
```


Indicates the type of scene. If a DSC recorded the image, this tag value shall always be set to 1, indicating that the image was directly photographed.

### CustomRendered {#CustomRendered}
```
public static final TiffTagID CustomRendered
```


This tag indicates the use of special processing on image data, such as rendering geared to output.

### ExposureMode {#ExposureMode}
```
public static final TiffTagID ExposureMode
```


This tag indicates the exposure mode set when the image was shot. In auto-bracketing mode, the camera shoots a series of frames of the same scene at different exposure settings.

### WhiteBalance {#WhiteBalance}
```
public static final TiffTagID WhiteBalance
```


This tag indicates the white balance mode set when the image was shot.

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final TiffTagID DigitalZoomRatio
```


This tag indicates the digital zoom ratio when the image was shot. If the numerator of the recorded value is 0, this indicates that digital zoom was not used.

### FocalLengthIn35mmFilm {#FocalLengthIn35mmFilm}
```
public static final TiffTagID FocalLengthIn35mmFilm
```


This tag indicates the equivalent focal length assuming a 35mm film camera, in mm. A value of 0 means the focal length is unknown. Note that this tag differs from the FocalLength tag.

### GainControl {#GainControl}
```
public static final TiffTagID GainControl
```


This tag indicates the degree of overall image gain adjustment.

### Contrast {#Contrast}
```
public static final TiffTagID Contrast
```


This tag indicates the direction of contrast processing applied by the camera when the image was shot.

### Saturation {#Saturation}
```
public static final TiffTagID Saturation
```


This tag indicates the direction of saturation processing applied by the camera when the image was shot.

### Sharpness {#Sharpness}
```
public static final TiffTagID Sharpness
```


This tag indicates the direction of sharpness processing applied by the camera when the image was shot.

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final TiffTagID DeviceSettingDescription
```


This tag indicates information on the picture-taking conditions of a particular camera model.

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final TiffTagID SubjectDistanceRange
```


This tag indicates the distance to the subject.

### CompositeImage {#CompositeImage}
```
public static final TiffTagID CompositeImage
```


This tag indicates whether the recorded image is a composite image\* or not.

### SourceImageNumberOfCompositeImage {#SourceImageNumberOfCompositeImage}
```
public static final TiffTagID SourceImageNumberOfCompositeImage
```


This tag indicates the number of the source images (tentatively recorded images) captured for a composite Image.

### SourceExposureTimesOfCompositeImage {#SourceExposureTimesOfCompositeImage}
```
public static final TiffTagID SourceExposureTimesOfCompositeImage
```


For a composite image, this tag records the parameters relating exposure time of the exposures for generating the said composite image, such as respective exposure times of captured source images (tentatively recorded images).

### Temperature {#Temperature}
```
public static final TiffTagID Temperature
```


Temperature as the ambient situation at the shot, for example the room temperature where the photographer was holding the camera. The unit is °C.

### Humidity {#Humidity}
```
public static final TiffTagID Humidity
```


Humidity as the ambient situation at the shot, for example the room humidity where the photographer was holding the camera. The unit is %.

### Pressure {#Pressure}
```
public static final TiffTagID Pressure
```


Pressure as the ambient situation at the shot, for example the room atmospfere where the photographer was holding the camera or the water pressure under the sea. The unit is hPa.

### WaterDepth {#WaterDepth}
```
public static final TiffTagID WaterDepth
```


Water depth as the ambient situation at the shot, for example the water depth of the camera at underwater photography. The unit is m.

### Acceleration {#Acceleration}
```
public static final TiffTagID Acceleration
```


Acceleration (a scalar regardless of direction) as the ambient situation at the shot, for example the driving acceleration of the vehicle which the photographer rode on at the shot. The unit is mGal (10-5 m/s2).

### CameraElevationAngle {#CameraElevationAngle}
```
public static final TiffTagID CameraElevationAngle
```


Elevation/depression. angle of the orientation of the camera(imaging optical axis) as the ambient situation at the shot. The unit is degree(°).

### ImageUniqueID {#ImageUniqueID}
```
public static final TiffTagID ImageUniqueID
```


This tag indicates an identifier assigned uniquely to each image.

### LensSpecification {#LensSpecification}
```
public static final TiffTagID LensSpecification
```


This tag notes minimum focal length, maximum focal length, minimum F number in the minimum focal length, and minimum F number in the maximum focal length, which are specification information for the lens that was used in photography.

### LensMake {#LensMake}
```
public static final TiffTagID LensMake
```


This tag records the lens manufacturer as an ASCII string.

### LensModel {#LensModel}
```
public static final TiffTagID LensModel
```


This tag records the lens\\u2019s model name and model number as an ASCII string.

### LensSerialNumber {#LensSerialNumber}
```
public static final TiffTagID LensSerialNumber
```


This tag records the serial number of the interchangeable lens that was used in photography as an ASCII string.

### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static TiffTagID getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[TiffTagID](../../com.groupdocs.metadata.core/tifftagid)
### getFirst() {#getFirst--}
```
public static IEnumValue getFirst()
```




**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getAllValues() {#getAllValues--}
```
public Object[] getAllValues()
```


Returns the array of all values defined in the class.

**Returns:**
java.lang.Object[]
### values() {#values--}
```
public static Iterable<TiffTagID> values()
```




**Returns:**
java.lang.Iterable<com.groupdocs.metadata.core.TiffTagID>
### getEnumValueByRawValue(int rawValue) {#getEnumValueByRawValue-int-}
```
public IEnumValue getEnumValueByRawValue(int rawValue)
```


Returns the enumeration value by the raw value associated with it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getEnumValueByName(String name) {#getEnumValueByName-java.lang.String-}
```
public IEnumValue getEnumValueByName(String name)
```


Returns the enumeration value by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getRawValueType() {#getRawValueType--}
```
public RawIntegerType getRawValueType()
```


Returns the underlying type of the raw value of this enumeration value.

**Returns:**
[RawIntegerType](../../com.groupdocs.metadata.core/rawintegertype)
### getRawValue() {#getRawValue--}
```
public int getRawValue()
```


Returns the raw value of this enumeration value.

**Returns:**
int
### name() {#name--}
```
public String name()
```


Returns the name of this enumeration value.

**Returns:**
java.lang.String
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
