---
title: PngCompressedTextChunk class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 170
url: /python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk/
is_root: false
---

## PngCompressedTextChunk class

Represents compressed textual data extracted from a PNG image.



**Inheritance:** [`PngCompressedTextChunk`](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk) → 
[`PngTextChunk`](/metadata/python-net/groupdocs.metadata.formats.image/pngtextchunk) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The PngCompressedTextChunk type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk/count) | Gets the number of metadata properties. |
| [keyword](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk/keyword) | Gets the keyword that indicates the type of information represented by the chunk. |
| [text](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk/text) | Gets the actual text string represented by the chunk. |
| [compression_method](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk/compression_method) | Gets the algorithm used to compress the chunk data. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### See Also
* module [`groupdocs.metadata.formats.image`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`PngCompressedTextChunk`](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk)
* class [`PngTextChunk`](/metadata/python-net/groupdocs.metadata.formats.image/pngtextchunk)
