---
title: ImageResourceID class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "ImageResourceID enum — GroupDocs.Metadata for Python via .NET API reference."
type: docs
url: /python-net/groupdocs.metadata.formats.image/imageresourceid/
is_root: false
weight: 130
---


## ImageResourceID class

The ImageResourceID type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| [RESOLUTION_INFO](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/resolution_info/) | ResolutionInfo structure. See Appendix A in Photoshop API Guide PDF document. |
| [NAMES_OF_ALPHA_CHANNELS](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/names_of_alpha_channels/) | Names of the alpha channels as a series of Pascal strings. |
| [CAPTION](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/caption/) | The caption as a Pascal string. |
| [BORDER_INFORMATION](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/border_information/) | Border information. Contains a fixed number (2 bytes real, 2 bytes fraction) for the border width, and 2 bytes for border units (1 = inches, 2 = cm, 3 = points, 4 = picas, 5 = columns). |
| [BACKGROUND_COLOR](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/background_color/) | Background color. See more. |
| [PRINT_FLAGS](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/print_flags/) | Print flags. A series of one-byte boolean values (see Page Setup dialog): labels, crop marks, color bars, registration marks, negative, flip, interpolate, caption, print flags. |
| [GRAYSCALE](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/grayscale/) | Grayscale and multichannel halftoning information. |
| [COLOR_HALFTONING](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/color_halftoning/) | Color halftoning information. |
| [DUOTONE_HALFTONING](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/duotone_halftoning/) | Duotone halftoning information. |
| [GRAYSCALE_FUNCTION](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/grayscale_function/) | Grayscale and multichannel transfer function. |
| [COLOR_TRANSFER_FUNCTIONS](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/color_transfer_functions/) | Color transfer functions. |
| [DUOTONE_TRANSFER_FUNCTIONS](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/duotone_transfer_functions/) | Duotone transfer functions. |
| [DUOTONE_IMAGE_INFORMATION](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/duotone_image_information/) | Duotone image information. |
| [EPS_OPTIONS](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/eps_options/) | EPS options. |
| [QUICK_MASK_INFORMATION](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/quick_mask_information/) | Quick Mask information. 2 bytes containing Quick Mask channel ID; 1- byte boolean indicating whether the mask was initially empty. |
| [LAYER_STATE_INFORMATION](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/layer_state_information/) | Layer state information. 2 bytes containing the index of target layer (0 = bottom layer). |
| [WORKING_PATH](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/working_path/) | Working path (not saved). See See Path resource format. |
| [LAYERS_GROUP_INFORMATION](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/layers_group_information/) | Layers group information. 2 bytes per layer containing a group ID for the dragging groups. Layers in a group have the same group ID. |
| [IPTC](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/iptc/) | IPTC-NAA record. Contains the File Info... information. See the documentation in the IPTC folder of the Documentation folder. |
| [IMAGE_MODE_FOR_RAW_FORMAT](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/image_mode_for_raw_format/) | Image mode for raw format files. |
| [JPEG_QUALITY](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/jpeg_quality/) | JPEG quality. Private. |
| [GRID_AND_GUIDES_INFO_PHOTOSHOP4](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/grid_and_guides_info_photoshop4/) | Grid and guides information. |
| [THUMBNAIL_RESOURCE_PHOTOSHOP4](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/thumbnail_resource_photoshop4/) | Thumbnail resource for Photoshop 4.0 only. |
| [COPYRIGHT_FLAG_PHOTOSHOP4](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/copyright_flag_photoshop4/) | Copyright flag. Boolean indicating whether image is copyrighted. Can be set via Property suite or by user in File Info... |
| [URL_PHOTOSHOP4](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/url_photoshop4/) | URL. Handle of a text string with uniform resource locator. Can be set via Property suite or by user in File Info... |
| [THUMBNAIL_RESOURCE_PHOTOSHOP5](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/thumbnail_resource_photoshop5/) | Thumbnail resource (supersedes resource 1033). See See Thumbnail resource format. |
| [GLOBAL_ANGLE_PHOTOSHOP5](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/global_angle_photoshop5/) | Global Angle. 4 bytes that contain an integer between 0 and 359, which is the global lighting angle for effects layer. If not present, assumed to be 30. |
| [ICC_PROFILE_PHOTOSHOP5](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/icc_profile_photoshop5/) | (Photoshop 5.0) ICC Profile. The raw bytes of an ICC (International Color Consortium) format profile. See ICC1v42_2006-05.pdf in the Documentation folder and icProfileHeader.h in Sample Code\Common\Includes. |
| [WATERMARK_PHOTOSHOP5](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/watermark_photoshop5/) | Watermark. One byte. |
| [ICC_UNTAGGED_PROFILE_PHOTOSHOP5](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/icc_untagged_profile_photoshop5/) | ICC Untagged Profile. 1 byte that disables any assumed profile handling when opening the file. 1 = intentionally untagged. |
| [TRANSPARENCY_INDEX_PHOTOSHOP6](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/transparency_index_photoshop6/) | Transparency Index. 2 bytes for the index of transparent color, if any. |
| [GLOBAL_ALTITUDE_PHOTOSHOP6](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/global_altitude_photoshop6/) | Global Altitude. 4 byte entry for altitude. |
| [SLICES_PHOTOSHOP6](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/slices_photoshop6/) | Slices (Photoshop 6). |
| [WORKFLOW_URL_PHOTOSHOP6](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/workflow_url_photoshop6/) | Workflow URL. Unicode string. Photoshop 6. |
| [ALPHA_IDENTIFIERS_PHOTOSHOP6](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/alpha_identifiers_photoshop6/) | Alpha Identifiers. 4 bytes of length, followed by 4 bytes each for every alpha identifier. |
| [URL_LIST_PHOTOSHOP6](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/url_list_photoshop6/) | URL InternalList. 4 byte count of URLs, followed by 4 byte long, 4 byte ID, and Unicode string for each count. |
| [VERSION_INFO_PHOTOSHOP6](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/version_info_photoshop6/) | Version Info. 4 bytes version, 1 byte hasRealMergedData , Unicode string: writer name, Unicode string: reader name, 4 bytes file version. |
| [EXIF_DATA1_PHOTOSHOP7](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/exif_data1_photoshop7/) | EXIF data 1, see more. |
| [EXIF_DATA3_PHOTOSHOP7](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/exif_data3_photoshop7/) | EXIF data 3. |
| [XMP_PHOTOSHOP7](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/xmp_photoshop7/) | XMP metadata. File info as XML description, see more. |
| [CAPTION_DIGEST_PHOTOSHOP7](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/caption_digest_photoshop7/) | Caption digest. 16 bytes: RSA Data Security, MD5 message-digest algorithm. |
| [PRINT_SCALE_PHOTOSHOP7](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/print_scale_photoshop7/) | Print scale. 2 bytes style (0 = centered, 1 = size to fit, 2 = user defined). 4 bytes x location (floating point). 4 bytes y location (floating point). 4 bytes scale (floating point). |
| [PIXEL_ASPECT_RATIO](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/pixel_aspect_ratio/) | Pixel Aspect Ratio. 4 bytes (version = 1 or 2), 8 bytes double, x / y of a pixel. Version 2, attempting to correct values for NTSC and PAL, previously off by a factor of approx. 5%. |
| [LAYER_COMPS](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/layer_comps/) | Layer Comps. 4 bytes (descriptor version = 16), Descriptor. |
| [LAYER_SELECTION_IDS](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/layer_selection_ids/) | Layer Selection ID(s). 2 bytes count, following is repeated for each count: 4 bytes layer ID. |
| [PRINT_INFO_CS2](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/print_info_cs2/) | Print info (Photoshop CS2). |
| [LAYER_GROUP_ENABLED_ID_CS2](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/layer_group_enabled_id_cs2/) | Layer Group(s) Enabled ID. 1 byte for each layer in the document, repeated by length of the resource. NOTE: Layer groups have start and end markers (Photoshop CS2). |
| [COLOR_SAMPLERS_RESOURCE_CS3](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/color_samplers_resource_cs3/) | Color samplers resource. Also see ID 1038 for old format. |
| [MEASUREMENT_SCALE_CS3](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/measurement_scale_cs3/) | Measurement Scale. 4 bytes (descriptor version = 16), Descriptor. |
| [TIMELINE_INFORMATION_CS3](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/timeline_information_cs3/) | Timeline Information. 4 bytes (descriptor version = 16), Descriptor. |
| [SHEET_DISCLOSURE_CS3](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/sheet_disclosure_cs3/) | Sheet Disclosure. 4 bytes (descriptor version = 16), Descriptor. |
| [PRINT_INFORMATION_CS5](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/print_information_cs5/) | Print Information (Photoshop CS5). |
| [PRINT_STYLE_CS5](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/print_style_cs5/) | Print Style (Photoshop CS5). |
| [MACINTOSH_NS_PRINT_INFO_CS5](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/macintosh_ns_print_info_cs5/) | Macintosh NSPrintInfo. Variable OS specific info for Macintosh. NSPrintInfo. It is recommended that you do not interpret or use this data. (Photoshop CS5). |
| [WINDOWS_DEVMODE_CS5](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/windows_devmode_cs5/) | Windows DEVMODE. Variable OS specific info for Windows. DEVMODE. It is recommended that you do not interpret or use this data. (Photoshop CS5). |
| [AUTO_SAVE_FILE_PATH_CS6](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/auto_save_file_path_cs6/) | Auto Save File Path. Unicode string. (Photoshop CS6). |
| [AUTO_SAVE_FORMAT_CS6](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/auto_save_format_cs6/) | Auto Save Format. Unicode string. (Photoshop CS6). |
| [PATH_SELECTION_STATE_CC](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/path_selection_state_cc/) | Path Selection State. (Photoshop CC). |
| [IMAGE_READY_VARIABLES](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/image_ready_variables/) | Image Ready variables. XML representation of variables definition. |
| [IMAGE_READY_DATASETS](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/image_ready_datasets/) | Image Ready data sets. |
| [PRINT_FLAGS_INFORMATION](/metadata/python-net/groupdocs.metadata.formats.image/imageresourceid/print_flags_information/) | Print flags information. 2 bytes version ( = 1), 1 byte center crop marks, 1 byte ( = 0), 4 bytes bleed width value, 2 bytes bleed width scale. |

### See Also
* module [`groupdocs.metadata.formats.image`](/metadata/python-net/groupdocs.metadata.formats.image/)
