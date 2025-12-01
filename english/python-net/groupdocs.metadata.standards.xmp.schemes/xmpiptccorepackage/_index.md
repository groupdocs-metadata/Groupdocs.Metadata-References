---
title: XmpIptcCorePackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 80
url: /python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/
is_root: false
---

## XmpIptcCorePackage class

Represents the IPTC Core XMP package.



**Inheritance:** [`XmpIptcCorePackage`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage) → 
[`XmpPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage) → 
[`XmpMetadataContainer`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmetadatacontainer) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The XmpIptcCorePackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/__init__/#) | Initializes a new instance of the [`XmpIptcCorePackage`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/count) | Gets the number of metadata properties. |
| [prefix](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/prefix) | Gets the xmlns prefix. |
| [namespace_uri](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/namespace_uri) | Gets the namespace URI. |
| [xml_namespace](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/xml_namespace) | Gets the XML namespace. |
| [country_code](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/country_code) | Gets or sets the code of the country the content is focusing on. The code should be taken from ISO 3166 two or three letter code. |
| [intellectual_genre](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/intellectual_genre) | Gets or sets the intellectual genre. Describes the nature, intellectual, artistic or journalistic characteristic of a news object, not specifically its content. |
| [location](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/location) | Gets or sets the location the content is focusing on. |
| [scenes](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/scenes) | Gets or sets the scene of the photo content. |
| [subject_codes](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/subject_codes) | Gets or sets one or more Subjects from the IPTC "Subject-NewsCodes" taxonomy to categorize the content.Each Subject is represented as a string of 8 digits in an unordered list. |


### Methods
| Method | Description |
| :- | :- |
| [`set(self, name, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/set/#system.string-system.string) | Sets string property. |
| [`set(self, name, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/set/#system.string-int) | Sets integer property. |
| [`set(self, name, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/set/#system.string-bool) | Sets boolean property. |
| [`set(self, name, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/set/#system.string-system.datetime) | Sets DateTime property. |
| [`set(self, name, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/set/#system.string-float) | Sets double property. |
| [`set(self, name, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/set/#system.string-groupdocs.metadata.standards.xmp.xmpvaluebase) | Sets the value inherited from [`XmpValueBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [`set(self, name, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/set/#system.string-groupdocs.metadata.standards.xmp.xmpcomplextype) | Sets the value inherited from [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [`set(self, name, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/set/#system.string-groupdocs.metadata.standards.xmp.xmparray) | Sets the value inherited from [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray) . |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`get_xmp_representation(self)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/get_xmp_representation/#) | Converts the XMP value to the XML representation. |
| [`remove(self, name)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/remove/#system.string) | Removes the property with the specified name. |
| [`clear(self)`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/clear/#) | Removes all XMP properties. |



### See Also
* module [`groupdocs.metadata.standards.xmp.schemes`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray)
* class [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype)
* class [`XmpIptcCorePackage`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage)
* class [`XmpMetadataContainer`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmetadatacontainer)
* class [`XmpPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage)
* class [`XmpValueBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpvaluebase)
