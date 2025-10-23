---
title: RawIFD3Package class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.raw/rawifd3package/
is_root: false
weight: 80
---

## RawIFD3Package class

Represents IFD1 tags.



**Inheritance:** [`RawIFD3Package`](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package) → 
[`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The RawIFD3Package type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/count) | Gets the number of metadata properties. |
| [image_width](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/image_width) | Gets the image width. |
| [image_height](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/image_height) | Gets the image height. |
| [compression](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/compression) | Gets the image Compression. |
| [strip_offset](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/strip_offset) | Gets the image StripOffset. |
| [strip_byte_counts](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/strip_byte_counts) | Gets the image StripByteCounts. |
| [unknown1](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/unknown1) | Gets the Unknown1. |
| [unknown2](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/unknown2) | Gets the Unknown2. |
| [unknown3](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/unknown3) | Gets the Unknown3. |
| [unknown4](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/unknown4) | Gets the Unknown4. |


### Indexer
| Name | Description |
| :- | :- |
| [index] |  |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [to_list](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/to_list/#) | Creates a list from the package. |
| [remove](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/remove/#int) | Removes the property with the specified id. |
| [set](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/set/#groupdocs.metadata.formats.raw.tag.RawTag) | Adds or replaces the specified tag. |
| [clear](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package/clear/#) | Removes all Raw tags stored in the package. |



### See Also
* module [`groupdocs.metadata.formats.raw`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage)
* class [`RawIFD3Package`](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd3package)
