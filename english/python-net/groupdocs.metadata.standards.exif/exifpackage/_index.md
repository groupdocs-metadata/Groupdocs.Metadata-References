---
title: ExifPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.standards.exif/exifpackage/
is_root: false
weight: 40
---

## ExifPackage class

Represents an EXIF metadata package (Exchangeable Image File Format).



**Inheritance:** [`ExifPackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage) → 
[`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The ExifPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/__init__/#) | Initializes a new instance of the [`ExifPackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/count) | Gets the number of metadata properties. |
| [gps_package](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/gps_package) | Gets the GPS data. |
| [exif_ifd_package](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/exif_ifd_package) | Gets the EXIF IFD data. |
| [thumbnail](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/thumbnail) | Gets the image thumbnail represented as an array of bytes. |
| [artist](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/artist) | Gets or sets the name of the camera owner, photographer or image creator. |
| [copyright](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/copyright) | Gets or sets the copyright notice. |
| [date_time](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/date_time) | Gets or sets the date and time of image creation.<br/>In the EXIF standard, it is the date and time the file was changed. |
| [image_description](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/image_description) | Gets or sets a character string giving the title of the image.<br/>It may be a comment such as "1988 company picnic" or the like. |
| [image_length](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/image_length) | Gets or sets the number of rows of image data. |
| [orientation](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/orientation) | Gets or sets the orientation. |
| [image_width](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/image_width) | Gets or sets the number of columns of image data, equal to the number of pixels per row. |
| [make](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/make) | Gets or sets the manufacturer of the recording equipment.<br/>This is the manufacturer of the DSC, scanner, video digitizer or other equipment that generated the image. |
| [model](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/model) | Gets or sets the model name or model number of the equipment.<br/>This is the model name or number of the DSC, scanner, video digitizer or other equipment that generated the image. |
| [software](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/software) | Gets or sets the name and version of the software or firmware of the camera or image input device used to generate the image. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [to_list](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/to_list/#) | Creates a list from the package. |
| [remove](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/remove/#groupdocs.metadata.formats.image.TiffTagID) | Removes the property with the specified id. |
| [set](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/set/#groupdocs.metadata.formats.image.TiffTag) | Adds or replaces the specified tag. |
| [clear](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/clear/#) | Removes all TIFF tags stored in the package. |



### Remarks 


**Learn more** |
|
 |

### Example 


This code sample demonstrates how to update common EXIF properties.

### See Also
* module [`groupdocs.metadata.standards.exif`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage)
* class [`ExifPackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
