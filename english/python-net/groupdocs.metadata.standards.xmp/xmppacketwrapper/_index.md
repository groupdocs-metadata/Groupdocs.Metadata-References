---
title: XmpPacketWrapper class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/
is_root: false
weight: 240
---

## XmpPacketWrapper class

Contains serialized XMP package including header and trailer.
A wrapper consisting of a pair of XML processing instructions (PIs) may be placed around the rdf:RDF element.



**Inheritance:** [`XmpPacketWrapper`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The XmpPacketWrapper type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/__init__/#groupdocs.metadata.standards.xmp.XmpHeaderPI-groupdocs.metadata.standards.xmp.XmpTrailerPI-groupdocs.metadata.standards.xmp.XmpMeta) | Initializes a new instance of the [`XmpPacketWrapper`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper) class. |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/__init__/#) | Initializes a new instance of the [`XmpPacketWrapper`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/count) | Gets the number of metadata properties. |
| [header_pi](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/header_pi) | Gets or sets the header processing instruction. |
| [meta](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/meta) | Gets or sets the XMP meta. |
| [trailer_pi](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/trailer_pi) | Gets or sets the trailer processing instruction. |
| [packages](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/packages) | Gets array of [`XmpPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage) inside XMP. |
| [package_count](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/package_count) | Gets the number of packages inside the XMP structure. |
| [schemes](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/schemes) | Provides access to known XMP schemas. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [add_package](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/add_package/#groupdocs.metadata.standards.xmp.XmpPackage) | Adds the package. |
| [get_package](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/get_package/#System.String) | Gets package by namespace uri. |
| [contains_package](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/contains_package/#System.String) | Determines whether package is exist in XMP wrapper. |
| [remove_package](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/remove_package/#groupdocs.metadata.standards.xmp.XmpPackage) | Removes the specified package. |
| [clear_packages](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/clear_packages/#) | Removes all [`XmpPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage) inside XMP. |
| [get_xmp_representation](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/get_xmp_representation/#) | Returns string contained value in XMP format. |



### Remarks 


**Learn more** |
|
 |

### Example 


This example shows how to update XMP metadata properties.

### See Also
* module [`groupdocs.metadata.standards.xmp`](..)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`XmpPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage)
* class [`XmpPacketWrapper`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper)
