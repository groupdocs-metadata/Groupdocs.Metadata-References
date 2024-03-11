---
title: ImageResourceID
second_title: GroupDocs.Metadata for .NET API Reference
description: Image resources standard ID numbers. Not all file formats use all IDs. Some information may be stored in other sections of the file.
type: docs
weight: 1960
url: /net/groupdocs.metadata.formats.image/imageresourceid/
---
## ImageResourceID enumeration

Image resources standard ID numbers. Not all file formats use all ID's. Some information may be stored in other sections of the file.

```csharp
public enum ImageResourceID
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| ResolutionInfo | `1005` | ResolutionInfo structure. See Appendix A in Photoshop API Guide PDF document. |
| NamesOfAlphaChannels | `1006` | Names of the alpha channels as a series of Pascal strings. |
| Caption | `1008` | The caption as a Pascal string. |
| BorderInformation | `1009` | Border information. Contains a fixed number (2 bytes real, 2 bytes fraction) for the border width, and 2 bytes for border units (1 = inches, 2 = cm, 3 = points, 4 = picas, 5 = columns). |
| BackgroundColor | `1010` | Background color. [See more.](http://www.adobe.com/devnet-apps/photoshop/fileformatashtml/#50577411_31265) |
| PrintFlags | `1011` | Print flags. A series of one-byte boolean values (see Page Setup dialog): labels, crop marks, color bars, registration marks, negative, flip, interpolate, caption, print flags. |
| Grayscale | `1012` | Grayscale and multichannel halftoning information. |
| ColorHalftoning | `1013` | Color halftoning information. |
| DuotoneHalftoning | `1014` | Duotone halftoning information. |
| GrayscaleFunction | `1015` | Grayscale and multichannel transfer function. |
| ColorTransferFunctions | `1016` | Color transfer functions. |
| DuotoneTransferFunctions | `1017` | Duotone transfer functions. |
| DuotoneImageInformation | `1018` | Duotone image information. |
| EPSOptions | `1021` | EPS options. |
| QuickMaskInformation | `1022` | Quick Mask information. 2 bytes containing Quick Mask channel ID; 1- byte boolean indicating whether the mask was initially empty. |
| LayerStateInformation | `1024` | Layer state information. 2 bytes containing the index of target layer (0 = bottom layer). |
| WorkingPath | `1025` | Working path (not saved). See See Path resource format. |
| LayersGroupInformation | `1026` | Layers group information. 2 bytes per layer containing a group ID for the dragging groups. Layers in a group have the same group ID. |
| Iptc | `1028` | IPTC-NAA record. Contains the File Info... information. See the documentation in the IPTC folder of the Documentation folder. |
| ImageModeForRawFormat | `1029` | Image mode for raw format files. |
| JpegQuality | `1030` | JPEG quality. Private. |
| GridAndGuidesInfoPhotoshop4 | `1032` | Grid and guides information. |
| ThumbnailResourcePhotoshop4 | `1033` | Thumbnail resource for Photoshop 4.0 only. |
| CopyrightFlagPhotoshop4 | `1034` | Copyright flag. Boolean indicating whether image is copyrighted. Can be set via Property suite or by user in File Info... |
| UrlPhotoshop4 | `1035` | URL. Handle of a text string with uniform resource locator. Can be set via Property suite or by user in File Info... |
| ThumbnailResourcePhotoshop5 | `1036` | Thumbnail resource (supersedes resource 1033). See See Thumbnail resource format. |
| GlobalAnglePhotoshop5 | `1037` | Global Angle. 4 bytes that contain an integer between 0 and 359, which is the global lighting angle for effects layer. If not present, assumed to be 30. |
| IccProfilePhotoshop5 | `1039` | (Photoshop 5.0) ICC Profile. The raw bytes of an ICC (International Color Consortium) format profile. See ICC1v42_2006-05.pdf in the Documentation folder and icProfileHeader.h in Sample Code\Common\Includes. |
| WatermarkPhotoshop5 | `1040` | Watermark. One byte. |
| IccUntaggedProfilePhotoshop5 | `1041` | ICC Untagged Profile. 1 byte that disables any assumed profile handling when opening the file. 1 = intentionally untagged. |
| TransparencyIndexPhotoshop6 | `1047` | Transparency Index. 2 bytes for the index of transparent color, if any. |
| GlobalAltitudePhotoshop6 | `1049` | Global Altitude. 4 byte entry for altitude. |
| SlicesPhotoshop6 | `1050` | Slices (Photoshop 6). |
| WorkflowUrlPhotoshop6 | `1051` | Workflow URL. Unicode string. Photoshop 6. |
| AlphaIdentifiersPhotoshop6 | `1053` | Alpha Identifiers. 4 bytes of length, followed by 4 bytes each for every alpha identifier. |
| UrlListPhotoshop6 | `1054` | URL InternalList. 4 byte count of URLs, followed by 4 byte long, 4 byte ID, and Unicode string for each count. |
| VersionInfoPhotoshop6 | `1057` | Version Info. 4 bytes version, 1 byte hasRealMergedData , Unicode string: writer name, Unicode string: reader name, 4 bytes file version. |
| ExifData1Photoshop7 | `1058` | EXIF data 1, [see more](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf). |
| ExifData3Photoshop7 | `1059` | [EXIF data 3. ](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) |
| XmpPhotoshop7 | `1060` | XMP metadata. File info as XML description, [see more](http://www.adobe.com/devnet/xmp). |
| CaptionDigestPhotoshop7 | `1061` | Caption digest. 16 bytes: RSA Data Security, MD5 message-digest algorithm. |
| PrintScalePhotoshop7 | `1062` | Print scale. 2 bytes style (0 = centered, 1 = size to fit, 2 = user defined). 4 bytes x location (floating point). 4 bytes y location (floating point). 4 bytes scale (floating point). |
| PixelAspectRatio | `1064` | Pixel Aspect Ratio. 4 bytes (version = 1 or 2), 8 bytes double, x / y of a pixel. Version 2, attempting to correct values for NTSC and PAL, previously off by a factor of approx. 5%. |
| LayerComps | `1065` | Layer Comps. 4 bytes (descriptor version = 16), Descriptor. |
| LayerSelectionIds | `1069` | Layer Selection ID(s). 2 bytes count, following is repeated for each count: 4 bytes layer ID. |
| PrintInfoCS2 | `1071` | Print info (Photoshop CS2). |
| LayerGroupEnabledIdCS2 | `1072` | Layer Group(s) Enabled ID. 1 byte for each layer in the document, repeated by length of the resource. NOTE: Layer groups have start and end markers (Photoshop CS2). |
| ColorSamplersResourceCS3 | `1073` | Color samplers resource. Also see ID 1038 for old format. |
| MeasurementScaleCS3 | `1074` | Measurement Scale. 4 bytes (descriptor version = 16), Descriptor. |
| TimelineInformationCS3 | `1075` | Timeline Information. 4 bytes (descriptor version = 16), Descriptor. |
| SheetDisclosureCS3 | `1076` | Sheet Disclosure. 4 bytes (descriptor version = 16), Descriptor. |
| PrintInformationCS5 | `1082` | Print Information (Photoshop CS5). |
| PrintStyleCS5 | `1083` | Print Style (Photoshop CS5). |
| MacintoshNSPrintInfoCS5 | `1084` | Macintosh NSPrintInfo. Variable OS specific info for Macintosh. NSPrintInfo. It is recommended that you do not interpret or use this data. (Photoshop CS5). |
| WindowsDevmodeCS5 | `1085` | Windows DEVMODE. Variable OS specific info for Windows. DEVMODE. It is recommended that you do not interpret or use this data. (Photoshop CS5). |
| AutoSaveFilePathCS6 | `1086` | Auto Save File Path. Unicode string. (Photoshop CS6). |
| AutoSaveFormatCS6 | `1087` | Auto Save Format. Unicode string. (Photoshop CS6). |
| PathSelectionStateCC | `1088` | Path Selection State. (Photoshop CC). |
| ImageReadyVariables | `7000` | Image Ready variables. XML representation of variables definition. |
| ImageReadyDatasets | `7001` | Image Ready data sets. |
| PrintFlagsInformation | `10000` | Print flags information. 2 bytes version ( = 1), 1 byte center crop marks, 1 byte ( = 0), 4 bytes bleed width value, 2 bytes bleed width scale. |

### See Also

* namespace [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
