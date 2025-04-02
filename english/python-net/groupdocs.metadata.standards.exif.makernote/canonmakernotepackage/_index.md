---
title: CanonMakerNotePackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/
is_root: false
weight: 20
---

## CanonMakerNotePackage class

Represents CANON MakerNote metadata.



**Inheritance:** [`CanonMakerNotePackage`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage) → 
[`MakerNotePackage`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/makernotepackage) → 
[`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The CanonMakerNotePackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/count) | Gets the number of metadata properties. |
| [camera_settings](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/camera_settings) | Gets the camera settings. |
| [canon_image_type](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/canon_image_type) | Gets the Canon image type. |
| [canon_firmware_version](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/canon_firmware_version) | Gets the canon firmware version. |
| [file_number](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/file_number) | Gets the file number. |
| [owner_name](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/owner_name) | Gets the name of the owner. |
| [serial_number](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/serial_number) | Gets the serial number. |
| [canon_file_length](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/canon_file_length) | Gets the length of the canon file. |
| [canon_model_id](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/canon_model_id) | Gets the canon model identifier. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [to_list](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/to_list/#) | Creates a list from the package. |
| [remove](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/remove/#groupdocs.metadata.formats.image.TiffTagID) | Removes the property with the specified id. |
| [set](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/set/#groupdocs.metadata.formats.image.TiffTag) | Adds or replaces the specified tag. |
| [clear](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/clear/#) | Removes all TIFF tags stored in the package. |



### See Also
* module [`groupdocs.metadata.standards.exif.makernote`](..)
* class [`CanonMakerNotePackage`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage)
* class [`MakerNotePackage`](/metadata/python-net/groupdocs.metadata.standards.exif.makernote/makernotepackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
