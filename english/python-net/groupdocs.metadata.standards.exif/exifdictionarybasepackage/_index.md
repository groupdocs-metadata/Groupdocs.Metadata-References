---
title: ExifDictionaryBasePackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 10
url: /python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/
is_root: false
---

## ExifDictionaryBasePackage class

Provides an abstract base class for EXIF metadata dictionaries.



**Inheritance:** [`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The ExifDictionaryBasePackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/count) | Gets the number of metadata properties. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`to_list(self)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/to_list/#) | Creates a list from the package. |
| [`remove(self, tag_id)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove/#groupdocs.metadata.formats.image.tifftagid) | Removes the property with the specified id. |
| [`set(self, tag)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/set/#groupdocs.metadata.formats.image.tifftag) | Adds or replaces the specified tag. |
| [`clear(self)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear/#) | Removes all TIFF tags stored in the package. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.standards.exif`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
