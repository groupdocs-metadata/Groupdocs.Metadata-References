---
title: XmpColorantLab class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 70
url: /python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/
is_root: false
---

## XmpColorantLab class

Represents the LAB Colorant.



**Inheritance:** [`XmpColorantLab`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab) → 
[`XmpColorantBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantbase) → 
[`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype) → 
[`XmpMetadataContainer`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmetadatacontainer) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The XmpColorantLab type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/__init__/#) | Initializes a new instance of the [`XmpColorantLab`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab) class. |
| [`__init__(self, a, b, l)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/__init__/#int-int-float) | Initializes a new instance of the [`XmpColorantLab`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/count) | Gets the number of metadata properties. |
| [prefixes](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/prefixes) | Gets the namespace prefixes that are used in the [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype) instance. |
| [namespace_uris](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/namespace_uris) | Gets the namespace URIs that are used in the [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype) instance. |
| [mode](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/mode) | Gets the colour space in which the colour is defined. One of: CMYK, RGB, LAB. |
| [swatch_name](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/swatch_name) | Gets or sets the name of the swatch. |
| [color_type](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/color_type) | Gets or sets the type of color. |
| [a](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/a) | Gets or sets the A component. |
| [b](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/b) | Gets or sets the B component. |
| [l](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/l) | Gets or sets the L component. |
| [MIN_L](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/min_l) | Component L min value. |
| [MAX_L](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/max_l) | Component L max value. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`get_xmp_representation(self)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/get_xmp_representation/#) | Returns string contained value in XMP format. |
| [`get_namespace_uri(self, prefix)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab/get_namespace_uri/#system.string) | Gets the namespace URI associated with the specified prefix. |



### See Also
* module [`groupdocs.metadata.standards.xmp`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`XmpColorantBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantbase)
* class [`XmpColorantLab`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantlab)
* class [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype)
* class [`XmpMetadataContainer`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmetadatacontainer)
