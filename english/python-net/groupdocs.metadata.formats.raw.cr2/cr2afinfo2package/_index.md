---
title: Cr2AFInfo2Package class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/
is_root: false
weight: 20
---

## Cr2AFInfo2Package class

Represents Canon MakerNotes tags.



**Inheritance:** [`Cr2AFInfo2Package`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package) → 
[`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Cr2AFInfo2Package type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/__init__/#) | Initializes a new instance of the [`Cr2AFInfo2Package`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/count) | Gets the number of metadata properties. |
| [af_info_size](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/af_info_size) | Gets the AFInfoSize. |
| [af_area_mode](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/af_area_mode) | Gets the AFAreaMode. |
| [num_af_points](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/num_af_points) | Gets the NumAFPoints. |
| [valid_af_points](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/valid_af_points) | Gets the ValidAFPoints. |
| [canon_image_width](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/canon_image_width) | Gets the CanonImageWidth. |
| [canon_image_height](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/canon_image_height) | Gets the CanonImageHeight. |
| [af_image_width](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/af_image_width) | Gets the AFImageWidth. |
| [af_image_height](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/af_image_height) | Gets the AFImageHeight. |
| [af_area_widths](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/af_area_widths) | Gets the AFAreaWidths. |
| [af_area_heights](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/af_area_heights) | Gets the AFAreaHeights. |
| [af_area_x_positions](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/af_area_x_positions) | Gets the AFAreaXPositions. |
| [af_area_y_positions](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/af_area_y_positions) | Gets the AFAreaYPositions. |
| [af_points_in_focus](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/af_points_in_focus) | Gets the AFPointsInFocus. |
| [af_points_selected](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/af_points_selected) | Gets the AFPointsSelected. |
| [primary_af_point](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/primary_af_point) | Gets the PrimaryAFPoint. |


### Indexer
| Name | Description |
| :- | :- |
| [index] |  |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [to_list](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/to_list/#) | Creates a list from the package. |
| [remove](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/remove/#int) | Removes the property with the specified id. |
| [set](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/set/#groupdocs.metadata.formats.raw.tag.RawTag) | Adds or replaces the specified tag. |
| [clear](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package/clear/#) | Removes all Raw tags stored in the package. |



### See Also
* module [`groupdocs.metadata.formats.raw.cr2`](..)
* class [`Cr2AFInfo2Package`](/metadata/python-net/groupdocs.metadata.formats.raw.cr2/cr2afinfo2package)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage)
