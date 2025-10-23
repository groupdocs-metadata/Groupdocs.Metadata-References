---
title: XmpBasicPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/
is_root: false
weight: 40
---

## XmpBasicPackage class

Represents the XMP basic namespace.



**Inheritance:** [`XmpBasicPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage) → 
[`XmpPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage) → 
[`XmpMetadataContainer`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmetadatacontainer) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The XmpBasicPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/__init__/#) | Initializes a new instance of the [`XmpBasicPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/count) | Gets the number of metadata properties. |
| [prefix](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/prefix) | Gets the xmlns prefix. |
| [namespace_uri](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/namespace_uri) | Gets the namespace URI. |
| [xml_namespace](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/xml_namespace) | Gets the XML namespace. |
| [base_url](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/base_url) | Gets or sets the base URL for relative URLs in the document content.<br/>If this document contains Internet links, and those links are relative, they are relative to this base URL. |
| [create_date](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/create_date) | Gets or sets the date and time the resource was created. |
| [creator_tool](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/creator_tool) | Gets or sets the name of the tool used to create the resource. |
| [identifiers](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/identifiers) | Gets or sets an unordered array of text strings that unambiguously identify the resource within a given context. |
| [label](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/label) | Gets or sets a word or short phrase that identifies the resource as a member of a user-defined collection. |
| [metadata_date](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/metadata_date) | Gets or sets the date and time that any metadata for this resource was last changed. |
| [modify_date](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/modify_date) | Gets or sets the date and time the resource was last modified. |
| [nickname](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/nickname) | Gets or sets a short informal name for the resource. |
| [rating](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/rating) | Gets or sets a user-assigned rating for this file.<br/>The value shall be -1 or in the range [0..5], where -1 indicates “rejected” and 0 indicates “unrated”. |
| [thumbnails](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/thumbnails) | Gets or sets an array of thumbnail images for the file, which can differ in characteristics such as size or image encoding. |
| [RATING_REJECTED](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/rating_rejected) | Rating rejected value. |
| [RATING_MIN](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/rating_min) | Rating min value. |
| [RATING_MAX](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/rating_max) | Rating max value. |


### Methods
| Method | Description |
| :- | :- |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/set/#System.String-System.String) | Adds string property. |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/set/#System.String-int) | Sets integer property. |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/set/#System.String-bool) | Sets boolean property. |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/set/#System.String-System.DateTime) | Sets DateTime property. |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/set/#System.String-float) | Sets double property. |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/set/#System.String-groupdocs.metadata.standards.xmp.XmpValueBase) | Sets the value inherited from [`XmpValueBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/set/#System.String-groupdocs.metadata.standards.xmp.XmpComplexType) | Sets the value inherited from [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/set/#System.String-groupdocs.metadata.standards.xmp.XmpArray) | Sets the value inherited from [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray) . |
| [contains](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [get_xmp_representation](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/get_xmp_representation/#) | Converts the XMP value to the XML representation. |
| [remove](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/remove/#System.String) | Removes the property with the specified name. |
| [clear](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/clear/#) | Removes all XMP properties. |



### See Also
* module [`groupdocs.metadata.standards.xmp.schemes`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray)
* class [`XmpBasicPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage)
* class [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype)
* class [`XmpMetadataContainer`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmetadatacontainer)
* class [`XmpPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage)
* class [`XmpValueBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpvaluebase)
