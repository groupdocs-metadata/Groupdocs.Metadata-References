---
title: TiffTagID enumeration
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.image/tifftagid/
is_root: false
weight: 590
---

## TiffTagID enumeration

Defines ids of TIFF tags.



The TiffTagID type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| GPS_VERSION_ID | Indicates the version of GPSInfoIFD. |
| GPS_LATITUDE_REF | Indicates whether the latitude is north or south latitude. |
| GPS_LATITUDE | Indicates the latitude. |
| GPS_LONGITUDE_REF | Indicates whether the longitude is east or west longitude. |
| GPS_LONGITUDE | Indicates the longitude. |
| GPS_ALTITUDE_REF | Indicates the altitude used as the reference altitude. |
| GPS_ALTITUDE | Indicates the altitude based on the reference in GPSAltitudeRef. |
| GPS_TIME_STAMP | Indicates the time as UTC (Coordinated Universal Time). |
| GPS_SATELLITES | ndicates the GPS satellites used for measurements. |
| GPS_STATUS | Indicates the status of the GPS receiver when the image is recorded. |
| GPS_MEASURE_MODE | Indicates the GPS measurement mode. |
| GPS_DOP | Indicates the GPS DOP (data degree of precision). |
| GPS_SPEED_REF | Indicates the unit used to express the GPS receiver speed of movement |
| GPS_SPEED | Indicates the speed of GPS receiver movement. |
| GPS_TRACK_REF | Indicates the reference for giving the direction of GPS receiver movement. |
| GPS_TRACK | Indicates the direction of GPS receiver movement. |
| GPS_IMG_DIRECTION_REF | Indicates the reference for giving the direction of the image when it is captured. |
| GPS_IMG_DIRECTION | Indicates the direction of the image when it was captured. |
| GPS_MAP_DATUM | Indicates the geodetic survey data used by the GPS receiver. |
| GPS_DEST_LATITUDE_REF | Indicates whether the latitude of the destination point is north or south latitude. |
| GPS_DEST_LATITUDE | Indicates the latitude of the destination point. |
| GPS_DEST_LONGITUDE_REF | Indicates whether the longitude of the destination point is east or west longitude. |
| GPS_DEST_LONGITUDE | Indicates the longitude of the destination point. |
| GPS_DEST_BEARING_REF | Indicates the reference used for giving the bearing to the destination point. |
| GPS_DEST_BEARING | Indicates the bearing to the destination point. |
| GPS_DEST_DISTANCE_REF | Indicates the unit used to express the distance to the destination point. |
| GPS_DEST_DISTANCE | Indicates the distance to the destination point. |
| GPS_PROCESSING_METHOD | A character string recording the name of the method used for location finding. |
| GPS_AREA_INFORMATION | A character string recording the name of the GPS area. |
| GPS_DATE_STAMP | A character string recording date and time information relative to UTC (Coordinated Universal Time). |
| GPS_DIFFERENTIAL | Indicates whether differential correction is applied to the GPS receiver. |
| GPS_H_POSITIONING_ERROR | This tag indicates horizontal positioning errors in meters. |
| NEW_SUBFILE_TYPE | A general indication of the kind of data contained in this sub-file. |
| SUBFILE_TYPE | A general indication of the kind of data contained in this subfile.<br/>This field is deprecated. The NewSubfileType field should be used instead |
| IMAGE_WIDTH | The number of columns in the image, i.e., the number of pixels per scan line. |
| IMAGE_LENGTH | The number of rows (sometimes described as scan lines) in the image. |
| BITS_PER_SAMPLE | Number of bits per component. |
| COMPRESSION | Compression scheme used on the image data. |
| PHOTOMETRIC_INTERPRETATION | The color space of the image data. |
| THRESHHOLDING | For black and white TIFF files that represent shades of gray, the technique used to convert from gray to black and white pixels. |
| CELL_WIDTH | The width of the dithering or halftoning matrix used to create a dithered or <br/>halftoned bi-level file. |
| CELL_LENGTH | The length of the dithering or halftoning matrix used to create a dithered or <br/>halftoned bi-level file. |
| FILL_ORDER | The logical order of bits within a byte. |
| DOCUMENT_NAME | The name of the document from which this image was scanned. |
| IMAGE_DESCRIPTION | A string that describes the subject of the image. |
| MAKE | The scanner manufacturer. |
| MODEL | The scanner model name or number. |
| STRIP_OFFSETS | For each strip, the byte offset of that strip. |
| ORIENTATION | The orientation of the image with respect to the rows and columns. |
| SAMPLES_PER_PIXEL | The number of components per pixel. |
| ROWS_PER_STRIP | The number of rows per strip. |
| STRIP_BYTE_COUNTS | For each strip, the number of bytes in the strip after compression. |
| MIN_SAMPLE_VALUE | The minimum component value used. |
| MAX_SAMPLE_VALUE | The maximum component value used. |
| X_RESOLUTION | The number of pixels per ResolutionUnit in the ImageWidth direction. |
| Y_RESOLUTION | The number of pixels per ResolutionUnit in the ImageLength direction. |
| PLANAR_CONFIGURATION | How the components of each pixel are stored. |
| PAGE_NAME | The name of the page from which this image was scanned. |
| X_POSITION | X position of the image. |
| Y_POSITION | Y position of the image. |
| FREE_OFFSETS | For each string of contiguous unused bytes in a TIFF file, the byte offset of the string. |
| FREE_BYTE_COUNTS | For each string of contiguous unused bytes in a TIFF file, the number of bytes in the string. |
| GRAY_RESPONSE_UNIT | The precision of the information contained in the GrayResponseCurve. |
| GRAY_RESPONSE_CURVE | For grayscale data, the optical density of each possible pixel value. |
| T4_OPTIONS | T4-encoding options. |
| T6_OPTIONS | T6-encoding options. |
| RESOLUTION_UNIT | The unit of measurement for XResolution and YResolution. |
| PAGE_NUMBER | The page number of the page from which this image was scanned. |
| TRANSFER_FUNCTION | Describes a transfer function for the image in tabular style. Pixel components can<br/>be gamma-compensated, companded, non-uniformly quantized, or coded in some<br/>other way. The TransferFunction maps the pixel components from a non-linear<br/>BitsPerSample (e.g. 8-bit) form into a 16-bit linear form without a perceptible loss<br/>of accuracy. |
| SOFTWARE | Name and version number of the software package(s) used to create the image. |
| DATE_TIME | Date and time of image creation. |
| ARTIST | Person who created the image. |
| HOST_COMPUTER | The computer and/or operating system in use at the time of image creation. |
| PREDICTOR | This section defines a Predictor that greatly improves compression ratios for some images. |
| WHITE_POINT | The chromaticity of the white point of the image. |
| PRIMARY_CHROMATICITIES | The chromaticities of the primaries of the image. |
| COLOR_MAP | A color map for palette color images. |
| HALFTONE_HINTS | The purpose of the HalftoneHints field is to convey to the halftone function the<br/>range of gray levels within a colorimetrically-specified image that should retain<br/>tonal detail. |
| TILE_WIDTH | The tile width in pixels. This is the number of columns in each tile. |
| TILE_LENGTH | The tile length (height) in pixels. This is the number of rows in each tile. |
| TILE_OFFSETS | For each tile, the byte offset of that tile, as compressed and stored on disk. <br/>The offset is specified with respect to the beginning of the TIFF file. <br/>Note that this implies that each tile has a location independent of the locations of other tiles. |
| TILE_BYTE_COUNTS | For each tile, the number of (compressed) bytes in that tile. |
| INK_SET | The set of inks used in a separated (PhotometricInterpretation=5) image. |
| INK_NAMES | The name of each ink used in a separated (PhotometricInterpretation=5) image,<br/>written as a list of concatenated, NUL-terminated ASCII strings. |
| NUMBER_OF_INKS | The number of inks. Usually equal to SamplesPerPixel, unless there are extra samples. |
| DOT_RANGE | The component values that correspond to a 0% dot and 100% dot. DotRange[0]<br/>corresponds to a 0% dot, and DotRange[1] corresponds to a 100% dot. |
| EXTRA_SAMPLES | Description of extra components. |
| SAMPLE_FORMAT | This field specifies how to interpret each data sample in a pixel. |
| S_MIN_SAMPLE_VALUE | This field specifies the minimum sample value. |
| S_MAX_SAMPLE_VALUE | This new field specifies the maximum sample value. |
| TRANSFER_RANGE | Expands the range of the TransferFunction. |
| JPEG_PROC | This Field indicates the JPEG process used to produce the compressed data. |
| JPEG_INTERCHANGE_FORMAT | This Field indicates whether a JPEG interchange format bitstream is present in the TIFF file. |
| JPEG_INTERCHANGE_FORMAT_LENGTH | This Field indicates the length in bytes of the JPEG interchange format bitstream |
| JPEG_RESTART_INTERVAL | This Field indicates the length of the restart interval used in the compressed image data. |
| JPEG_LOSSLESS_PREDICTORS | This Field points to a list of lossless predictor-selection values, one per component. |
| JPEG_POINT_TRANSFORMS | This Field points to a list of point transform values, one per component. |
| JPEG_Q_TABLES | This Field points to a list of offsets to the quantization tables, one per component. |
| JPEG_DC_TABLES | This Field points to a list of offsets to the DC Huffman tables or the lossless<br/>Huffman tables, one per component. |
| JPEG_AC_TABLES | This Field points to a list of offsets to the Huffman AC tables, one per component. |
| Y_CB_CR_COEFFICIENTS | The matrix cofficients for transformation from RGB to YCbCr image data. |
| Y_CB_CR_SUB_SAMPLING | The sampling ratio of chrominance components in relation to the luminance component. |
| Y_CB_CR_POSITIONING | Specifies the positioning of subsampled chrominance components relative to luminance samples. |
| REFERENCE_BLACK_WHITE | Specifies a pair of headroom and footroom image data values (codes) for each pixel component. |
| COPYRIGHT | Copyright notice. |
| USER_COMMENT | Keywords or comments on the image; complements ImageDescription. |
| XMP | Pointer to the XMP metadata. |
| IMAGE_ID | OPI-related. |
| IPTC | IPTC (International Press Telecommunications Council) metadata.<br/>Often times, the data type is incorrectly specified as LONG. |
| PHOTOSHOP | Collection of Photoshop 'Image Resource Blocks'. |
| IMAGE_LAYER | Image layer. |
| ICC_PROFILE | Color profile data. |
| EXIF_IFD | Pointer to collection of all EXIF Metadata. <br/>EXIF uses field names rather than tags to indicate the field content. |
| GPS_IFD | Pointer to GPS data. |
| MAKERNOTES | Pointer to makernotes data. |
| INTEROPERABILITY_IFD | Exif-related Interoperability IFD. |
| CAMERA_OWNER_NAME | Camera owner name as ASCII string. |
| BODY_SERIAL_NUMBER | Camera body serial number as ASCII string. |
| CFA_PATTERN | ndicates the color filter array (CFA) geometric pattern of the image sensor when a one-chip color area sensor is used. It does not apply to all sensing methods. |
| EXIF_VERSION | The version of the EXIF standard supported. |
| COMPONENTS_CONFIGURATION | Information specific to the compressed data. The channels of each component are arranged in order from the 1st component to the 4th. |
| FLASHPIX_VERSION | The Flashpix format version supported by a FPXR file. If the FPXR function supports Flashpix format Ver. 1.0, this is indicated similarly to ExifVersion by recording "0100" as 4-byte ASCII. |
| COLOR_SPACE | The color space information tag (ColorSpace) is always recorded as the color space specifier. <br/>Normally sRGB (=1) is used to define the color space based on the PC monitor conditions and environment. <br/>If a color space other than sRGB is used, Uncalibrated (=FFFF.H) is set. |
| PIXEL_X_DIMENSION | Information specific to compressed data. When a compressed file is recorded, <br/>the valid width of the meaningful image shall be recorded in this tag, whether or not there is padding data or a restart marker. |
| PIXEL_Y_DIMENSION | Information specific to compressed data. When a compressed file is recorded, <br/>the valid height of the meaningful image shall be recorded in this tag, whether or not there is padding data or a restart marker. |
| SCENE_CAPTURE_TYPE | This tag indicates the type of scene that was shot. It may also be used to record the mode in which the image was shot. |
| GAMMA | Indicates the value of coefficient gamma. |
| COMPRESSED_BITS_PER_PIXEL | Information specific to compressed data. The compression mode used for a compressed image is indicated in unit bits per pixel. |
| RELATED_SOUND_FILE | This tag is used to record the name of an audio file related to the image data. <br/>The only relational information recorded here is the Exif audio file name and extension <br/>(an ASCII string consisting of 8 characters + '.' + 3 characters). |
| DATE_TIME_ORIGINAL | The date and time when the original image data was generated. <br/>For a DSC the date and time the picture was taken are recorded. <br/>The format is "YYYY:MM:DD HH:MM:SS" with time shown in 24-hour format, and the date and time separated by one blank character. |
| DATE_TIME_DIGITIZED | The date and time when the image was stored as digital data. <br/>If, for example, an image was captured by DSC and at the same time the file was recorded, then the DateTimeOriginal and DateTimeDigitized will have the same contents. <br/>The format is "YYYY:MM:DD HH:MM:SS" with time shown in 24-hour format, and the date and time separated by one blank character. |
| OFFSET_TIME | A tag used to record the offset from UTC (the time difference from Universal Time Coordinated including daylight saving time) of the time of DateTime tag. <br/>The format when recording the offset is "±HH:MM". <br/>The part of "±" shall be recorded as "+" or "-". |
| OFFSET_TIME_ORIGINAL | A tag used to record the offset from UTC (the time difference from Universal Time Coordinated including daylight saving time) of the time of DateTimeOriginal tag.<br/>The format when recording the offset is "±HH:MM". <br/>The part of "±" shall be recorded as "+" or "-". |
| OFFSET_TIME_DIGITIZED | A tag used to record the offset from UTC (the time difference from Universal Time Coordinated including daylight saving time) of the time of DateTimeDigitized tag. <br/>The format when recording the offset is "±HH:MM". <br/>The part of "±" shall be recorded as "+" or "-". |
| SUBSEC_TIME | A tag used to record fractions of seconds for the DateTime tag. |
| SUBSEC_TIME_ORIGINAL | A tag used to record fractions of seconds for the DateTimeOriginal tag. |
| SUBSEC_TIME_DIGITIZED | A tag used to record fractions of seconds for the DateTimeDigitized tag. |
| EXPOSURE_TIME | Exposure time, given in seconds (sec). |
| F_NUMBER | The F number. |
| EXPOSURE_PROGRAM | The class of the program used by the camera to set exposure when the picture is taken. |
| SPECTRAL_SENSITIVITY | Indicates the spectral sensitivity of each channel of the camera used. <br/>The tag value is an ASCII string compatible with the standard developed by the ASTM Technical committee. |
| PHOTOGRAPHIC_SENSITIVITY | This tag indicates the sensitivity of the camera or input device when the image was shot. |
| OECF | Indicates the Opto-Electric Conversion Function (OECF) specified in ISO 14524. <br/>OECF is the relationship between the camera optical input and the image values. |
| SENSITIVITY_TYPE | The SensitivityType tag indicates which one of the parameters of ISO12232 is the PhotographicSensitivity tag. <br/>Although it is an optional tag, it should be recorded when a PhotographicSensitivity tag is recorded. |
| STANDARD_OUTPUT_SENSITIVITY | This tag indicates the standard output sensitivity value of a camera or input device defined in ISO 12232. <br/>When recording this tag, the PhotographicSensitivity and SensitivityType tags shall also be recorded. |
| RECOMMENDED_EXPOSURE_INDEX | This tag indicates the recommended exposure index value of a camera or input device defined in ISO 12232. <br/>When recording this tag, the PhotographicSensitivity and SensitivityType tags shall also be recorded. |
| ISO_SPEED | This tag indicates the ISO speed value of a camera or input device that is defined in ISO 12232. <br/>When recording this tag, the PhotographicSensitivity and SensitivityType tags shall also be recorded. |
| ISO_SPEED_LATITUDE_YYY | This tag indicates the ISO speed latitude yyy value of a camera or input device that is defined in ISO 12232. |
| ISO_SPEED_LATITUDE_ZZZ | This tag indicates the ISO speed latitude zzz value of a camera or input device that is defined in ISO 12232. |
| SHUTTER_SPEED_VALUE | Shutter speed. The unit is the APEX (Additive System of Photographic Exposure) setting. |
| APERTURE_VALUE | The lens aperture. The unit is the APEX value. |
| BRIGHTNESS_VALUE | The value of brightness. The unit is the APEX value. |
| EXPOSURE_BIAS_VALUE | The exposure bias. The unit is the APEX value. |
| MAX_APERTURE_VALUE | The smallest F number of the lens. The unit is the APEX value. |
| SUBJECT_DISTANCE | The distance to the subject, given in meters. |
| METERING_MODE | The metering mode. |
| LIGHT_SOURCE | The kind of light source. |
| FLASH | This tag indicates the status of flash when the image was shot. <br/>Bit 0 indicates the flash firing status, bits 1 and 2 indicate the flash return status, <br/>bits 3 and 4 indicate the flash mode, bit 5 indicates whether the flash function is present, and bit 6 indicates "red eye" mode. |
| SUBJECT_AREA | This tag indicates the location and area of the main subject in the overall scene. |
| FOCAL_LENGTH | The actual focal length of the lens, in mm. Conversion is not made to the focal length of a 35 mm film camera. |
| FLASH_ENERGY | Indicates the strobe energy at the time the image is captured, as measured in Beam Candle Power Seconds (BCPS). |
| SPATIAL_FREQUENCY_RESPONSE | This tag records the camera or input device spatial frequency table and SFR values in the direction of image width, <br/>image height, and diagonal direction, as specified in ISO 12233. |
| FOCAL_PLANE_X_RESOLUTION | Indicates the number of pixels in the image width (X) direction per FocalPlaneResolutionUnit on the camera focal plane. |
| FOCAL_PLANE_Y_RESOLUTION | Indicates the number of pixels in the image height (Y) direction per FocalPlaneResolutionUnit on the camera focal plane. |
| FOCAL_PLANE_RESOLUTION_UNIT | Indicates the unit for measuring FocalPlaneXResolution and FocalPlaneYResolution. This value is the same as the ResolutionUnit. |
| SUBJECT_LOCATION | Indicates the location of the main subject in the scene. <br/>The value of this tag represents the pixel at the center of the main subject relative to the left edge, prior to rotation processing as per the Rotation tag. <br/>The first value indicates the X column number and second indicates the Y row number. |
| EXPOSURE_INDEX | Indicates the exposure index selected on the camera or input device at the time the image is captured. |
| SENSING_METHOD | Indicates the image sensor type on the camera or input device. |
| FILE_SOURCE | Indicates the image source. If a DSC recorded the image, this tag value always shall be set to 3. |
| SCENE_TYPE | Indicates the type of scene. If a DSC recorded the image, this tag value shall always be set to 1, indicating that the image was directly photographed. |
| CUSTOM_RENDERED | This tag indicates the use of special processing on image data, such as rendering geared to output. |
| EXPOSURE_MODE | This tag indicates the exposure mode set when the image was shot. In auto-bracketing mode, <br/>the camera shoots a series of frames of the same scene at different exposure settings. |
| WHITE_BALANCE | This tag indicates the white balance mode set when the image was shot. |
| DIGITAL_ZOOM_RATIO | This tag indicates the digital zoom ratio when the image was shot. <br/>If the numerator of the recorded value is 0, this indicates that digital zoom was not used. |
| FOCAL_LENGTH_IN_35MM_FILM | This tag indicates the equivalent focal length assuming a 35mm film camera, in mm. <br/>A value of 0 means the focal length is unknown. Note that this tag differs from the FocalLength tag. |
| GAIN_CONTROL | This tag indicates the degree of overall image gain adjustment. |
| CONTRAST | This tag indicates the direction of contrast processing applied by the camera when the image was shot. |
| SATURATION | This tag indicates the direction of saturation processing applied by the camera when the image was shot. |
| SHARPNESS | This tag indicates the direction of sharpness processing applied by the camera when the image was shot. |
| DEVICE_SETTING_DESCRIPTION | This tag indicates information on the picture-taking conditions of a particular camera model. |
| SUBJECT_DISTANCE_RANGE | This tag indicates the distance to the subject. |
| COMPOSITE_IMAGE | This tag indicates whether the recorded image is a composite image* or not. |
| SOURCE_IMAGE_NUMBER_OF_COMPOSITE_IMAGE | This tag indicates the number of the source images (tentatively recorded images) captured for a composite Image. |
| SOURCE_EXPOSURE_TIMES_OF_COMPOSITE_IMAGE | For a composite image, this tag records the parameters relating exposure time of the exposures for generating the said composite image, <br/>such as respective exposure times of captured source images (tentatively recorded images). |
| TEMPERATURE | Temperature as the ambient situation at the shot, for example the room temperature where the photographer was holding the camera. The unit is °C. |
| HUMIDITY | Humidity as the ambient situation at the shot, for example the room humidity where the photographer was holding the camera. The unit is %. |
| PRESSURE | Pressure as the ambient situation at the shot, <br/>for example the room atmospfere where the photographer was holding the camera or the water pressure under the sea. <br/>The unit is hPa. |
| WATER_DEPTH | Water depth as the ambient situation at the shot, for example the water depth of the camera at underwater photography. The unit is m. |
| ACCELERATION | Acceleration (a scalar regardless of direction) as the ambient situation at the shot, for example the driving acceleration of the vehicle which the photographer rode on at the shot. <br/>The unit is mGal (10-5 m/s2). |
| CAMERA_ELEVATION_ANGLE | Elevation/depression. angle of the orientation of the camera(imaging optical axis) as the ambient situation at the shot. The unit is degree(°). |
| IMAGE_UNIQUE_ID | This tag indicates an identifier assigned uniquely to each image. |
| LENS_SPECIFICATION | This tag notes minimum focal length, maximum focal length, minimum F number in the minimum focal length, <br/>and minimum F number in the maximum focal length, which are specification information for the lens that was used in photography. |
| LENS_MAKE | This tag records the lens manufacturer as an ASCII string. |
| LENS_MODEL | This tag records the lens’s model name and model number as an ASCII string. |
| LENS_SERIAL_NUMBER | This tag records the serial number of the interchangeable lens that was used in photography as an ASCII string. |



### See Also
* module [`groupdocs.metadata.formats.image`](..)
