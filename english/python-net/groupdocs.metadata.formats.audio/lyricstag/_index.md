---
title: LyricsTag class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents Lyrics3 v2.00 metadata."
type: docs
url: /python-net/groupdocs.metadata.formats.audio/lyricstag/
is_root: false
weight: 200
---


## LyricsTag class

Represents Lyrics3 v2.00 metadata.

Lyrics3 v2.00 uses fields to represent information. The data in a field can consist of ASCII characters in the range 01 to 254 according to the standard. As the ASCII character map is only defined from 00 to 128 ISO-8859-1 might be assumed. Numerical fields are 5 or 6 characters long, depending on location, and are padded with zeroes.

Learn more
- Handling the Lyrics tag (https://docs.groupdocs.com/display/metadatanet/Handling+the+Lyrics+tag)

The LyricsTag type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/__init__/) | Initializes a new instance of the [`LyricsTag`](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/) class. |

### Methods
| Method | Description |
| :- | :- |
| [get](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/get/#id) | Retrieves the value of the field with the specified id. |
| [get_file](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/get_file/) |  |
| [get_string](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/get_string/) |  |
| [remove](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/remove/#id) | Removes the field with the specified id. |
| [remove_file](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/remove_file/) |  |
| [remove_string](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/remove_string/) |  |
| [set](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/set/#field) | Adds or replaces the specified Lyrics3 field. |
| [set_lyrics_field](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/set_lyrics_field/) |  |
| [to_list](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/to_list/) | Creates a list from the package. |
| [add_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties/) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [add_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains/) | Returns True if the package contains a metadata property with the specified name; otherwise, False. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains_file](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_file/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains_string](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_string/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [find_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties/) | Finds metadata properties that satisfy the specified predicate, searching recursively through all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [find_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_enumerator](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_enumerator/) | Returns an enumerator that iterates through the collection. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
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
| [additional_info](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/additional_info/) | The additional information represented by the INF field. |
| [album](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/album/) | The album name. |
| [artist](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/artist/) | The artist name. This value is represented by the EAR field. |
| [author](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/author/) | The author of the lyrics tag. This value is represented by the AUT field. |
| [lyrics](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/lyrics/) | The lyrics, represented by the LYR field. |
| [track](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/track/) | The track title, represented by the ETT field. |
| [count](/metadata/python-net/groupdocs.metadata.common/metadatapackage/count/) | The number of metadata properties. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [keys](/metadata/python-net/groupdocs.metadata.common/metadatapackage/keys/) | The collection of metadata property names. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [know_property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/know_property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [metadata_type](/metadata/python-net/groupdocs.metadata.common/metadatapackage/metadata_type/) | The metadata type of the package. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### Example

```python
from groupdocs.metadata import Metadata, MP3RootPackage, Constants

with Metadata(Constants.MP3WithLyrics) as metadata:
    root = metadata.get_root_package(MP3RootPackage)

    if root.lyrics3_v2 is not None:
        print(root.lyrics3_v2.lyrics)
        print(root.lyrics3_v2.album)
        print(root.lyrics3_v2.artist)
        print(root.lyrics3_v2.track)

        for field in root.lyrics3_v2.to_list():
            print(f"{field.id} = {field.data}")
```

### See Also
* module [`groupdocs.metadata.formats.audio`](/metadata/python-net/groupdocs.metadata.formats.audio/)
