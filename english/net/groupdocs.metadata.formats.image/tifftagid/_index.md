---
title: TiffTagID
second_title: GroupDocs.Metadata for .NET API Reference
description: Defines ids of TIFF tags.
type: docs
weight: 2280
url: /net/groupdocs.metadata.formats.image/tifftagid/
---
## TiffTagID enumeration

Defines ids of TIFF tags.

```csharp
public enum TiffTagID : ushort
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| GpsVersionID | `0` | Indicates the version of GPSInfoIFD. |
| GpsLatitudeRef | `1` | Indicates whether the latitude is north or south latitude. |
| GpsLatitude | `2` | Indicates the latitude. |
| GpsLongitudeRef | `3` | Indicates whether the longitude is east or west longitude. |
| GpsLongitude | `4` | Indicates the longitude. |
| GpsAltitudeRef | `5` | Indicates the altitude used as the reference altitude. |
| GpsAltitude | `6` | Indicates the altitude based on the reference in GPSAltitudeRef. |
| GpsTimeStamp | `7` | Indicates the time as UTC (Coordinated Universal Time). |
| GpsSatellites | `8` | ndicates the GPS satellites used for measurements. |
| GpsStatus | `9` | Indicates the status of the GPS receiver when the image is recorded. |
| GpsMeasureMode | `10` | Indicates the GPS measurement mode. |
| GpsDop | `11` | Indicates the GPS DOP (data degree of precision). |
| GpsSpeedRef | `12` | Indicates the unit used to express the GPS receiver speed of movement |
| GpsSpeed | `13` | Indicates the speed of GPS receiver movement. |
| GpsTrackRef | `14` | Indicates the reference for giving the direction of GPS receiver movement. |
| GpsTrack | `15` | Indicates the direction of GPS receiver movement. |
| GpsImgDirectionRef | `16` | Indicates the reference for giving the direction of the image when it is captured. |
| GpsImgDirection | `17` | Indicates the direction of the image when it was captured. |
| GpsMapDatum | `18` | Indicates the geodetic survey data used by the GPS receiver. |
| GpsDestLatitudeRef | `19` | Indicates whether the latitude of the destination point is north or south latitude. |
| GpsDestLatitude | `20` | Indicates the latitude of the destination point. |
| GpsDestLongitudeRef | `21` | Indicates whether the longitude of the destination point is east or west longitude. |
| GpsDestLongitude | `22` | Indicates the longitude of the destination point. |
| GpsDestBearingRef | `23` | Indicates the reference used for giving the bearing to the destination point. |
| GpsDestBearing | `24` | Indicates the bearing to the destination point. |
| GpsDestDistanceRef | `25` | Indicates the unit used to express the distance to the destination point. |
| GpsDestDistance | `26` | Indicates the distance to the destination point. |
| GpsProcessingMethod | `27` | A character string recording the name of the method used for location finding. |
| GpsAreaInformation | `28` | A character string recording the name of the GPS area. |
| GpsDateStamp | `29` | A character string recording date and time information relative to UTC (Coordinated Universal Time). |
| GpsDifferential | `30` | Indicates whether differential correction is applied to the GPS receiver. |
| GpsHPositioningError | `31` | This tag indicates horizontal positioning errors in meters. |
| NewSubfileType | `254` | A general indication of the kind of data contained in this sub-file. |
| SubfileType | `255` | A general indication of the kind of data contained in this subfile. This field is deprecated. The NewSubfileType field should be used instead |
| ImageWidth | `256` | The number of columns in the image, i.e., the number of pixels per scan line. |
| ImageLength | `257` | The number of rows (sometimes described as scan lines) in the image. |
| BitsPerSample | `258` | Number of bits per component. |
| Compression | `259` | Compression scheme used on the image data. |
| PhotometricInterpretation | `262` | The color space of the image data. |
| Threshholding | `263` | For black and white TIFF files that represent shades of gray, the technique used to convert from gray to black and white pixels. |
| CellWidth | `264` | The width of the dithering or halftoning matrix used to create a dithered or halftoned bi-level file. |
| CellLength | `265` | The length of the dithering or halftoning matrix used to create a dithered or halftoned bi-level file. |
| FillOrder | `266` | The logical order of bits within a byte. |
| DocumentName | `269` | The name of the document from which this image was scanned. |
| ImageDescription | `270` | A string that describes the subject of the image. |
| Make | `271` | The scanner manufacturer. |
| Model | `272` | The scanner model name or number. |
| StripOffsets | `273` | For each strip, the byte offset of that strip. |
| Orientation | `274` | The orientation of the image with respect to the rows and columns. |
| SamplesPerPixel | `277` | The number of components per pixel. |
| RowsPerStrip | `278` | The number of rows per strip. |
| StripByteCounts | `279` | For each strip, the number of bytes in the strip after compression. |
| MinSampleValue | `280` | The minimum component value used. |
| MaxSampleValue | `281` | The maximum component value used. |
| XResolution | `282` | The number of pixels per ResolutionUnit in the ImageWidth direction. |
| YResolution | `283` | The number of pixels per ResolutionUnit in the ImageLength direction. |
| PlanarConfiguration | `284` | How the components of each pixel are stored. |
| PageName | `285` | The name of the page from which this image was scanned. |
| XPosition | `286` | X position of the image. |
| YPosition | `287` | Y position of the image. |
| FreeOffsets | `288` | For each string of contiguous unused bytes in a TIFF file, the byte offset of the string. |
| FreeByteCounts | `289` | For each string of contiguous unused bytes in a TIFF file, the number of bytes in the string. |
| GrayResponseUnit | `290` | The precision of the information contained in the GrayResponseCurve. |
| GrayResponseCurve | `291` | For grayscale data, the optical density of each possible pixel value. |
| T4Options | `292` | T4-encoding options. |
| T6Options | `293` | T6-encoding options. |
| ResolutionUnit | `296` | The unit of measurement for XResolution and YResolution. |
| PageNumber | `297` | The page number of the page from which this image was scanned. |
| TransferFunction | `301` | Describes a transfer function for the image in tabular style. Pixel components can be gamma-compensated, companded, non-uniformly quantized, or coded in some other way. The TransferFunction maps the pixel components from a non-linear BitsPerSample (e.g. 8-bit) form into a 16-bit linear form without a perceptible loss of accuracy. |
| Software | `305` | Name and version number of the software package(s) used to create the image. |
| DateTime | `306` | Date and time of image creation. |
| Artist | `315` | Person who created the image. |
| HostComputer | `316` | The computer and/or operating system in use at the time of image creation. |
| Predictor | `317` | This section defines a Predictor that greatly improves compression ratios for some images. |
| WhitePoint | `318` | The chromaticity of the white point of the image. |
| PrimaryChromaticities | `319` | The chromaticities of the primaries of the image. |
| ColorMap | `320` | A color map for palette color images. |
| HalftoneHints | `321` | The purpose of the HalftoneHints field is to convey to the halftone function the range of gray levels within a colorimetrically-specified image that should retain tonal detail. |
| TileWidth | `322` | The tile width in pixels. This is the number of columns in each tile. |
| TileLength | `323` | The tile length (height) in pixels. This is the number of rows in each tile. |
| TileOffsets | `324` | For each tile, the byte offset of that tile, as compressed and stored on disk. The offset is specified with respect to the beginning of the TIFF file. Note that this implies that each tile has a location independent of the locations of other tiles. |
| TileByteCounts | `325` | For each tile, the number of (compressed) bytes in that tile. |
| InkSet | `332` | The set of inks used in a separated (PhotometricInterpretation=5) image. |
| InkNames | `333` | The name of each ink used in a separated (PhotometricInterpretation=5) image, written as a list of concatenated, NUL-terminated ASCII strings. |
| NumberOfInks | `334` | The number of inks. Usually equal to SamplesPerPixel, unless there are extra samples. |
| DotRange | `336` | The component values that correspond to a 0% dot and 100% dot. DotRange[0] corresponds to a 0% dot, and DotRange[1] corresponds to a 100% dot. |
| ExtraSamples | `338` | Description of extra components. |
| SampleFormat | `339` | This field specifies how to interpret each data sample in a pixel. |
| SMinSampleValue | `340` | This field specifies the minimum sample value. |
| SMaxSampleValue | `341` | This new field specifies the maximum sample value. |
| TransferRange | `342` | Expands the range of the TransferFunction. |
| JpegProc | `512` | This Field indicates the JPEG process used to produce the compressed data. |
| JpegInterchangeFormat | `513` | This Field indicates whether a JPEG interchange format bitstream is present in the TIFF file. |
| JpegInterchangeFormatLength | `514` | This Field indicates the length in bytes of the JPEG interchange format bitstream |
| JpegRestartInterval | `515` | This Field indicates the length of the restart interval used in the compressed image data. |
| JpegLosslessPredictors | `517` | This Field points to a list of lossless predictor-selection values, one per component. |
| JpegPointTransforms | `518` | This Field points to a list of point transform values, one per component. |
| JpegQTables | `519` | This Field points to a list of offsets to the quantization tables, one per component. |
| JpegDCTables | `520` | This Field points to a list of offsets to the DC Huffman tables or the lossless Huffman tables, one per component. |
| JpegACTables | `521` | This Field points to a list of offsets to the Huffman AC tables, one per component. |
| YCbCrCoefficients | `529` | The matrix cofficients for transformation from RGB to YCbCr image data. |
| YCbCrSubSampling | `530` | The sampling ratio of chrominance components in relation to the luminance component. |
| YCbCrPositioning | `531` | Specifies the positioning of subsampled chrominance components relative to luminance samples. |
| ReferenceBlackWhite | `532` | Specifies a pair of headroom and footroom image data values (codes) for each pixel component. |
| Copyright | `33432` | Copyright notice. |
| UserComment | `37510` | Keywords or comments on the image; complements ImageDescription. |
| Xmp | `700` | Pointer to the XMP metadata. |
| ImageID | `32781` | OPI-related. |
| Iptc | `33723` | IPTC (International Press Telecommunications Council) metadata. Often times, the data type is incorrectly specified as LONG. |
| Photoshop | `34377` | Collection of Photoshop 'Image Resource Blocks'. |
| ImageLayer | `34732` | Image layer. |
| IccProfile | `34675` | Color profile data. |
| ExifIfd | `34665` | Pointer to collection of all EXIF Metadata. EXIF uses field names rather than tags to indicate the field content. |
| GpsIfd | `34853` | Pointer to GPS data. |
| Makernotes | `37500` | Pointer to makernotes data. |
| InteroperabilityIfd | `40965` | Exif-related Interoperability IFD. |
| CameraOwnerName | `42032` | Camera owner name as ASCII string. |
| BodySerialNumber | `42033` | Camera body serial number as ASCII string. |
| CfaPattern | `41730` | ndicates the color filter array (CFA) geometric pattern of the image sensor when a one-chip color area sensor is used. It does not apply to all sensing methods. |
| ExifVersion | `36864` | The version of the EXIF standard supported. |
| ComponentsConfiguration | `37121` | Information specific to the compressed data. The channels of each component are arranged in order from the 1st component to the 4th. |
| FlashpixVersion | `40960` | The Flashpix format version supported by a FPXR file. If the FPXR function supports Flashpix format Ver. 1.0, this is indicated similarly to ExifVersion by recording "0100" as 4-byte ASCII. |
| ColorSpace | `40961` | The color space information tag (ColorSpace) is always recorded as the color space specifier. Normally sRGB (=1) is used to define the color space based on the PC monitor conditions and environment. If a color space other than sRGB is used, Uncalibrated (=FFFF.H) is set. |
| PixelXDimension | `40962` | Information specific to compressed data. When a compressed file is recorded, the valid width of the meaningful image shall be recorded in this tag, whether or not there is padding data or a restart marker. |
| PixelYDimension | `40963` | Information specific to compressed data. When a compressed file is recorded, the valid height of the meaningful image shall be recorded in this tag, whether or not there is padding data or a restart marker. |
| SceneCaptureType | `41990` | This tag indicates the type of scene that was shot. It may also be used to record the mode in which the image was shot. |
| Gamma | `42240` | Indicates the value of coefficient gamma. |
| CompressedBitsPerPixel | `37122` | Information specific to compressed data. The compression mode used for a compressed image is indicated in unit bits per pixel. |
| RelatedSoundFile | `40964` | This tag is used to record the name of an audio file related to the image data. The only relational information recorded here is the Exif audio file name and extension (an ASCII string consisting of 8 characters + '.' + 3 characters). |
| DateTimeOriginal | `36867` | The date and time when the original image data was generated. For a DSC the date and time the picture was taken are recorded. The format is "YYYY:MM:DD HH:MM:SS" with time shown in 24-hour format, and the date and time separated by one blank character. |
| DateTimeDigitized | `36868` | The date and time when the image was stored as digital data. If, for example, an image was captured by DSC and at the same time the file was recorded, then the DateTimeOriginal and DateTimeDigitized will have the same contents. The format is "YYYY:MM:DD HH:MM:SS" with time shown in 24-hour format, and the date and time separated by one blank character. |
| OffsetTime | `36880` | A tag used to record the offset from UTC (the time difference from Universal Time Coordinated including daylight saving time) of the time of DateTime tag. The format when recording the offset is "±HH:MM". The part of "±" shall be recorded as "+" or "-". |
| OffsetTimeOriginal | `36881` | A tag used to record the offset from UTC (the time difference from Universal Time Coordinated including daylight saving time) of the time of DateTimeOriginal tag. The format when recording the offset is "±HH:MM". The part of "±" shall be recorded as "+" or "-". |
| OffsetTimeDigitized | `36882` | A tag used to record the offset from UTC (the time difference from Universal Time Coordinated including daylight saving time) of the time of DateTimeDigitized tag. The format when recording the offset is "±HH:MM". The part of "±" shall be recorded as "+" or "-". |
| SubsecTime | `37520` | A tag used to record fractions of seconds for the DateTime tag. |
| SubsecTimeOriginal | `37521` | A tag used to record fractions of seconds for the DateTimeOriginal tag. |
| SubsecTimeDigitized | `37522` | A tag used to record fractions of seconds for the DateTimeDigitized tag. |
| ExposureTime | `33434` | Exposure time, given in seconds (sec). |
| FNumber | `33437` | The F number. |
| ExposureProgram | `34850` | The class of the program used by the camera to set exposure when the picture is taken. |
| SpectralSensitivity | `34852` | Indicates the spectral sensitivity of each channel of the camera used. The tag value is an ASCII string compatible with the standard developed by the ASTM Technical committee. |
| PhotographicSensitivity | `34855` | This tag indicates the sensitivity of the camera or input device when the image was shot. |
| Oecf | `34856` | Indicates the Opto-Electric Conversion Function (OECF) specified in ISO 14524. OECF is the relationship between the camera optical input and the image values. |
| SensitivityType | `34864` | The SensitivityType tag indicates which one of the parameters of ISO12232 is the PhotographicSensitivity tag. Although it is an optional tag, it should be recorded when a PhotographicSensitivity tag is recorded. |
| StandardOutputSensitivity | `34865` | This tag indicates the standard output sensitivity value of a camera or input device defined in ISO 12232. When recording this tag, the PhotographicSensitivity and SensitivityType tags shall also be recorded. |
| RecommendedExposureIndex | `34866` | This tag indicates the recommended exposure index value of a camera or input device defined in ISO 12232. When recording this tag, the PhotographicSensitivity and SensitivityType tags shall also be recorded. |
| IsoSpeed | `34867` | This tag indicates the ISO speed value of a camera or input device that is defined in ISO 12232. When recording this tag, the PhotographicSensitivity and SensitivityType tags shall also be recorded. |
| ISOSpeedLatitudeYyy | `34868` | This tag indicates the ISO speed latitude yyy value of a camera or input device that is defined in ISO 12232. |
| ISOSpeedLatitudeZzz | `34869` | This tag indicates the ISO speed latitude zzz value of a camera or input device that is defined in ISO 12232. |
| ShutterSpeedValue | `37377` | Shutter speed. The unit is the APEX (Additive System of Photographic Exposure) setting. |
| ApertureValue | `37378` | The lens aperture. The unit is the APEX value. |
| BrightnessValue | `37379` | The value of brightness. The unit is the APEX value. |
| ExposureBiasValue | `37380` | The exposure bias. The unit is the APEX value. |
| MaxApertureValue | `37381` | The smallest F number of the lens. The unit is the APEX value. |
| SubjectDistance | `37382` | The distance to the subject, given in meters. |
| MeteringMode | `37383` | The metering mode. |
| LightSource | `37384` | The kind of light source. |
| Flash | `37385` | This tag indicates the status of flash when the image was shot. Bit 0 indicates the flash firing status, bits 1 and 2 indicate the flash return status, bits 3 and 4 indicate the flash mode, bit 5 indicates whether the flash function is present, and bit 6 indicates "red eye" mode. |
| SubjectArea | `37396` | This tag indicates the location and area of the main subject in the overall scene. |
| FocalLength | `37386` | The actual focal length of the lens, in mm. Conversion is not made to the focal length of a 35 mm film camera. |
| FlashEnergy | `41483` | Indicates the strobe energy at the time the image is captured, as measured in Beam Candle Power Seconds (BCPS). |
| SpatialFrequencyResponse | `41484` | This tag records the camera or input device spatial frequency table and SFR values in the direction of image width, image height, and diagonal direction, as specified in ISO 12233. |
| FocalPlaneXResolution | `41486` | Indicates the number of pixels in the image width (X) direction per FocalPlaneResolutionUnit on the camera focal plane. |
| FocalPlaneYResolution | `41487` | Indicates the number of pixels in the image height (Y) direction per FocalPlaneResolutionUnit on the camera focal plane. |
| FocalPlaneResolutionUnit | `41488` | Indicates the unit for measuring FocalPlaneXResolution and FocalPlaneYResolution. This value is the same as the ResolutionUnit. |
| SubjectLocation | `41492` | Indicates the location of the main subject in the scene. The value of this tag represents the pixel at the center of the main subject relative to the left edge, prior to rotation processing as per the Rotation tag. The first value indicates the X column number and second indicates the Y row number. |
| ExposureIndex | `41493` | Indicates the exposure index selected on the camera or input device at the time the image is captured. |
| SensingMethod | `41495` | Indicates the image sensor type on the camera or input device. |
| FileSource | `41728` | Indicates the image source. If a DSC recorded the image, this tag value always shall be set to 3. |
| SceneType | `41729` | Indicates the type of scene. If a DSC recorded the image, this tag value shall always be set to 1, indicating that the image was directly photographed. |
| CustomRendered | `41985` | This tag indicates the use of special processing on image data, such as rendering geared to output. |
| ExposureMode | `41986` | This tag indicates the exposure mode set when the image was shot. In auto-bracketing mode, the camera shoots a series of frames of the same scene at different exposure settings. |
| WhiteBalance | `41987` | This tag indicates the white balance mode set when the image was shot. |
| DigitalZoomRatio | `41988` | This tag indicates the digital zoom ratio when the image was shot. If the numerator of the recorded value is 0, this indicates that digital zoom was not used. |
| FocalLengthIn35mmFilm | `41989` | This tag indicates the equivalent focal length assuming a 35mm film camera, in mm. A value of 0 means the focal length is unknown. Note that this tag differs from the FocalLength tag. |
| GainControl | `41991` | This tag indicates the degree of overall image gain adjustment. |
| Contrast | `41992` | This tag indicates the direction of contrast processing applied by the camera when the image was shot. |
| Saturation | `41993` | This tag indicates the direction of saturation processing applied by the camera when the image was shot. |
| Sharpness | `41994` | This tag indicates the direction of sharpness processing applied by the camera when the image was shot. |
| DeviceSettingDescription | `41995` | This tag indicates information on the picture-taking conditions of a particular camera model. |
| SubjectDistanceRange | `41996` | This tag indicates the distance to the subject. |
| CompositeImage | `42080` | This tag indicates whether the recorded image is a composite image* or not. |
| SourceImageNumberOfCompositeImage | `42081` | This tag indicates the number of the source images (tentatively recorded images) captured for a composite Image. |
| SourceExposureTimesOfCompositeImage | `42082` | For a composite image, this tag records the parameters relating exposure time of the exposures for generating the said composite image, such as respective exposure times of captured source images (tentatively recorded images). |
| Temperature | `37888` | Temperature as the ambient situation at the shot, for example the room temperature where the photographer was holding the camera. The unit is °C. |
| Humidity | `37889` | Humidity as the ambient situation at the shot, for example the room humidity where the photographer was holding the camera. The unit is %. |
| Pressure | `37890` | Pressure as the ambient situation at the shot, for example the room atmospfere where the photographer was holding the camera or the water pressure under the sea. The unit is hPa. |
| WaterDepth | `37891` | Water depth as the ambient situation at the shot, for example the water depth of the camera at underwater photography. The unit is m. |
| Acceleration | `37892` | Acceleration (a scalar regardless of direction) as the ambient situation at the shot, for example the driving acceleration of the vehicle which the photographer rode on at the shot. The unit is mGal (10-5 m/s2). |
| CameraElevationAngle | `37893` | Elevation/depression. angle of the orientation of the camera(imaging optical axis) as the ambient situation at the shot. The unit is degree(°). |
| ImageUniqueID | `42016` | This tag indicates an identifier assigned uniquely to each image. |
| LensSpecification | `42034` | This tag notes minimum focal length, maximum focal length, minimum F number in the minimum focal length, and minimum F number in the maximum focal length, which are specification information for the lens that was used in photography. |
| LensMake | `42035` | This tag records the lens manufacturer as an ASCII string. |
| LensModel | `42036` | This tag records the lens’s model name and model number as an ASCII string. |
| LensSerialNumber | `42037` | This tag records the serial number of the interchangeable lens that was used in photography as an ASCII string. |

### See Also

* namespace [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
