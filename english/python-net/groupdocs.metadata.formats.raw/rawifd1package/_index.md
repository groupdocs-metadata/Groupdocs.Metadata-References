---
title: RawIFD1Package class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.raw/rawifd1package/
is_root: false
weight: 60
---

## RawIFD1Package class

Represents IFD1 tags.



**Inheritance:** [`RawIFD1Package`](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package) → 
[`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The RawIFD1Package type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package/count) | Gets the number of metadata properties. |
| [thumbnail_offset](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package/thumbnail_offset) | Gets the ThumbnailOffset. |
| [thumbnail_lenght](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package/thumbnail_lenght) | Gets the ThumbnailLenght. |


### Indexer
| Name | Description |
| :- | :- |
| [index] |  |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [to_list](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package/to_list/#) | Creates a list from the package. |
| [remove](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package/remove/#int) | Removes the property with the specified id. |
| [set](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package/set/#groupdocs.metadata.formats.raw.tag.RawTag) | Adds or replaces the specified tag. |
| [clear](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package/clear/#) | Removes all Raw tags stored in the package. |



### See Also
* module [`groupdocs.metadata.formats.raw`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage)
* class [`RawIFD1Package`](/metadata/python-net/groupdocs.metadata.formats.raw/rawifd1package)
