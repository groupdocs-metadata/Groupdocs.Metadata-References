---
title: Cr2AFInfoPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 30
url: /python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/
is_root: false
---

## Cr2AFInfoPackage class

Represents Canon MakerNotes tags.



**Inheritance:** [`Cr2AFInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage) → 
[`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Cr2AFInfoPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/__init__/#) | Initializes a new instance of the [`Cr2AFInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/count) | Gets the number of metadata properties. |
| [num_af_points](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/num_af_points) | Gets the NumAFPoints. |
| [valid_af_points](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/valid_af_points) | Gets the ValidAFPoints. |
| [canon_image_width](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/canon_image_width) | Gets the CanonImageWidth. |
| [canon_image_height](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/canon_image_height) | Gets the CanonImageHeight. |
| [af_image_width](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/af_image_width) | Gets the AFImageWidth. |
| [af_image_height](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/af_image_height) | Gets the AFImageHeight. |
| [af_area_width](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/af_area_width) | Gets the AFAreaWidth. |
| [af_area_height](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/af_area_height) | Gets the AFAreaHeight. |
| [af_area_x_positions](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/af_area_x_positions) | Gets the AFAreaXPositions. |
| [af_area_y_positions](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/af_area_y_positions) | Gets the AFAreaYPositions. |
| [af_points_in_focus](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/af_points_in_focus) | Gets the AFPointsInFocus. |
| [primary_af_point_af_info](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/primary_af_point_af_info) | Gets the PrimaryAFPointAFInfo. |
| [primary_af_point](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/primary_af_point) | Gets the PrimaryAFPoint. |


### Indexer
| Name | Description |
| :- | :- |
| [index] |  |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`to_list(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/to_list/#) | Creates a list from the package. |
| [`remove(self, tag_id)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/remove/#int) | Removes the property with the specified id. |
| [`set(self, tag)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/set/#groupdocs.metadata.formats.raw.tag.rawtag) | Adds or replaces the specified tag. |
| [`clear(self)`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage/clear/#) | Removes all Raw tags stored in the package. |



### See Also
* module [`groupdocs.metadata.formats.raw.cr2`](..)
* class [`Cr2AFInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfopackage)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage)
