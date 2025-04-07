---
title: Cr2LogInfoPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/
is_root: false
weight: 140
---

## Cr2LogInfoPackage class

Represents Canon MakerNotes tags.



**Inheritance:** [`Cr2LogInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage) → 
[`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Cr2LogInfoPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/__init__/#) | Initializes a new instance of the [`Cr2LogInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/count) | Gets the number of metadata properties. |
| [compression_format](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/compression_format) | Gets the CompressionFormat. |
| [sharpness](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/sharpness) | Gets the Sharpness. |
| [saturation](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/saturation) | Gets the Saturation. |
| [color_tone](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/color_tone) | Gets the ColorTone. |
| [color_space2](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/color_space2) | Gets the ColorSpace2. |
| [color_matrix](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/color_matrix) | Gets the ColorMatrix. |
| [canon_log_version](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/canon_log_version) | Gets the CanonLogVersion. |


### Indexer
| Name | Description |
| :- | :- |
| [index] |  |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [to_list](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/to_list/#) | Creates a list from the package. |
| [remove](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/remove/#int) | Removes the property with the specified id. |
| [set](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/set/#groupdocs.metadata.formats.raw.tag.RawTag) | Adds or replaces the specified tag. |
| [clear](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage/clear/#) | Removes all Raw tags stored in the package. |



### See Also
* module [`groupdocs.metadata.formats.raw.cr2`](..)
* class [`Cr2LogInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2loginfopackage)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage)
