---
title: ExifIfdPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.standards.exif/exififdpackage/
is_root: false
weight: 30
---

## ExifIfdPackage class

Represents the Exif Image File Directory. Exif IFD is a set of tags for recording Exif-specific attribute information.



**Inheritance:** [`ExifIfdPackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage) → 
[`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The ExifIfdPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/count) | Gets the number of metadata properties. |
| [camera_owner_name](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/camera_owner_name) | Gets or sets the camera owner's name. |
| [body_serial_number](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/body_serial_number) | Gets or sets the camera body serial number. |
| [cfa_pattern](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/cfa_pattern) | Gets or sets the color filter array (CFA) geometric pattern of the image sensor when a one-chip color area sensor is used. |
| [user_comment](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/user_comment) | Gets or sets the user comment. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [to_list](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/to_list/#) | Creates a list from the package. |
| [remove](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/remove/#groupdocs.metadata.formats.image.TiffTagID) | Removes the property with the specified id. |
| [set](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/set/#groupdocs.metadata.formats.image.TiffTag) | Adds or replaces the specified tag. |
| [clear](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage/clear/#) | Removes all TIFF tags stored in the package. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.standards.exif`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage)
* class [`ExifIfdPackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exififdpackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
