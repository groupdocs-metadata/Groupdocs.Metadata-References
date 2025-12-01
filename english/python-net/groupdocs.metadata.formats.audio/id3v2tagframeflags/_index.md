---
title: ID3V2TagFrameFlags class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 110
url: /python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/
is_root: false
---

## ID3V2TagFrameFlags class

Represents flags used in a ID3v2 tag frame.



The ID3V2TagFrameFlags type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [tag_alter_preservation](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/tag_alter_preservation) | Gets the flag that tells the software what to do with this frame if it is unknown and the tag is altered in any way. <br/>This applies to all kinds of alterations, <br/>including adding more padding and reordering the frames. |
| [file_alter_preservation](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/file_alter_preservation) | Gets the flag that tells the software what to do with this frame if it is unknown and the file, excluding the tag, is altered. <br/>This does not apply when the audio is completely replaced with other audio data. |
| [read_only](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/read_only) | Gets the tag that tells the software that the contents of this frame is intended to be read-only. |
| [compression](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/compression) | Gets a value indicating whether the frame is compressed. |
| [encryption](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/encryption) | Gets a value indicating whether the frame is encrypted. <br/>If set one byte indicating with which method it was encrypted will be appended to the frame header. |
| [grouping_identity](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/grouping_identity) | Gets a value indicating whether the frame belongs to a group of frames. <br/>If set a group identifier byte is added to the frame header. <br/>Every frame with the same group identifier belongs to the same group. |
| [unsynchronisation](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/unsynchronisation) | Gets a value indicating whether unsynchronisation was applied to this frame. |
| [data_length_indicator](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/data_length_indicator) | Gets a value indicating whether a data length indicator has been added to<br/>the frame. The data length indicator is the value one would write<br/>as the 'Frame length' if all of the frame format flags were<br/>zeroed, represented as a 32 bit synchsafe integer. |


### Methods
| Method | Description |
| :- | :- |
| [`equals(self, other)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframeflags/equals/#groupdocs.metadata.formats.audio.id3v2tagframeflags) | Indicates whether the current object is equal to another object of the same type. |



### See Also
* module [`groupdocs.metadata.formats.audio`](..)
