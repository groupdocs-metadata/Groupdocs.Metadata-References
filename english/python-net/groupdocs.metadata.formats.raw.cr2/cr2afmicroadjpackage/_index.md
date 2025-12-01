---
title: Cr2AFMicroAdjPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 40
url: /python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/
is_root: false
---

## Cr2AFMicroAdjPackage class

Represents Canon MakerNotes tags.



**Inheritance:** [`Cr2AFMicroAdjPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage) → 
[`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Cr2AFMicroAdjPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/__init__/#) | Initializes a new instance of the [`Cr2AFMicroAdjPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/count) | Gets the number of metadata properties. |
| [af_micro_adj_mode](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/af_micro_adj_mode) | Gets the AFMicroAdjMode. |
| [af_micro_adj_value](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/af_micro_adj_value) | Gets the AFMicroAdjValue. |


### Indexer
| Name | Description |
| :- | :- |
| [index] |  |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`to_list(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/to_list/#) | Creates a list from the package. |
| [`remove(self, tag_id)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/remove/#int) | Removes the property with the specified id. |
| [`set(self, tag)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/set/#groupdocs.metadata.formats.raw.tag.rawtag) | Adds or replaces the specified tag. |
| [`clear(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage/clear/#) | Removes all Raw tags stored in the package. |



### See Also
* module [`groupdocs.metadata.formats.raw.cr2`](..)
* class [`Cr2AFMicroAdjPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afmicroadjpackage)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage)
