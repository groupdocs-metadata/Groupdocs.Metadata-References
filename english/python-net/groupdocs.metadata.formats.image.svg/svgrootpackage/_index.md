---
title: SvgRootPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/groupdocs.metadata.formats.image.svg/svgrootpackage/
is_root: false
---

## SvgRootPackage class

Represents a native metadata package in a SVG image file.



**Inheritance:** [`SvgRootPackage`](/metadata/python-net/groupdocs.metadata.formats.image.svg/svgrootpackage) → 
[`ImageRootPackage`](/metadata/python-net/groupdocs.metadata.formats.image/imagerootpackage) → 
[`RootMetadataPackage`](/metadata/python-net/groupdocs.metadata.common/rootmetadatapackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The SvgRootPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.image.svg/svgrootpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.image.svg/svgrootpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.image.svg/svgrootpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.image.svg/svgrootpackage/count) | Gets the number of metadata properties. |
| [file_type](/metadata/python-net/groupdocs.metadata.formats.image.svg/svgrootpackage/file_type) | Gets the file type metadata package. |
| [svg_package](/metadata/python-net/groupdocs.metadata.formats.image.svg/svgrootpackage/svg_package) | Gets the Svg native metadata package. |
| [xmp_package](/metadata/python-net/groupdocs.metadata.formats.image.svg/svgrootpackage/xmp_package) | Gets or sets the XMP metadata package. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.image.svg/svgrootpackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.image.svg/svgrootpackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.image.svg/svgrootpackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.image.svg/svgrootpackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.image.svg/svgrootpackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.image.svg/svgrootpackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.image.svg/svgrootpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### Example 


This code sample shows how to extract technical information from a SVG file.

### See Also
* module [`groupdocs.metadata.formats.image.svg`](..)
* class [`ImageRootPackage`](/metadata/python-net/groupdocs.metadata.formats.image/imagerootpackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RootMetadataPackage`](/metadata/python-net/groupdocs.metadata.common/rootmetadatapackage)
* class [`SvgRootPackage`](/metadata/python-net/groupdocs.metadata.formats.image.svg/svgrootpackage)
