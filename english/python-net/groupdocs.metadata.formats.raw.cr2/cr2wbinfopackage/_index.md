---
title: Cr2WBInfoPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/
is_root: false
weight: 290
---

## Cr2WBInfoPackage class

Represents Canon MakerNotes tags.



**Inheritance:** [`Cr2WBInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage) → 
[`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Cr2WBInfoPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/__init__/#) | Initializes a new instance of the [`Cr2WBInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/count) | Gets the number of metadata properties. |
| [wb_grbg_levels_auto](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbg_levels_auto) | Gets the WB_GRBGLevelsAuto. |
| [wb_grbg_levels_daylight](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbg_levels_daylight) | Gets the WB_GRBGLevelsDaylight. |
| [wb_grbg_levels_cloudy](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbg_levels_cloudy) | Gets the WB_GRBGLevelsCloudy. |
| [wb_grbg_levels_tungsten](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbg_levels_tungsten) | Gets the WB_GRBGLevelsTungsten. |
| [wb_grbg_levels_fluorescent](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbg_levels_fluorescent) | Gets the WB_GRBGLevelsFluorescent. |
| [wb_grbg_levels_fluor_high](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbg_levels_fluor_high) | Gets the WB_GRBGLevelsFluorHigh. |
| [wb_grbg_levels_flash](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbg_levels_flash) | Gets the WB_GRBGLevelsFlash. |
| [wb_grbg_levels_underwater](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbg_levels_underwater) | Gets the WB_GRBGLevelsUnderwater. |
| [wb_grbg_levels_custom1](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbg_levels_custom1) | Gets the WB_GRBGLevelsCustom1. |
| [wb_grbg_levels_custom2](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbg_levels_custom2) | Gets the WB_GRBGLevelsCustom2. |


### Indexer
| Name | Description |
| :- | :- |
| [index] |  |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [to_list](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/to_list/#) | Creates a list from the package. |
| [remove](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/remove/#int) | Removes the property with the specified id. |
| [set](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/set/#groupdocs.metadata.formats.raw.tag.RawTag) | Adds or replaces the specified tag. |
| [clear](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/clear/#) | Removes all Raw tags stored in the package. |



### See Also
* module [`groupdocs.metadata.formats.raw.cr2`](..)
* class [`Cr2WBInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage)
