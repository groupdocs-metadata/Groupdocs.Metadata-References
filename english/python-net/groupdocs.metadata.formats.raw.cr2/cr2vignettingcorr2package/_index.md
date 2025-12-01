---
title: Cr2VignettingCorr2Package class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 280
url: /python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/
is_root: false
---

## Cr2VignettingCorr2Package class

Represents Canon MakerNotes tags.



**Inheritance:** [`Cr2VignettingCorr2Package`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package) → 
[`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Cr2VignettingCorr2Package type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/__init__/#) | Initializes a new instance of the [`Cr2VignettingCorr2Package`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/count) | Gets the number of metadata properties. |
| [peripheral_lighting_setting](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/peripheral_lighting_setting) | Gets the PeripheralLightingSetting. |
| [chromatic_aberration_setting](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/chromatic_aberration_setting) | Gets the ChromaticAberrationSetting. |
| [distortion_correction_setting](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/distortion_correction_setting) | Gets the DistortionCorrectionSetting. |
| [digital_lens_optimizer_setting](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/digital_lens_optimizer_setting) | Gets the DigitalLensOptimizerSetting. |


### Indexer
| Name | Description |
| :- | :- |
| [index] |  |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`to_list(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/to_list/#) | Creates a list from the package. |
| [`remove(self, tag_id)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/remove/#int) | Removes the property with the specified id. |
| [`set(self, tag)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/set/#groupdocs.metadata.formats.raw.tag.rawtag) | Adds or replaces the specified tag. |
| [`clear(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package/clear/#) | Removes all Raw tags stored in the package. |



### See Also
* module [`groupdocs.metadata.formats.raw.cr2`](..)
* class [`Cr2VignettingCorr2Package`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2vignettingcorr2package)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage)
