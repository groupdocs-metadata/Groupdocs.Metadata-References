---
title: Jpeg2000RootPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 150
url: /python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage/
is_root: false
---

## Jpeg2000RootPackage class

Represents the root package intended to work with metadata in a JPEG2000 image.



**Inheritance:** [`Jpeg2000RootPackage`](/metadata/python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage) → 
[`ImageRootPackage`](/metadata/python-net/groupdocs.metadata.formats.image/imagerootpackage) → 
[`RootMetadataPackage`](/metadata/python-net/groupdocs.metadata.common/rootmetadatapackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Jpeg2000RootPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage/count) | Gets the number of metadata properties. |
| [file_type](/metadata/python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage/file_type) | Gets the file type metadata package. |
| [xmp_package](/metadata/python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage/xmp_package) | Gets or sets the XMP metadata package. |
| [exif_package](/metadata/python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage/exif_package) | Gets or sets the EXIF metadata package. |
| [jpeg_2000_package](/metadata/python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage/jpeg_2000_package) | Gets the JPEG2000 native metadata package. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |
 |

### See Also
* module [`groupdocs.metadata.formats.image`](..)
* class [`ImageRootPackage`](/metadata/python-net/groupdocs.metadata.formats.image/imagerootpackage)
* class [`Jpeg2000RootPackage`](/metadata/python-net/groupdocs.metadata.formats.image/jpeg2000rootpackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RootMetadataPackage`](/metadata/python-net/groupdocs.metadata.common/rootmetadatapackage)
