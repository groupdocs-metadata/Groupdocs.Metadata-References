---
title: Cr2LightingOptPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 130
url: /python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/
is_root: false
---

## Cr2LightingOptPackage class

Represents Canon MakerNotes tags.



**Inheritance:** [`Cr2LightingOptPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage) → 
[`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Cr2LightingOptPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/__init__/#) | Initializes a new instance of the [`Cr2LightingOptPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/count) | Gets the number of metadata properties. |
| [size](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/size) | Gets the Size. |
| [peripheral_illumination_corr](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/peripheral_illumination_corr) | Gets the PeripheralIlluminationCorr. |
| [auto_lighting_optimizer](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/auto_lighting_optimizer) | Gets the AutoLightingOptimizer. |
| [highlight_tone_priority](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/highlight_tone_priority) | Gets the HighlightTonePriority. |
| [long_exposure_noise_reduction](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/long_exposure_noise_reduction) | Gets the LongExposureNoiseReduction. |
| [high_iso_noise_reduction](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/high_iso_noise_reduction) | Gets the HighISONoiseReduction. |
| [digital_lens_optimizer](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/digital_lens_optimizer) | Gets the DigitalLensOptimizer. |


### Indexer
| Name | Description |
| :- | :- |
| [index] |  |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`to_list(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/to_list/#) | Creates a list from the package. |
| [`remove(self, tag_id)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/remove/#int) | Removes the property with the specified id. |
| [`set(self, tag)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/set/#groupdocs.metadata.formats.raw.tag.rawtag) | Adds or replaces the specified tag. |
| [`clear(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage/clear/#) | Removes all Raw tags stored in the package. |



### See Also
* module [`groupdocs.metadata.formats.raw.cr2`](..)
* class [`Cr2LightingOptPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2lightingoptpackage)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage)
