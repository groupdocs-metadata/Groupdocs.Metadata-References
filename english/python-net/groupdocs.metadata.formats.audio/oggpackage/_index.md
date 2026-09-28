---
title: OggPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents a native metadata package in a OGG audio file."
type: docs
url: /python-net/groupdocs.metadata.formats.audio/oggpackage/
is_root: false
weight: 220
---


## OggPackage class

Represents a native metadata package in a OGG audio file.

Learn more:
- https://docs.groupdocs.com/display/metadatanet/Handling+metadata+in+OGG+files

The OggPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/__init__/) | Initializes a new instance of the [`OggPackage`](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/) class. |

### Methods
| Method | Description |
| :- | :- |
| [add_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties/) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [add_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains/) | Returns True if the package contains a metadata property with the specified name; otherwise, False. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains_file](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_file/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains_string](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_string/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [find_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties/) | Finds metadata properties that satisfy the specified predicate, searching recursively through all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [find_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_enumerator](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_enumerator/) | Returns an enumerator that iterates through the collection. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_file](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_file/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_string](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_string/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [remove_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/remove_properties/) | Removes metadata properties satisfying the specified predicate. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [remove_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/remove_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [sanitize](/metadata/python-net/groupdocs.metadata.common/metadatapackage/sanitize/) | Removes writable metadata properties from the package, recursively affecting all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [set_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties/) | Sets known metadata properties satisfying the specified predicate. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [set_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [update_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties/) | Updates known metadata properties that satisfy the specified predicate, recursively affecting all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [update_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### Properties
| Property | Description |
| :- | :- |
| [album](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/album/) | The collection name to which this track belongs. |
| [artist](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/artist/) | The artist generally considered responsible for the work, such as the performing band or singer for popular music, the composer for classical music, or the author of the original text for an audio book. |
| [contact](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/contact/) | The contact information for the creators or distributors of the track. |
| [copyright](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/copyright/) | The copyright attribution, e.g., '2001 Nobody's Band' or '1999 Jack Moffitt'. |
| [date](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/date/) | The date the track was recorded. |
| [description](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/description/) | The short text description of the contents. |
| [genre](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/genre/) | The short text indication of music genre. |
| [isrc](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/isrc/) | The ISRC number for the track. |
| [license](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/license/) | The license information, for example, 'All Rights Reserved', 'Any Use Permitted', a URL to a license such as a Creative Commons license (e.g., "creativecommons.org/licenses/by/4.0/"), or similar. License value. |
| [location](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/location/) | The location where track was recorded. |
| [ogg_user_comments](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/ogg_user_comments/) | The Ogg user comments contained in the metadata as a list of [`OggUserComment`](/metadata/python-net/groupdocs.metadata.formats.audio/oggusercomment/) entries. |
| [organization](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/organization/) | The name of the organization producing the track (i.e. the 'record label'). |
| [performer](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/performer/) | The artist(s) who performed the work. In classical music this would be the conductor, orchestra, soloists. In an audio book it would be the actor who did the reading. In popular music this is typically the same as the ARTIST and is omitted. |
| [title](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/title/) | The track or work name. |
| [tracknumber](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/tracknumber/) | The track number of this piece if part of a specific larger collection or album. |
| [vendor](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/vendor/) | The vendor value. |
| [version](/metadata/python-net/groupdocs.metadata.formats.audio/oggpackage/version/) | The version field may be used to differentiate multiple versions of the same track title in a single collection (e.g. remix info). |
| [count](/metadata/python-net/groupdocs.metadata.common/metadatapackage/count/) | The number of metadata properties. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [keys](/metadata/python-net/groupdocs.metadata.common/metadatapackage/keys/) | The collection of metadata property names. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [know_property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/know_property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [metadata_type](/metadata/python-net/groupdocs.metadata.common/metadatapackage/metadata_type/) | The metadata type of the package. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### Example

```python
from groupdocs.metadata import Metadata, OggRootPackage

with Metadata("input.ogg") as metadata:
    root = metadata.get_root_package(OggRootPackage)
    if root.ogg_package is not None:
        print(root.ogg_package.title)
        print(root.ogg_package.version)
        print(root.ogg_package.album)
```

### See Also
* module [`groupdocs.metadata.formats.audio`](/metadata/python-net/groupdocs.metadata.formats.audio/)
