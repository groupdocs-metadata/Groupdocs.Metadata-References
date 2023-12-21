---
title: ImageResourceID
second_title: GroupDocs.Signature for Java API Reference
description: Image resources standard ID numbers.
type: docs
weight: 126
url: /java/com.groupdocs.metadata.core/imageresourceid/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public final class ImageResourceID implements IEnumValue
```

Image resources standard ID numbers. Not all file formats use all ID's. Some information may be stored in other sections of the file.
## Fields

| Field | Description |
| --- | --- |
| [ResolutionInfo](#ResolutionInfo) | ResolutionInfo structure. |
| [NamesOfAlphaChannels](#NamesOfAlphaChannels) | Names of the alpha channels as a series of Pascal strings. |
| [Caption](#Caption) | The caption as a Pascal string. |
| [BorderInformation](#BorderInformation) | Border information. |
| [BackgroundColor](#BackgroundColor) | Background color. |
| [PrintFlags](#PrintFlags) | Print flags. |
| [Grayscale](#Grayscale) | Grayscale and multichannel halftoning information. |
| [ColorHalftoning](#ColorHalftoning) | Color halftoning information. |
| [DuotoneHalftoning](#DuotoneHalftoning) | Duotone halftoning information. |
| [GrayscaleFunction](#GrayscaleFunction) | Grayscale and multichannel transfer function. |
| [ColorTransferFunctions](#ColorTransferFunctions) | Color transfer functions. |
| [DuotoneTransferFunctions](#DuotoneTransferFunctions) | Duotone transfer functions. |
| [DuotoneImageInformation](#DuotoneImageInformation) | Duotone image information. |
| [EPSOptions](#EPSOptions) | EPS options. |
| [QuickMaskInformation](#QuickMaskInformation) | Quick Mask information. |
| [LayerStateInformation](#LayerStateInformation) | Layer state information. |
| [WorkingPath](#WorkingPath) | Working path (not saved). |
| [LayersGroupInformation](#LayersGroupInformation) | Layers group information. |
| [Iptc](#Iptc) | IPTC-NAA record. |
| [ImageModeForRawFormat](#ImageModeForRawFormat) | Image mode for raw format files. |
| [JpegQuality](#JpegQuality) | JPEG quality. |
| [GridAndGuidesInfoPhotoshop4](#GridAndGuidesInfoPhotoshop4) | Grid and guides information. |
| [ThumbnailResourcePhotoshop4](#ThumbnailResourcePhotoshop4) | Thumbnail resource for Photoshop 4.0 only. |
| [CopyrightFlagPhotoshop4](#CopyrightFlagPhotoshop4) | Copyright flag. |
| [UrlPhotoshop4](#UrlPhotoshop4) | URL. |
| [ThumbnailResourcePhotoshop5](#ThumbnailResourcePhotoshop5) | Thumbnail resource (supersedes resource 1033). |
| [GlobalAnglePhotoshop5](#GlobalAnglePhotoshop5) | Global Angle. |
| [IccProfilePhotoshop5](#IccProfilePhotoshop5) | (Photoshop 5.0) ICC Profile. |
| [WatermarkPhotoshop5](#WatermarkPhotoshop5) | Watermark. |
| [IccUntaggedProfilePhotoshop5](#IccUntaggedProfilePhotoshop5) | ICC Untagged Profile. |
| [TransparencyIndexPhotoshop6](#TransparencyIndexPhotoshop6) | Transparency Index. |
| [GlobalAltitudePhotoshop6](#GlobalAltitudePhotoshop6) | Global Altitude. |
| [SlicesPhotoshop6](#SlicesPhotoshop6) | Slices (Photoshop 6). |
| [WorkflowUrlPhotoshop6](#WorkflowUrlPhotoshop6) | Workflow URL. |
| [AlphaIdentifiersPhotoshop6](#AlphaIdentifiersPhotoshop6) | Alpha Identifiers. |
| [UrlListPhotoshop6](#UrlListPhotoshop6) | URL InternalList. |
| [VersionInfoPhotoshop6](#VersionInfoPhotoshop6) | Version Info. |
| [ExifData1Photoshop7](#ExifData1Photoshop7) | EXIF data 1,  see more . |
| [ExifData3Photoshop7](#ExifData3Photoshop7) |  EXIF data 3.  |
| [XmpPhotoshop7](#XmpPhotoshop7) | XMP metadata. |
| [CaptionDigestPhotoshop7](#CaptionDigestPhotoshop7) | Caption digest. |
| [PrintScalePhotoshop7](#PrintScalePhotoshop7) | Print scale. |
| [PixelAspectRatio](#PixelAspectRatio) | Pixel Aspect Ratio. |
| [LayerComps](#LayerComps) | Layer Comps. |
| [LayerSelectionIds](#LayerSelectionIds) | Layer Selection ID(s). |
| [PrintInfoCS2](#PrintInfoCS2) | Print info (Photoshop CS2). |
| [LayerGroupEnabledIdCS2](#LayerGroupEnabledIdCS2) | Layer Group(s) Enabled ID. |
| [ColorSamplersResourceCS3](#ColorSamplersResourceCS3) | Color samplers resource. |
| [MeasurementScaleCS3](#MeasurementScaleCS3) | Measurement Scale. |
| [TimelineInformationCS3](#TimelineInformationCS3) | Timeline Information. |
| [SheetDisclosureCS3](#SheetDisclosureCS3) | Sheet Disclosure. |
| [PrintInformationCS5](#PrintInformationCS5) | Print Information (Photoshop CS5). |
| [PrintStyleCS5](#PrintStyleCS5) | Print Style (Photoshop CS5). |
| [MacintoshNSPrintInfoCS5](#MacintoshNSPrintInfoCS5) | Macintosh NSPrintInfo. |
| [WindowsDevmodeCS5](#WindowsDevmodeCS5) | Windows DEVMODE. |
| [AutoSaveFilePathCS6](#AutoSaveFilePathCS6) | Auto Save File Path. |
| [AutoSaveFormatCS6](#AutoSaveFormatCS6) | Auto Save Format. |
| [PathSelectionStateCC](#PathSelectionStateCC) | Path Selection State. |
| [ImageReadyVariables](#ImageReadyVariables) | Image Ready variables. |
| [ImageReadyDatasets](#ImageReadyDatasets) | Image Ready data sets. |
| [PrintFlagsInformation](#PrintFlagsInformation) | Print flags information. |
## Methods

| Method | Description |
| --- | --- |
| [getByRawValue(int rawValue)](#getByRawValue-int-) |  |
| [getFirst()](#getFirst--) |  |
| [getAllValues()](#getAllValues--) |  |
| [getEnumValueByRawValue(int rawValue)](#getEnumValueByRawValue-int-) |  |
| [getEnumValueByName(String name)](#getEnumValueByName-java.lang.String-) |  |
| [getRawValueType()](#getRawValueType--) |  |
| [getRawValue()](#getRawValue--) |  |
| [name()](#name--) |  |
| [equals(Object o)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### ResolutionInfo {#ResolutionInfo}
```
public static final ImageResourceID ResolutionInfo
```


ResolutionInfo structure. See Appendix A in Photoshop API Guide PDF document.

### NamesOfAlphaChannels {#NamesOfAlphaChannels}
```
public static final ImageResourceID NamesOfAlphaChannels
```


Names of the alpha channels as a series of Pascal strings.

### Caption {#Caption}
```
public static final ImageResourceID Caption
```


The caption as a Pascal string.

### BorderInformation {#BorderInformation}
```
public static final ImageResourceID BorderInformation
```


Border information. Contains a fixed number (2 bytes real, 2 bytes fraction) for the border width, and 2 bytes for border units (1 = inches, 2 = cm, 3 = points, 4 = picas, 5 = columns).

### BackgroundColor {#BackgroundColor}
```
public static final ImageResourceID BackgroundColor
```


Background color.  See more. 

### PrintFlags {#PrintFlags}
```
public static final ImageResourceID PrintFlags
```


Print flags. A series of one-byte boolean values (see Page Setup dialog): labels, crop marks, color bars, registration marks, negative, flip, interpolate, caption, print flags.

### Grayscale {#Grayscale}
```
public static final ImageResourceID Grayscale
```


Grayscale and multichannel halftoning information.

### ColorHalftoning {#ColorHalftoning}
```
public static final ImageResourceID ColorHalftoning
```


Color halftoning information.

### DuotoneHalftoning {#DuotoneHalftoning}
```
public static final ImageResourceID DuotoneHalftoning
```


Duotone halftoning information.

### GrayscaleFunction {#GrayscaleFunction}
```
public static final ImageResourceID GrayscaleFunction
```


Grayscale and multichannel transfer function.

### ColorTransferFunctions {#ColorTransferFunctions}
```
public static final ImageResourceID ColorTransferFunctions
```


Color transfer functions.

### DuotoneTransferFunctions {#DuotoneTransferFunctions}
```
public static final ImageResourceID DuotoneTransferFunctions
```


Duotone transfer functions.

### DuotoneImageInformation {#DuotoneImageInformation}
```
public static final ImageResourceID DuotoneImageInformation
```


Duotone image information.

### EPSOptions {#EPSOptions}
```
public static final ImageResourceID EPSOptions
```


EPS options.

### QuickMaskInformation {#QuickMaskInformation}
```
public static final ImageResourceID QuickMaskInformation
```


Quick Mask information. 2 bytes containing Quick Mask channel ID; 1- byte boolean indicating whether the mask was initially empty.

### LayerStateInformation {#LayerStateInformation}
```
public static final ImageResourceID LayerStateInformation
```


Layer state information. 2 bytes containing the index of target layer (0 = bottom layer).

### WorkingPath {#WorkingPath}
```
public static final ImageResourceID WorkingPath
```


Working path (not saved). See See Path resource format.

### LayersGroupInformation {#LayersGroupInformation}
```
public static final ImageResourceID LayersGroupInformation
```


Layers group information. 2 bytes per layer containing a group ID for the dragging groups. Layers in a group have the same group ID.

### Iptc {#Iptc}
```
public static final ImageResourceID Iptc
```


IPTC-NAA record. Contains the File Info... information. See the documentation in the IPTC folder of the Documentation folder.

### ImageModeForRawFormat {#ImageModeForRawFormat}
```
public static final ImageResourceID ImageModeForRawFormat
```


Image mode for raw format files.

### JpegQuality {#JpegQuality}
```
public static final ImageResourceID JpegQuality
```


JPEG quality. Private.

### GridAndGuidesInfoPhotoshop4 {#GridAndGuidesInfoPhotoshop4}
```
public static final ImageResourceID GridAndGuidesInfoPhotoshop4
```


Grid and guides information.

### ThumbnailResourcePhotoshop4 {#ThumbnailResourcePhotoshop4}
```
public static final ImageResourceID ThumbnailResourcePhotoshop4
```


Thumbnail resource for Photoshop 4.0 only.

### CopyrightFlagPhotoshop4 {#CopyrightFlagPhotoshop4}
```
public static final ImageResourceID CopyrightFlagPhotoshop4
```


Copyright flag. Boolean indicating whether image is copyrighted. Can be set via Property suite or by user in File Info...

### UrlPhotoshop4 {#UrlPhotoshop4}
```
public static final ImageResourceID UrlPhotoshop4
```


URL. Handle of a text string with uniform resource locator. Can be set via Property suite or by user in File Info...

### ThumbnailResourcePhotoshop5 {#ThumbnailResourcePhotoshop5}
```
public static final ImageResourceID ThumbnailResourcePhotoshop5
```


Thumbnail resource (supersedes resource 1033). See See Thumbnail resource format.

### GlobalAnglePhotoshop5 {#GlobalAnglePhotoshop5}
```
public static final ImageResourceID GlobalAnglePhotoshop5
```


Global Angle. 4 bytes that contain an integer between 0 and 359, which is the global lighting angle for effects layer. If not present, assumed to be 30.

### IccProfilePhotoshop5 {#IccProfilePhotoshop5}
```
public static final ImageResourceID IccProfilePhotoshop5
```


(Photoshop 5.0) ICC Profile. The raw bytes of an ICC (International Color Consortium) format profile. See ICC1v42\_2006-05.pdf in the Documentation folder and icProfileHeader.h in Sample Code\\Common\\Includes.

### WatermarkPhotoshop5 {#WatermarkPhotoshop5}
```
public static final ImageResourceID WatermarkPhotoshop5
```


Watermark. One byte.

### IccUntaggedProfilePhotoshop5 {#IccUntaggedProfilePhotoshop5}
```
public static final ImageResourceID IccUntaggedProfilePhotoshop5
```


ICC Untagged Profile. 1 byte that disables any assumed profile handling when opening the file. 1 = intentionally untagged.

### TransparencyIndexPhotoshop6 {#TransparencyIndexPhotoshop6}
```
public static final ImageResourceID TransparencyIndexPhotoshop6
```


Transparency Index. 2 bytes for the index of transparent color, if any.

### GlobalAltitudePhotoshop6 {#GlobalAltitudePhotoshop6}
```
public static final ImageResourceID GlobalAltitudePhotoshop6
```


Global Altitude. 4 byte entry for altitude.

### SlicesPhotoshop6 {#SlicesPhotoshop6}
```
public static final ImageResourceID SlicesPhotoshop6
```


Slices (Photoshop 6).

### WorkflowUrlPhotoshop6 {#WorkflowUrlPhotoshop6}
```
public static final ImageResourceID WorkflowUrlPhotoshop6
```


Workflow URL. Unicode string. Photoshop 6.

### AlphaIdentifiersPhotoshop6 {#AlphaIdentifiersPhotoshop6}
```
public static final ImageResourceID AlphaIdentifiersPhotoshop6
```


Alpha Identifiers. 4 bytes of length, followed by 4 bytes each for every alpha identifier.

### UrlListPhotoshop6 {#UrlListPhotoshop6}
```
public static final ImageResourceID UrlListPhotoshop6
```


URL InternalList. 4 byte count of URLs, followed by 4 byte long, 4 byte ID, and Unicode string for each count.

### VersionInfoPhotoshop6 {#VersionInfoPhotoshop6}
```
public static final ImageResourceID VersionInfoPhotoshop6
```


Version Info. 4 bytes version, 1 byte hasRealMergedData , Unicode string: writer name, Unicode string: reader name, 4 bytes file version.

### ExifData1Photoshop7 {#ExifData1Photoshop7}
```
public static final ImageResourceID ExifData1Photoshop7
```


EXIF data 1,  see more .

### ExifData3Photoshop7 {#ExifData3Photoshop7}
```
public static final ImageResourceID ExifData3Photoshop7
```


 EXIF data 3. 

### XmpPhotoshop7 {#XmpPhotoshop7}
```
public static final ImageResourceID XmpPhotoshop7
```


XMP metadata. File info as XML description,  see more .

### CaptionDigestPhotoshop7 {#CaptionDigestPhotoshop7}
```
public static final ImageResourceID CaptionDigestPhotoshop7
```


Caption digest. 16 bytes: RSA Data Security, MD5 message-digest algorithm.

### PrintScalePhotoshop7 {#PrintScalePhotoshop7}
```
public static final ImageResourceID PrintScalePhotoshop7
```


Print scale. 2 bytes style (0 = centered, 1 = size to fit, 2 = user defined). 4 bytes x location (floating point). 4 bytes y location (floating point). 4 bytes scale (floating point).

### PixelAspectRatio {#PixelAspectRatio}
```
public static final ImageResourceID PixelAspectRatio
```


Pixel Aspect Ratio. 4 bytes (version = 1 or 2), 8 bytes double, x / y of a pixel. Version 2, attempting to correct values for NTSC and PAL, previously off by a factor of approx. 5%.

### LayerComps {#LayerComps}
```
public static final ImageResourceID LayerComps
```


Layer Comps. 4 bytes (descriptor version = 16), Descriptor.

### LayerSelectionIds {#LayerSelectionIds}
```
public static final ImageResourceID LayerSelectionIds
```


Layer Selection ID(s). 2 bytes count, following is repeated for each count: 4 bytes layer ID.

### PrintInfoCS2 {#PrintInfoCS2}
```
public static final ImageResourceID PrintInfoCS2
```


Print info (Photoshop CS2).

### LayerGroupEnabledIdCS2 {#LayerGroupEnabledIdCS2}
```
public static final ImageResourceID LayerGroupEnabledIdCS2
```


Layer Group(s) Enabled ID. 1 byte for each layer in the document, repeated by length of the resource. NOTE: Layer groups have start and end markers (Photoshop CS2).

### ColorSamplersResourceCS3 {#ColorSamplersResourceCS3}
```
public static final ImageResourceID ColorSamplersResourceCS3
```


Color samplers resource. Also see ID 1038 for old format.

### MeasurementScaleCS3 {#MeasurementScaleCS3}
```
public static final ImageResourceID MeasurementScaleCS3
```


Measurement Scale. 4 bytes (descriptor version = 16), Descriptor.

### TimelineInformationCS3 {#TimelineInformationCS3}
```
public static final ImageResourceID TimelineInformationCS3
```


Timeline Information. 4 bytes (descriptor version = 16), Descriptor.

### SheetDisclosureCS3 {#SheetDisclosureCS3}
```
public static final ImageResourceID SheetDisclosureCS3
```


Sheet Disclosure. 4 bytes (descriptor version = 16), Descriptor.

### PrintInformationCS5 {#PrintInformationCS5}
```
public static final ImageResourceID PrintInformationCS5
```


Print Information (Photoshop CS5).

### PrintStyleCS5 {#PrintStyleCS5}
```
public static final ImageResourceID PrintStyleCS5
```


Print Style (Photoshop CS5).

### MacintoshNSPrintInfoCS5 {#MacintoshNSPrintInfoCS5}
```
public static final ImageResourceID MacintoshNSPrintInfoCS5
```


Macintosh NSPrintInfo. Variable OS specific info for Macintosh. NSPrintInfo. It is recommended that you do not interpret or use this data. (Photoshop CS5).

### WindowsDevmodeCS5 {#WindowsDevmodeCS5}
```
public static final ImageResourceID WindowsDevmodeCS5
```


Windows DEVMODE. Variable OS specific info for Windows. DEVMODE. It is recommended that you do not interpret or use this data. (Photoshop CS5).

### AutoSaveFilePathCS6 {#AutoSaveFilePathCS6}
```
public static final ImageResourceID AutoSaveFilePathCS6
```


Auto Save File Path. Unicode string. (Photoshop CS6).

### AutoSaveFormatCS6 {#AutoSaveFormatCS6}
```
public static final ImageResourceID AutoSaveFormatCS6
```


Auto Save Format. Unicode string. (Photoshop CS6).

### PathSelectionStateCC {#PathSelectionStateCC}
```
public static final ImageResourceID PathSelectionStateCC
```


Path Selection State. (Photoshop CC).

### ImageReadyVariables {#ImageReadyVariables}
```
public static final ImageResourceID ImageReadyVariables
```


Image Ready variables. XML representation of variables definition.

### ImageReadyDatasets {#ImageReadyDatasets}
```
public static final ImageResourceID ImageReadyDatasets
```


Image Ready data sets.

### PrintFlagsInformation {#PrintFlagsInformation}
```
public static final ImageResourceID PrintFlagsInformation
```


Print flags information. 2 bytes version ( = 1), 1 byte center crop marks, 1 byte ( = 0), 4 bytes bleed width value, 2 bytes bleed width scale.

### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static ImageResourceID getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[ImageResourceID](../../com.groupdocs.metadata.core/imageresourceid)
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
