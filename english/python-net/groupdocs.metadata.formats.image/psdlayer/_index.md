---
title: PsdLayer class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.image/psdlayer/
is_root: false
weight: 220
---

## PsdLayer class

Represents a layer in a PSD file.



**Inheritance:** [`PsdLayer`](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The PsdLayer type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/count) | Gets the number of metadata properties. |
| [bits_per_pixel](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/bits_per_pixel) | Gets the bits per pixel value. |
| [channel_count](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/channel_count) | Gets the number of channels. |
| [flags](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/flags) | Gets the layer flags. |
| [length](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/length) | Gets the overall layer length in bytes. |
| [opacity](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/opacity) | Gets the layer opacity. 0 = transparent, 255 = opaque. |
| [top](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/top) | Gets the top layer position. |
| [left](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/left) | Gets the left layer position. |
| [bottom](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/bottom) | Gets the bottom layer position. |
| [right](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/right) | Gets the right layer position. |
| [height](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/height) | Gets the height. |
| [width](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/width) | Gets the width. |
| [name](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/name) | Gets the layer name. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.image`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`PsdLayer`](/metadata/python-net/groupdocs.metadata.formats.image/psdlayer)
