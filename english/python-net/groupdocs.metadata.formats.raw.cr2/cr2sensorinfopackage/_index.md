---
title: Cr2SensorInfoPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/
is_root: false
weight: 250
---

## Cr2SensorInfoPackage class

Represents Canon MakerNotes tags.



**Inheritance:** [`Cr2SensorInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage) → 
[`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Cr2SensorInfoPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/__init__/#) | Initializes a new instance of the [`Cr2SensorInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/count) | Gets the number of metadata properties. |
| [sensor_width](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/sensor_width) | Gets the SensorWidth. |
| [sensor_height](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/sensor_height) | Gets the SensorHeight. |
| [sensor_left_border](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/sensor_left_border) | Gets the SensorLeftBorder. |
| [sensor_top_border](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/sensor_top_border) | Gets the SensorTopBorder. |
| [sensor_right_border](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/sensor_right_border) | Gets the SensorRightBorder. |
| [sensor_bottom_border](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/sensor_bottom_border) | Gets the SensorBottomBorder. |
| [black_mask_left_border](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/black_mask_left_border) | Gets the BlackMaskLeftBorder. |
| [black_mask_top_border](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/black_mask_top_border) | Gets the BlackMaskTopBorder. |
| [black_mask_right_border](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/black_mask_right_border) | Gets the BlackMaskRightBorder. |
| [black_mask_bottom_border](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/black_mask_bottom_border) | Gets the BlackMaskBottomBorder. |


### Indexer
| Name | Description |
| :- | :- |
| [index] |  |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [to_list](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/to_list/#) | Creates a list from the package. |
| [remove](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/remove/#int) | Removes the property with the specified id. |
| [set](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/set/#groupdocs.metadata.formats.raw.tag.RawTag) | Adds or replaces the specified tag. |
| [clear](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage/clear/#) | Removes all Raw tags stored in the package. |



### See Also
* module [`groupdocs.metadata.formats.raw.cr2`](..)
* class [`Cr2SensorInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2sensorinfopackage)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage)
