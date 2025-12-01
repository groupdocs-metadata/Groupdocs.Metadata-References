---
title: XmpColorantRgb class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 80
url: /python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/
is_root: false
---

## XmpColorantRgb class

Represents the RGB Colorant.



**Inheritance:** [`XmpColorantRgb`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb) → 
[`XmpColorantBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantbase) → 
[`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype) → 
[`XmpMetadataContainer`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmetadatacontainer) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The XmpColorantRgb type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/__init__/#) | Initializes a new instance of the [`XmpColorantRgb`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb) class. |
| [`__init__(self, red, green, blue)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/__init__/#int-int-int) | Initializes a new instance of the [`XmpColorantRgb`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/count) | Gets the number of metadata properties. |
| [prefixes](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/prefixes) | Gets the namespace prefixes that are used in the [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype) instance. |
| [namespace_uris](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/namespace_uris) | Gets the namespace URIs that are used in the [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype) instance. |
| [mode](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/mode) | Gets the colour space in which the colour is defined. One of: CMYK, RGB, LAB. |
| [swatch_name](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/swatch_name) | Gets or sets the name of the swatch. |
| [color_type](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/color_type) | Gets or sets the type of color. |
| [red](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/red) | Gets or sets the red component. |
| [green](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/green) | Gets or sets the green value. |
| [blue](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/blue) | Gets or sets the blue component. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`get_xmp_representation(self)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/get_xmp_representation/#) | Returns string contained value in XMP format. |
| [`get_namespace_uri(self, prefix)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb/get_namespace_uri/#system.string) | Gets the namespace URI associated with the specified prefix. |



### See Also
* module [`groupdocs.metadata.standards.xmp`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`XmpColorantBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantbase)
* class [`XmpColorantRgb`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantrgb)
* class [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype)
* class [`XmpMetadataContainer`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmetadatacontainer)
