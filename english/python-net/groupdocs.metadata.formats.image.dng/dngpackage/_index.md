---
title: DngPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.image.dng/dngpackage/
is_root: false
weight: 10
---

## DngPackage class

Represents native DNG metadata.



**Inheritance:** [`DngPackage`](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The DngPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/__init__/#) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/count) | Gets the number of metadata properties. |
| [camera_manufacturer](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/camera_manufacturer) | Gets the camera manufacturer. |
| [colors_count](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/colors_count) | Gets the colors. |
| [description](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/description) | Gets the description of colors (RGBG,RGBE,GMCY, or GBTG). |
| [dng_version](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/dng_version) | Gets the DNG version. |
| [filters](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/filters) | Gets the Bit mask describing the order of color pixels in the matrix. |
| [is_foveon](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/is_foveon) | Gets the is foveon matrix. |
| [model](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/model) | Gets the camera model. |
| [raw_count](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/raw_count) | Gets the number of RAW images in file (0 means that the file has not been recognized). |
| [software](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/software) | Gets the software. |
| [translation_cfa_dng](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/translation_cfa_dng) | Gets the translation array for CFA mosaic DNG format. |
| [aperture](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/aperture) | Gets the aperture. |
| [artist](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/artist) | Gets the author of image. |
| [focal_length](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/focal_length) | Gets the length of the focal. |
| [gps_data](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/gps_data) | Gets the GPS data. |
| [iso_speed](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/iso_speed) | Gets the ISO sensitivity. |
| [shot_order](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/shot_order) | Gets serial number of image. |
| [shutter_speed](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/shutter_speed) | Gets the shutter speed. |
| [timestamp](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/timestamp) | Gets the date of shooting. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.image.dng`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`DngPackage`](/metadata/python-net/groupdocs.metadata.formats.image.dng/dngpackage)
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
