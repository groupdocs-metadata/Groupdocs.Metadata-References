---
title: RawIFD2Package class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 70
url: /python-net/groupdocs.metadata.formats.raw/rawifd2package/
is_root: false
---

## RawIFD2Package class

Represents IFD1 tags.



**Inheritance:** [`RawIFD2Package`](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package) → 
[`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The RawIFD2Package type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/count) | Gets the number of metadata properties. |
| [image_width](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/image_width) | Gets the image width. |
| [image_height](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/image_height) | Gets the image height. |
| [bits_per_sample](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/bits_per_sample) | Gets the image BitsPerSample. |
| [compression](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/compression) | Gets the image Compression. |
| [photometric_interpretation](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/photometric_interpretation) | Gets the image PhotometricInterpretation. |
| [strip_offset](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/strip_offset) | Gets the image StripOffset. |
| [samples_per_pixel](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/samples_per_pixel) | Gets the SamplesPerPixel. |
| [row_per_strip](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/row_per_strip) | Gets the RowPerStrip. |
| [strip_byte_counts](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/strip_byte_counts) | Gets the StripByteCounts. |
| [planar_configuration](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/planar_configuration) | Gets the PlanarConfiguration. |
| [unknown1](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/unknown1) | Gets the Unknown1. |
| [unknown2](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/unknown2) | Gets the Unknown2. |
| [unknown3](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/unknown3) | Gets the Unknown3. |


### Indexer
| Name | Description |
| :- | :- |
| [index] |  |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`to_list(self)`](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/to_list/#) | Creates a list from the package. |
| [`remove(self, tag_id)`](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/remove/#int) | Removes the property with the specified id. |
| [`set(self, tag)`](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/set/#groupdocs.metadata.formats.raw.tag.rawtag) | Adds or replaces the specified tag. |
| [`clear(self)`](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package/clear/#) | Removes all Raw tags stored in the package. |



### See Also
* module [`groupdocs.metadata.formats.raw`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage)
* class [`RawIFD2Package`](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd2package)
