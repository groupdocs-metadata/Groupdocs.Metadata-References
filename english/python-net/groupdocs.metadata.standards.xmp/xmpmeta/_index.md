---
title: XmpMeta class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.standards.xmp/xmpmeta/
is_root: false
weight: 200
---

## XmpMeta class

Represents xmpmeta. Optional.
The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.



**Inheritance:** [`XmpMeta`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta) → 
[`XmpElementBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpelementbase) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The XmpMeta type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/__init__/#) | Initializes a new instance of the [`XmpElementBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpelementbase) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/count) | Gets the number of metadata properties. |
| [adobe_xmp_toolkit](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/adobe_xmp_toolkit) | Gets Adobe XMP toolkit version. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_attribute](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/set_attribute/#str-str) | Adds an attribute. |
| [clear_attributes](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/clear_attributes/#) | Removes all attributes. |
| [contains_attribute](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/contains_attribute/#str) | Determines whether the element contains a specific attribute. |
| [get_attribute](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/get_attribute/#str) | Gets the attribute. |
| [get_xmp_representation](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta/get_xmp_representation/#) | Converts XMP value to the xml representation. |



### See Also
* module [`groupdocs.metadata.standards.xmp`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`XmpElementBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpelementbase)
* class [`XmpMeta`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmeta)
