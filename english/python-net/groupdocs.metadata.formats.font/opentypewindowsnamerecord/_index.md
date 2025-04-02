---
title: OpenTypeWindowsNameRecord class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord/
is_root: false
weight: 70
---

## OpenTypeWindowsNameRecord class

Represents the Name record table value for [`OpenTypePlatform.WINDOWS`](/metadata/python-net/groupdocs.metadata.formats.font/opentypeplatform#WINDOWS) platform.



**Inheritance:** [`OpenTypeWindowsNameRecord`](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord) → 
[`OpenTypeBaseNameRecord`](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The OpenTypeWindowsNameRecord type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord/count) | Gets the number of metadata properties. |
| [name_id](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord/name_id) | Gets the name identifier. |
| [platform](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord/platform) | Gets the platform identifier. |
| [value](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord/value) | Gets the string value of record. |
| [encoding](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord/encoding) | Gets the encoding identifier. |
| [language](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord/language) | Gets the language identifier. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.font`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`OpenTypeBaseNameRecord`](/metadata/python-net/groupdocs.metadata.formats.font/opentypebasenamerecord)
* class [`OpenTypeWindowsNameRecord`](/metadata/python-net/groupdocs.metadata.formats.font/opentypewindowsnamerecord)
