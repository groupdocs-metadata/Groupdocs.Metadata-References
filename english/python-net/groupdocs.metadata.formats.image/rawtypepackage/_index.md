---
title: RawTypePackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 340
url: /python-net/groupdocs.metadata.formats.image/rawtypepackage/
is_root: false
---

## RawTypePackage class

Represents a metadata package containing image-specific file format information.



**Inheritance:** [`RawTypePackage`](/metadata/python-net/groupdocs.metadata.formats.image/rawtypepackage) → 
[`FileTypePackage`](/metadata/python-net/groupdocs.metadata.common/filetypepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The RawTypePackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.image/rawtypepackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.image/rawtypepackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.image/rawtypepackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.image/rawtypepackage/count) | Gets the number of metadata properties. |
| [file_format](/metadata/python-net/groupdocs.metadata.formats.image/rawtypepackage/file_format) | Gets the file format. |
| [mime_type](/metadata/python-net/groupdocs.metadata.formats.image/rawtypepackage/mime_type) | Gets the MIME type. |
| [extension](/metadata/python-net/groupdocs.metadata.formats.image/rawtypepackage/extension) | Gets the file extension. |
| [byte_order](/metadata/python-net/groupdocs.metadata.formats.image/rawtypepackage/byte_order) | Gets the byte-order of the image.<br/>Please see [https://en.wikipedia.org/wiki/Endianness](https://en.wikipedia.org/wiki/Endianness) for more information. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.image/rawtypepackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.image/rawtypepackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.image/rawtypepackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.image/rawtypepackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.image/rawtypepackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.image/rawtypepackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.image/rawtypepackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### See Also
* module [`groupdocs.metadata.formats.image`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`FileTypePackage`](/metadata/python-net/groupdocs.metadata.common/filetypepackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RawTypePackage`](/metadata/python-net/groupdocs.metadata.formats.image/rawtypepackage)
