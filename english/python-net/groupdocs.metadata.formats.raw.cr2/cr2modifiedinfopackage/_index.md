---
title: Cr2ModifiedInfoPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/
is_root: false
weight: 160
---

## Cr2ModifiedInfoPackage class

Represents Canon MakerNotes tags.



**Inheritance:** [`Cr2ModifiedInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage) → 
[`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Cr2ModifiedInfoPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/__init__/#) | Initializes a new instance of the [`Cr2ModifiedInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/count) | Gets the number of metadata properties. |
| [modified_tone_curve](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/modified_tone_curve) | Gets the ModifiedToneCurve. |
| [modified_sharpness](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/modified_sharpness) | Gets the ModifiedSharpness. |
| [modified_sharpness_freq](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/modified_sharpness_freq) | Gets the ModifiedSharpnessFreq. |
| [modified_sensor_red_level](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/modified_sensor_red_level) | Gets the ModifiedSensorRedLevel. |
| [modified_sensor_blue_level](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/modified_sensor_blue_level) | Gets the ModifiedSensorBlueLevel. |
| [modified_white_balance_red](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/modified_white_balance_red) | Gets the ModifiedWhiteBalanceRed. |
| [modified_white_balance_blue](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/modified_white_balance_blue) | Gets the ModifiedWhiteBalanceBlue. |
| [modified_white_balance](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/modified_white_balance) | Gets the ModifiedWhiteBalance. |
| [modified_color_temp](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/modified_color_temp) | Gets the ModifiedColorTemp. |
| [modified_picture_style](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/modified_picture_style) | Gets the ModifiedPictureStyle. |
| [modified_digital_gain](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/modified_digital_gain) | Gets the ModifiedDigitalGain. |


### Indexer
| Name | Description |
| :- | :- |
| [index] |  |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [to_list](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/to_list/#) | Creates a list from the package. |
| [remove](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/remove/#int) | Removes the property with the specified id. |
| [set](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/set/#groupdocs.metadata.formats.raw.tag.RawTag) | Adds or replaces the specified tag. |
| [clear](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage/clear/#) | Removes all Raw tags stored in the package. |



### See Also
* module [`groupdocs.metadata.formats.raw.cr2`](..)
* class [`Cr2ModifiedInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2modifiedinfopackage)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage)
