---
title: Cr2ProcessingPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/
is_root: false
weight: 230
---

## Cr2ProcessingPackage class

Represents Canon MakerNotes tags.



**Inheritance:** [`Cr2ProcessingPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage) → 
[`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Cr2ProcessingPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/__init__/#) | Initializes a new instance of the [`Cr2ProcessingPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/count) | Gets the number of metadata properties. |
| [tone_curve](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/tone_curve) | Gets the ToneCurve. |
| [sharpness](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/sharpness) | Gets the Sharpness. |
| [sharpness_frequency](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/sharpness_frequency) | Gets the SharpnessFrequency. |
| [sensor_red_level](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/sensor_red_level) | Gets the SensorRedLevel. |
| [sensor_blue_level](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/sensor_blue_level) | Gets the SensorBlueLevel. |
| [white_balance_red](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/white_balance_red) | Gets the WhiteBalanceRed. |
| [white_balance_blue](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/white_balance_blue) | Gets the WhiteBalanceBlue. |
| [white_balance](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/white_balance) | Gets the WhiteBalance. |
| [color_temperature](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/color_temperature) | Gets the ColorTemperature. |
| [picture_style](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/picture_style) | Gets the PictureStyle. |
| [digital_gain](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/digital_gain) | Gets the DigitalGain. |
| [wb_shift_ab](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/wb_shift_ab) | Gets the WBShiftAB. |
| [wb_shift_gm](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/wb_shift_gm) | Gets the WBShiftGM. |


### Indexer
| Name | Description |
| :- | :- |
| [index] |  |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [to_list](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/to_list/#) | Creates a list from the package. |
| [remove](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/remove/#int) | Removes the property with the specified id. |
| [set](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/set/#groupdocs.metadata.formats.raw.tag.RawTag) | Adds or replaces the specified tag. |
| [clear](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage/clear/#) | Removes all Raw tags stored in the package. |



### See Also
* module [`groupdocs.metadata.formats.raw.cr2`](..)
* class [`Cr2ProcessingPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2processingpackage)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage)
