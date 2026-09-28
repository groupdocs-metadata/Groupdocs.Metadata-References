---
title: MetadataPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents base abstraction for a metadata package."
type: docs
url: /python-net/groupdocs.metadata.common/metadatapackage/
is_root: false
weight: 140
---


## MetadataPackage class

Represents base abstraction for a metadata package.

The MetadataPackage type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [add_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties/#predicate-value) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [add_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties_func/) |  |
| [contains](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains/#property_name) | Returns True if the package contains a metadata property with the specified name; otherwise, False. |
| [contains_file](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_file/) |  |
| [contains_string](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_string/) |  |
| [find_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties/#predicate) | Finds metadata properties that satisfy the specified predicate, searching recursively through all nested packages. |
| [find_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties_func/) |  |
| [get](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get/) |  |
| [get_enumerator](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_enumerator/) | Returns an enumerator that iterates through the collection. |
| [get_file](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_file/) |  |
| [get_string](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_string/) |  |
| [remove_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/remove_properties/#predicate) | Removes metadata properties satisfying the specified predicate. |
| [remove_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/remove_properties_func/) |  |
| [sanitize](/metadata/python-net/groupdocs.metadata.common/metadatapackage/sanitize/) | Removes writable metadata properties from the package, recursively affecting all nested packages. |
| [set_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties/#predicate-value) | Sets known metadata properties satisfying the specified predicate. |
| [set_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties_func/) |  |
| [update_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties/#predicate-value) | Updates known metadata properties that satisfy the specified predicate, recursively affecting all nested packages. |
| [update_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties_func/) |  |

### Properties
| Property | Description |
| :- | :- |
| [count](/metadata/python-net/groupdocs.metadata.common/metadatapackage/count/) | The number of metadata properties. |
| [keys](/metadata/python-net/groupdocs.metadata.common/metadatapackage/keys/) | The collection of metadata property names. |
| [know_property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/know_property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [metadata_type](/metadata/python-net/groupdocs.metadata.common/metadatapackage/metadata_type/) | The metadata type of the package. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |

### See Also
* module [`groupdocs.metadata.common`](/metadata/python-net/groupdocs.metadata.common/)
