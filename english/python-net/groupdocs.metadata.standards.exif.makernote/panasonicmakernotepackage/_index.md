---
title: PanasonicMakerNotePackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 50
url: /python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/
is_root: false
---

## PanasonicMakerNotePackage class

Represents PANASONIC MakerNote metadata.



**Inheritance:** [`PanasonicMakerNotePackage`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage) → 
[`MakerNotePackage`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/makernotepackage) → 
[`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The PanasonicMakerNotePackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/count) | Gets the number of metadata properties. |
| [image_quality](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/image_quality) | Gets the image quality. |
| [firmware_version](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/firmware_version) | Gets the firmware version. |
| [white_balance](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/white_balance) | Gets the white balance. |
| [focus_mode](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/focus_mode) | Gets the focus mode. |
| [af_mode](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/af_mode) | Gets the AF mode. |
| [image_stabilization](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/image_stabilization) | Gets the image stabilization mode. |
| [macro_mode](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/macro_mode) | Gets the macro mode. |
| [shooting_mode](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/shooting_mode) | Gets the shooting mode. |
| [audio](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/audio) | Gets the audio mode. |
| [lens_type](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/lens_type) | Gets the type of the lens. |
| [lens_serial_number](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/lens_serial_number) | Gets the lens serial number. |
| [accessory_type](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/accessory_type) | Gets the type of the accessory. |
| [accessory_serial_number](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/accessory_serial_number) | Gets the accessory serial number. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`to_list(self)`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/to_list/#) | Creates a list from the package. |
| [`remove(self, tag_id)`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/remove/#groupdocs.metadata.formats.image.tifftagid) | Removes the property with the specified id. |
| [`set(self, tag)`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/set/#groupdocs.metadata.formats.image.tifftag) | Adds or replaces the specified tag. |
| [`clear(self)`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/clear/#) | Removes all TIFF tags stored in the package. |



### See Also
* module [`groupdocs.metadata.standards.exif.makernote`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage)
* class [`MakerNotePackage`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/makernotepackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`PanasonicMakerNotePackage`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage)
