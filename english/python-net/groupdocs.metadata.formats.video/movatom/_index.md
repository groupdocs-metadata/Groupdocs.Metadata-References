---
title: MovAtom class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.video/movatom/
is_root: false
weight: 270
---

## MovAtom class

Represents a QuickTime atom.



**Inheritance:** [`MovAtom`](/metadata/python-net/groupdocs.metadata.formats.video/movatom) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The MovAtom type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.video/movatom/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.video/movatom/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.video/movatom/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.video/movatom/count) | Gets the number of metadata properties. |
| [offset](/metadata/python-net/groupdocs.metadata.formats.video/movatom/offset) | Gets the atom offset. |
| [size](/metadata/python-net/groupdocs.metadata.formats.video/movatom/size) | Gets the atom size in bytes. |
| [long_size](/metadata/python-net/groupdocs.metadata.formats.video/movatom/long_size) | Gets the atom size in bytes. |
| [type](/metadata/python-net/groupdocs.metadata.formats.video/movatom/type) | Gets the 4-characters type. |
| [data_offset](/metadata/python-net/groupdocs.metadata.formats.video/movatom/data_offset) | Gets the data offset. |
| [data_size](/metadata/python-net/groupdocs.metadata.formats.video/movatom/data_size) | Gets the data size in bytes. |
| [has_extended_size](/metadata/python-net/groupdocs.metadata.formats.video/movatom/has_extended_size) | Gets a value indicating whether the extended size field was used to store the atom data. |
| [atoms](/metadata/python-net/groupdocs.metadata.formats.video/movatom/atoms) | Gets an array of [`MovAtom`](/metadata/python-net/groupdocs.metadata.formats.video/movatom) atoms. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.video/movatom/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.video/movatom/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.video/movatom/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.video/movatom/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.video/movatom/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.video/movatom/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.video/movatom/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.video`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`MovAtom`](/metadata/python-net/groupdocs.metadata.formats.video/movatom)
