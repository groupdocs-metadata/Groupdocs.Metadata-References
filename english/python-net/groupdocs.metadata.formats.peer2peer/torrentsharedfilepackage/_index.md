---
title: TorrentSharedFilePackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 30
url: /python-net/groupdocs.metadata.formats.peer2peer/torrentsharedfilepackage/
is_root: false
---

## TorrentSharedFilePackage class

Represents shared file information.
Contains detailed info about each file in a torrent distribution.



**Inheritance:** [`TorrentSharedFilePackage`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentsharedfilepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The TorrentSharedFilePackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentsharedfilepackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentsharedfilepackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentsharedfilepackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentsharedfilepackage/count) | Gets the number of metadata properties. |
| [name](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentsharedfilepackage/name) | Gets the full name of the file (relative path to the file from the root torrent folder). |
| [length](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentsharedfilepackage/length) | Gets the length of the file in bytes. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentsharedfilepackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentsharedfilepackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentsharedfilepackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentsharedfilepackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentsharedfilepackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentsharedfilepackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentsharedfilepackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.peer2peer`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`TorrentSharedFilePackage`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentsharedfilepackage)
