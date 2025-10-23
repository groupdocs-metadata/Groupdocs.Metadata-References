---
title: PngInternationalTextChunk class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/
is_root: false
weight: 180
---

## PngInternationalTextChunk class

Represents international textual data extracted from a PNG image.



**Inheritance:** [`PngInternationalTextChunk`](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk) → 
[`PngCompressedTextChunk`](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk) → 
[`PngTextChunk`](/metadata/python-net/groupdocs.metadata.formats.image/pngtextchunk) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The PngInternationalTextChunk type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/count) | Gets the number of metadata properties. |
| [keyword](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/keyword) | Gets the keyword that indicates the type of information represented by the chunk. |
| [text](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/text) | Gets the actual text string represented by the chunk. |
| [compression_method](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/compression_method) | Gets the algorithm used to compress the chunk data. |
| [is_compressed](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/is_compressed) | Gets a value indicating whether the chunk is compressed. |
| [language](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/language) | Gets the human language used by the translated keyword and the text. |
| [translated_keyword](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/translated_keyword) | Gets the translated keyword that contains a translation of the keyword into the language indicated by the language property. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### See Also
* module [`groupdocs.metadata.formats.image`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`PngCompressedTextChunk`](/metadata/python-net/groupdocs.metadata.formats.image/pngcompressedtextchunk)
* class [`PngInternationalTextChunk`](/metadata/python-net/groupdocs.metadata.formats.image/pnginternationaltextchunk)
* class [`PngTextChunk`](/metadata/python-net/groupdocs.metadata.formats.image/pngtextchunk)
