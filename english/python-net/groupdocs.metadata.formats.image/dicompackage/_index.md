---
title: DicomPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.image/dicompackage/
is_root: false
weight: 30
---

## DicomPackage class

Represents native DICOM metadata.



**Inheritance:** [`DicomPackage`](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The DicomPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/__init__/#) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/count) | Gets the number of metadata properties. |
| [header_offset](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/header_offset) | Gets the header offset. |
| [header_bytes](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/header_bytes) | Gets the header information by bytes. |
| [bits_allocated](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/bits_allocated) | Gets the bits allocated value. |
| [dicom_info](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/dicom_info) | Gets the header information of the DICOM file. |
| [blues](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/blues) | Gets the array colors of the blue. |
| [greens](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/greens) | Gets the array colors of the green. |
| [reds](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/reds) | Gets the array colors of the red. |
| [number_of_frames](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/number_of_frames) | Gets the number of frames. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.image`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`DicomPackage`](/metadata/python-net/groupdocs.metadata.formats.image/dicompackage)
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
