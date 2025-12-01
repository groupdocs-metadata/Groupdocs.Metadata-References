---
title: ImageResourceID enumeration
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 540
url: /python-net/groupdocs.metadata.formats.image/imageresourceid/
is_root: false
---

## ImageResourceID enumeration

Image resources standard ID numbers. Not all file formats use all ID's. Some information may be stored in other sections of the file.



The ImageResourceID type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| RESOLUTION_INFO | ResolutionInfo structure. See Appendix A in Photoshop API Guide PDF document. |
| NAMES_OF_ALPHA_CHANNELS | Names of the alpha channels as a series of Pascal strings. |
| CAPTION | The caption as a Pascal string. |
| BORDER_INFORMATION | Border information. <br/>Contains a fixed number (2 bytes real, 2 bytes fraction) for the border width, <br/>and 2 bytes for border units (1 = inches, 2 = cm, 3 = points, 4 = picas, 5 = columns). |
| BACKGROUND_COLOR | Background color. |
| PRINT_FLAGS | Print flags. <br/>A series of one-byte boolean values (see Page Setup dialog): <br/>labels, crop marks, color bars, registration marks, negative, flip, interpolate, caption, print flags. |
| GRAYSCALE | Grayscale and multichannel halftoning information. |
| COLOR_HALFTONING | Color halftoning information. |
| DUOTONE_HALFTONING | Duotone halftoning information. |
| GRAYSCALE_FUNCTION | Grayscale and multichannel transfer function. |
| COLOR_TRANSFER_FUNCTIONS | Color transfer functions. |
| DUOTONE_TRANSFER_FUNCTIONS | Duotone transfer functions. |
| DUOTONE_IMAGE_INFORMATION | Duotone image information. |
| EPS_OPTIONS | EPS options. |
| QUICK_MASK_INFORMATION | Quick Mask information. 2 bytes containing Quick Mask channel ID; 1- byte boolean indicating whether the mask was initially empty. |
| LAYER_STATE_INFORMATION | Layer state information. 2 bytes containing the index of target layer (0 = bottom layer). |
| WORKING_PATH | Working path (not saved). See See Path resource format. |
| LAYERS_GROUP_INFORMATION | Layers group information. <br/>2 bytes per layer containing a group ID for the dragging groups. Layers in a group have the same group ID. |
| IPTC | IPTC-NAA record. Contains the File Info... information. See the documentation in the IPTC folder of the Documentation folder. |
| IMAGE_MODE_FOR_RAW_FORMAT | Image mode for raw format files. |
| JPEG_QUALITY | JPEG quality. Private. |
| GRID_AND_GUIDES_INFO_PHOTOSHOP4 | Grid and guides information. |
| THUMBNAIL_RESOURCE_PHOTOSHOP4 | Thumbnail resource for Photoshop 4.0 only. |
| COPYRIGHT_FLAG_PHOTOSHOP4 | Copyright flag. Boolean indicating whether image is copyrighted. Can be set via Property suite or by user in File Info... |
| URL_PHOTOSHOP4 | URL. Handle of a text string with uniform resource locator. Can be set via Property suite or by user in File Info... |
| THUMBNAIL_RESOURCE_PHOTOSHOP5 | Thumbnail resource (supersedes resource 1033). See See Thumbnail resource format. |
| GLOBAL_ANGLE_PHOTOSHOP5 | Global Angle. <br/>4 bytes that contain an integer between 0 and 359, which is the global lighting angle for effects layer. If not present, assumed to be 30. |
| ICC_PROFILE_PHOTOSHOP5 | (Photoshop 5.0) ICC Profile. <br/>The raw bytes of an ICC (International Color Consortium) format profile. See ICC1v42_2006-05.pdf in the Documentation folder and icProfileHeader.h in Sample Code\Common\Includes. |
| WATERMARK_PHOTOSHOP5 | Watermark. One byte. |
| ICC_UNTAGGED_PROFILE_PHOTOSHOP5 | ICC Untagged Profile. 1 byte that disables any assumed profile handling when opening the file. 1 = intentionally untagged. |
| TRANSPARENCY_INDEX_PHOTOSHOP6 | Transparency Index. 2 bytes for the index of transparent color, if any. |
| GLOBAL_ALTITUDE_PHOTOSHOP6 | Global Altitude. 4 byte entry for altitude. |
| SLICES_PHOTOSHOP6 | Slices (Photoshop 6). |
| WORKFLOW_URL_PHOTOSHOP6 | Workflow URL. Unicode string. Photoshop 6. |
| ALPHA_IDENTIFIERS_PHOTOSHOP6 | Alpha Identifiers. 4 bytes of length, followed by 4 bytes each for every alpha identifier. |
| URL_LIST_PHOTOSHOP6 | URL InternalList. 4 byte count of URLs, followed by 4 byte long, 4 byte ID, and Unicode string for each count. |
| VERSION_INFO_PHOTOSHOP6 | Version Info. 4 bytes version, 1 byte hasRealMergedData , Unicode string: writer name, Unicode string: reader name, 4 bytes file version. |
| EXIF_DATA_1_PHOTOSHOP_7 | EXIF data 1 |
| EXIF_DATA_3_PHOTOSHOP_7 | ExifData3Photoshop7 |
| XMP_PHOTOSHOP7 | XMP metadata. File info as XML description. |
| CAPTION_DIGEST_PHOTOSHOP7 | Caption digest. 16 bytes: RSA Data Security, MD5 message-digest algorithm. |
| PRINT_SCALE_PHOTOSHOP7 | Print scale. 2 bytes style (0 = centered, 1 = size to fit, 2 = user defined). <br/>4 bytes x location (floating point). <br/>4 bytes y location (floating point). <br/>4 bytes scale (floating point). |
| PIXEL_ASPECT_RATIO | Pixel Aspect Ratio. 4 bytes (version = 1 or 2), 8 bytes double, x / y of a pixel. <br/>Version 2, attempting to correct values for NTSC and PAL, previously off by a factor of approx. 5%. |
| LAYER_COMPS | Layer Comps. 4 bytes (descriptor version = 16), Descriptor. |
| LAYER_SELECTION_IDS | Layer Selection ID(s). <br/>2 bytes count, following is repeated for each count: 4 bytes layer ID. |
| PRINT_INFO_CS2 | Print info (Photoshop CS2). |
| LAYER_GROUP_ENABLED_ID_CS2 | Layer Group(s) Enabled ID. <br/>1 byte for each layer in the document, repeated by length of the resource. <br/>NOTE: Layer groups have start and end markers (Photoshop CS2). |
| COLOR_SAMPLERS_RESOURCE_CS3 | Color samplers resource. Also see ID 1038 for old format. |
| MEASUREMENT_SCALE_CS3 | Measurement Scale. 4 bytes (descriptor version = 16), Descriptor. |
| TIMELINE_INFORMATION_CS3 | Timeline Information. 4 bytes (descriptor version = 16), Descriptor. |
| SHEET_DISCLOSURE_CS3 | Sheet Disclosure. 4 bytes (descriptor version = 16), Descriptor. |
| PRINT_INFORMATION_CS5 | Print Information (Photoshop CS5). |
| PRINT_STYLE_CS5 | Print Style (Photoshop CS5). |
| MACINTOSH_NS_PRINT_INFO_CS5 | Macintosh NSPrintInfo. <br/>Variable OS specific info for Macintosh. NSPrintInfo. <br/>It is recommended that you do not interpret or use this data. (Photoshop CS5). |
| WINDOWS_DEVMODE_CS5 | Windows DEVMODE. <br/>Variable OS specific info for Windows. DEVMODE. <br/>It is recommended that you do not interpret or use this data. (Photoshop CS5). |
| AUTO_SAVE_FILE_PATH_CS6 | Auto Save File Path. Unicode string. (Photoshop CS6). |
| AUTO_SAVE_FORMAT_CS6 | Auto Save Format. Unicode string. (Photoshop CS6). |
| PATH_SELECTION_STATE_CC | Path Selection State. (Photoshop CC). |
| IMAGE_READY_VARIABLES | Image Ready variables. XML representation of variables definition. |
| IMAGE_READY_DATASETS | Image Ready data sets. |
| PRINT_FLAGS_INFORMATION | Print flags information. <br/>2 bytes version ( = 1), <br/>1 byte center crop marks, <br/>1 byte ( = 0), 4 bytes bleed width value, 2 bytes bleed width scale. |



### See Also
* module [`groupdocs.metadata.formats.image`](..)
