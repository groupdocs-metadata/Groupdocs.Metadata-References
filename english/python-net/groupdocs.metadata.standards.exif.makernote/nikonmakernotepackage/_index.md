---
title: NikonMakerNotePackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/
is_root: false
weight: 40
---

## NikonMakerNotePackage class

Represents NIKON MakerNote metadata.



**Inheritance:** [`NikonMakerNotePackage`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage) → 
[`MakerNotePackage`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/makernotepackage) → 
[`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The NikonMakerNotePackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/__init__/#list) | Initializes a new instance of the [`NikonMakerNotePackage`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/count) | Gets the number of metadata properties. |
| [maker_note_version](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/maker_note_version) | Gets the MakerNote version. |
| [iso](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/iso) | Gets the iso. |
| [color_mode](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/color_mode) | Gets the color mode. |
| [quality](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/quality) | Gets the quality string. |
| [white_balance](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/white_balance) | Gets the white balance. |
| [sharpness](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/sharpness) | Gets the sharpness. |
| [focus_mode](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/focus_mode) | Gets the focus mode. |
| [flash_setting](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/flash_setting) | Gets the flash setting. |
| [flash_type](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/flash_type) | Gets the type of the flash. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [to_list](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/to_list/#) | Creates a list from the package. |
| [remove](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/remove/#groupdocs.metadata.formats.image.TiffTagID) | Removes the property with the specified id. |
| [set](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/set/#groupdocs.metadata.formats.image.TiffTag) | Adds or replaces the specified tag. |
| [clear](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/clear/#) | Removes all TIFF tags stored in the package. |



### See Also
* module [`groupdocs.metadata.standards.exif.makernote`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage)
* class [`MakerNotePackage`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/makernotepackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`NikonMakerNotePackage`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage)
