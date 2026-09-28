---
title: ID3V2TagFrameFlags class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents flags used in an ID3v2 tag frame."
type: docs
url: /python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/
is_root: false
weight: 140
---


## ID3V2TagFrameFlags class

Represents flags used in an ID3v2 tag frame.

The ID3V2TagFrameFlags type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [equals](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/equals/#other) | Indicates whether the current object is equal to another object of the same type. |
| [equals](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/equals/#obj) | Determines whether the specified object is equal to this instance. |
| [equals_id3v2_tag_frame_flags](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/equals_id3v2_tag_frame_flags/) |  |
| [equals_object](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/equals_object/) |  |
| [get_hash_code](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/get_hash_code/) | Returns a hash code for this instance. |

### Properties
| Property | Description |
| :- | :- |
| [compression](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/compression/) | The compression flag indicates whether the frame is compressed. |
| [data_length_indicator](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/data_length_indicator/) | The data_length_indicator property indicates whether a data length indicator has been added to the frame. |
| [encryption](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/encryption/) | The frame is encrypted flag. If True, one byte indicating the encryption method is appended to the frame header. |
| [file_alter_preservation](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/file_alter_preservation/) | The flag that tells the software what to do with this frame if it is unknown and the file, excluding the tag, is altered. |
| [grouping_identity](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/grouping_identity/) | The frame belongs to a group of frames if set to True; otherwise, it does not belong to a group. |
| [read_only](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/read_only/) | The tag that tells the software that the contents of this frame is intended to be read-only. |
| [tag_alter_preservation](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/tag_alter_preservation/) | The flag that tells the software what to do with this frame if it is unknown and the tag is altered in any way, applying to all kinds of alterations including adding more padding and reordering the frames. |
| [unsynchronisation](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/unsynchronisation/) | The value indicating whether unsynchronisation was applied to this frame. |

### See Also
* module [`groupdocs.metadata.formats.audio`](/metadata/python-net/groupdocs.metadata.formats.audio/)
