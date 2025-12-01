---
title: XmpThumbnail class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 320
url: /python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/
is_root: false
---

## XmpThumbnail class

Represents a thumbnail image for a file.



**Inheritance:** [`XmpThumbnail`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail) → 
[`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype) → 
[`XmpMetadataContainer`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmetadatacontainer) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The XmpThumbnail type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/__init__/#) | Initializes a new instance of the [`XmpThumbnail`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail) class. |
| [`__init__(self, width, height)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/__init__/#int-int) | Initializes a new instance of the [`XmpThumbnail`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/count) | Gets the number of metadata properties. |
| [prefixes](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/prefixes) | Gets the namespace prefixes that are used in the [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype) instance. |
| [namespace_uris](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/namespace_uris) | Gets the namespace URIs that are used in the [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype) instance. |
| [width](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/width) | Gets or sets the image width in pixels. |
| [height](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/height) | Gets or sets the image height in pixels. |
| [image_base64](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/image_base64) | Gets or sets the full thumbnail image data, converted to base 64 notation. |
| [image_data](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/image_data) | Gets the image data. |
| [format](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/format) | Gets or sets the image format. Defined value: JPEG. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`get_xmp_representation(self)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/get_xmp_representation/#) | Returns string contained value in XMP format. |
| [`get_namespace_uri(self, prefix)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail/get_namespace_uri/#system.string) | Gets the namespace URI associated with the specified prefix. |



### See Also
* module [`groupdocs.metadata.standards.xmp`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype)
* class [`XmpMetadataContainer`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmetadatacontainer)
* class [`XmpThumbnail`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpthumbnail)
