---
title: ID3V1Tag class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents an ID3v1 tag."
type: docs
url: /python-net/groupdocs.metadata.formats.audio/id3v1tag/
is_root: false
weight: 40
---


## ID3V1Tag class

Represents an ID3v1 tag.

ID3(v1) tag is a small chunk of extra data at the end of MP3.

Please find more information at https://id3.org/ID3v1.

Learn more

- [Handling the ID3v1 tag](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v1+tag)

The ID3V1Tag type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/__init__/) | Initializes a new instance of the ID3V1Tag class. |

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
| [album](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/album/) | The album, with a maximum length of 30 characters. |
| [artist](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/artist/) | The artist. Maximum length is 30 characters. |
| [comment](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/comment/) | The comment. Maximum length is 30 characters. |
| [genre_value](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/genre_value/) | The genre identifier. |
| [title](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/title/) | The title of the ID3v1 tag. |
| [track_number](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/track_number/) | The track number. Presented in an ID3v1.1 tag only. |
| [version](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/version/) | The ID3 version. It can be ID3 or ID3v1.1. |
| [year](/metadata/python-net/groupdocs.metadata.formats.audio/id3v1tag/year/) | The year. Maximum length is 4 characters. |
| [count](/metadata/python-net/groupdocs.metadata.common/metadatapackage/count/) | The number of metadata properties. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [keys](/metadata/python-net/groupdocs.metadata.common/metadatapackage/keys/) | The collection of metadata property names. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [know_property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/know_property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [metadata_type](/metadata/python-net/groupdocs.metadata.common/metadatapackage/metadata_type/) | The metadata type of the package. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### Example

```python
from groupdocs.metadata import Metadata, Constants, MP3RootPackage

with Metadata(Constants.MP3WithID3V1) as metadata:
    root = metadata.get_root_package(MP3RootPackage)

    if root.id3v1 is not None:
        print(root.id3v1.album)
        print(root.id3v1.artist)
        print(root.id3v1.title)
        print(root.id3v1.version)
        print(root.id3v1.comment)
```

### See Also
* module [`groupdocs.metadata.formats.audio`](/metadata/python-net/groupdocs.metadata.formats.audio/)
