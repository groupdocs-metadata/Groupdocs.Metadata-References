---
title: ID3V2Tag class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents an ID3v2 tag."
type: docs
url: /python-net/groupdocs.metadata.formats.audio/id3v2tag/
is_root: false
weight: 120
---


## ID3V2Tag class

Represents an ID3v2 tag.

Learn more
- Handling the ID3v2 tag: https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag

The ID3V2Tag type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/__init__/) | Initializes a new ID3V2Tag instance. |

### Methods
| Method | Description |
| :- | :- |
| [add](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/add/#frame) | Adds a frame to the tag. |
| [add_id3v2_tag_frame](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/add_id3v2_tag_frame/) |  |
| [clear](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/clear/#frame_id) | Removes all frames with the specified id. |
| [clear_file](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/clear_file/) |  |
| [clear_string](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/clear_string/) |  |
| [get](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/get/#frame_id) | Gets an array of frames with the specified id. |
| [get_file](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/get_file/) |  |
| [get_string](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/get_string/) |  |
| [remove](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/remove/#frame) | Removes the specified frame from the tag. |
| [remove_attached_pictures](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/remove_attached_pictures/) | Removes all attached pictures stored in APIC frames. |
| [remove_id3v2_tag_frame](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/remove_id3v2_tag_frame/) |  |
| [set](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/set/#frame) | Removes all frames having the same id as the specified one and adds the new frame to the tag. |
| [set_id3v2_tag_frame](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/set_id3v2_tag_frame/) |  |
| [to_list](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/to_list/) | Creates a list from the package. |
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
| [album](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/album/) | The Album/Movie/Show title. |
| [artist](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/artist/) | The lead artist(s), lead performer(s), soloist(s), or performing group. This value is represented by the `TPE1` frame. |
| [attached_pictures](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/attached_pictures/) | The attached pictures directly related to the audio file. |
| [band](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/band/) | The Band/Orchestra/Accompaniment. This value is represented by the TPE2 frame. |
| [bits_per_minute](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/bits_per_minute/) | The number of beats per minute in the main part of the audio. |
| [comments](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/comments/) | The user comments stored in the COMM frame, intended for any full‑text information that does not fit in other frames. |
| [composers](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/composers/) | The composers. The names are separated with the "/" character. |
| [content_type](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/content_type/) | The content type of the ID3v2 tag. This value is represented by the TCON frame. |
| [copyright](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/copyright/) | The copyright message, represented by the TCOP frame. |
| [date](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/date/) | The recording date as a four‑character numeric string in DDMM format. Represented by the TDAT frame. |
| [encoded_by](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/encoded_by/) | The name of the person or organization that encoded the audio file. |
| [isrc](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/isrc/) | The International Standard Recording Code (ISRC) (12 characters) represented by the TSRC frame. |
| [length_in_milliseconds](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/length_in_milliseconds/) | The length of the audio file in milliseconds, represented as a numeric string. |
| [musical_key](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/musical_key/) | The musical key in which the sound starts, represented by the TKEY frame. |
| [original_album](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/original_album/) | The original album/movie/show title, represented by the TOAL frame. |
| [publisher](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/publisher/) | The name of the label or publisher. |
| [size_in_bytes](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/size_in_bytes/) | The size of the audio file in bytes, excluding the ID3v2 tag, represented as a numeric string. |
| [software_hardware](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/software_hardware/) | The used audio encoder and its settings when the file was encoded. |
| [subtitle](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/subtitle/) | The Subtitle/Description refinement, represented by the TIT3 frame. |
| [tag_size](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/tag_size/) | The size of the tag. |
| [time](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/time/) | The time of the recording as a numeric string in HHMM format. The field is always four characters long and is represented by the TIME frame. |
| [title](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/title/) | The Title/Song name/Content description, represented by the TIT2 frame. |
| [track_number](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/track_number/) | The track number of the audio file on its original recording as a numeric string. |
| [track_play_counter](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/track_play_counter/) | The number of times the file has been played. |
| [version](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/version/) | The ID3 version. |
| [year](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/year/) | The year of the recording as a numeric string. The value is always four characters long (until the year 10000) and is represented by the TYER frame. |
| [count](/metadata/python-net/groupdocs.metadata.common/metadatapackage/count/) | The number of metadata properties. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [keys](/metadata/python-net/groupdocs.metadata.common/metadatapackage/keys/) | The collection of metadata property names. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [know_property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/know_property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [metadata_type](/metadata/python-net/groupdocs.metadata.common/metadatapackage/metadata_type/) | The metadata type of the package. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### Example

```python
from groupdocs.metadata import Metadata, MP3RootPackage

with Metadata(Constants.MP3WithID3V2) as metadata:
    root = metadata.get_root_package(MP3RootPackage)

    if root.ID3V2 is not None:
        print(root.ID3V2.Album)
        print(root.ID3V2.Artist)
        print(root.ID3V2.Band)
        print(root.ID3V2.Title)
        print(root.ID3V2.Composers)
        print(root.ID3V2.Copyright)
        print(root.ID3V2.Publisher)
        print(root.ID3V2.OriginalAlbum)
        print(root.ID3V2.MusicalKey)

        if root.ID3V2.AttachedPictures:
            for picture in root.ID3V2.AttachedPictures:
                print(picture.AttachedPictureType)
                print(picture.MimeType)
                print(picture.Description)
                # ...
```

### See Also
* module [`groupdocs.metadata.formats.audio`](/metadata/python-net/groupdocs.metadata.formats.audio/)
