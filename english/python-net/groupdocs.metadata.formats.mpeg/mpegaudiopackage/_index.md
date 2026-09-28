---
title: MpegAudioPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents MPEG audio metadata."
type: docs
url: /python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/
is_root: false
weight: 10
---


## MpegAudioPackage class

Represents MPEG audio metadata.

The MpegAudioPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/__init__/) | Initializes a new instance of the [`MpegAudioPackage`](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/) class. |

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
| [bitrate](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/bitrate/) | The bitrate. |
| [channel_mode](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/channel_mode/) | The channel mode. |
| [copyright](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/copyright/) | The copyright flag indicating whether the audio package is copyrighted. |
| [emphasis](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/emphasis/) | The emphasis. |
| [frequency](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/frequency/) | The frequency. |
| [header_position](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/header_position/) | The header offset. |
| [is_original](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/is_original/) | The original bit of the audio. |
| [is_protected](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/is_protected/) | The audio package is protected. |
| [layer](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/layer/) | The layer description. For an MP3 audio it is '3'. |
| [mode_extension_bits](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/mode_extension_bits/) | The mode extension bits. |
| [mpeg_audio_version](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/mpeg_audio_version/) | The MPEG audio version. Can be MPEG-1, MPEG-2 etc. |
| [padding_bit](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/padding_bit/) | The padding bit. |
| [private_bit](/metadata/python-net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/private_bit/) | The private bit indicating whether the audio package is private. |
| [count](/metadata/python-net/groupdocs.metadata.common/metadatapackage/count/) | The number of metadata properties. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [keys](/metadata/python-net/groupdocs.metadata.common/metadatapackage/keys/) | The collection of metadata property names. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [know_property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/know_property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [metadata_type](/metadata/python-net/groupdocs.metadata.common/metadatapackage/metadata_type/) | The metadata type of the package. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### Example

```python
from groupdocs.metadata import Metadata, Constants, MP3RootPackage

with Metadata(Constants.MP3WithID3V2) as metadata:
    root = metadata.get_root_package(MP3RootPackage)

    print(root.mpeg_audio_package.bitrate)
    print(root.mpeg_audio_package.channel_mode)
    print(root.mpeg_audio_package.emphasis)
    print(root.mpeg_audio_package.frequency)
    print(root.mpeg_audio_package.header_position)
    print(root.mpeg_audio_package.layer)
```

### See Also
* module [`groupdocs.metadata.formats.mpeg`](/metadata/python-net/groupdocs.metadata.formats.mpeg/)
