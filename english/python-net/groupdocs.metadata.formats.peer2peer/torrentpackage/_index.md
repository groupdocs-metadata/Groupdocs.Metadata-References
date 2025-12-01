---
title: TorrentPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 10
url: /python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/
is_root: false
---

## TorrentPackage class

Represents torrent descriptor file metadata.
Please find more information at [https://en.wikipedia.org/wiki/Torrent_file](https://en.wikipedia.org/wiki/Torrent_file).



**Inheritance:** [`TorrentPackage`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The TorrentPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/count) | Gets the number of metadata properties. |
| [announce](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/announce) | Gets or sets the URL of the tracker. |
| [comment](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/comment) | Gets or sets the author's comment. |
| [creation_date](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/creation_date) | Gets or sets the creation date of the torrent. |
| [created_by](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/created_by) | Gets or sets the name and version of the program used to create the torrent. |
| [shared_files](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/shared_files) | Gets an array containing shared file information entries. |
| [piece_length](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/piece_length) | Gets the number of bytes in each piece. For more information please see [`TorrentPackage.pieces`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage#pieces). |
| [pieces](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/pieces) | Gets a byte array consisting of the concatenation of all 20-byte SHA1 hash values, one per piece. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.peer2peer`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`TorrentPackage`](/metadata/python-net/groupdocs.metadata.formats.peer2peer/torrentpackage)
