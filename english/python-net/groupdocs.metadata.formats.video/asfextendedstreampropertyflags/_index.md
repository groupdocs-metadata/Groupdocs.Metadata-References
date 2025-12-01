---
title: AsfExtendedStreamPropertyFlags enumeration
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 320
url: /python-net/groupdocs.metadata.formats.video/asfextendedstreampropertyflags/
is_root: false
---

## AsfExtendedStreamPropertyFlags enumeration

Defines ASF extended stream property flags.



The AsfExtendedStreamPropertyFlags type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| RELIABLE | This digital media stream, if sent over a network, must be carried over a reliable data communications transport mechanism. |
| SEEKABLE | This flag should be set only if the stream is seekable. |
| NO_CLEANPOINTS | The stream does not contain any cleanpoints. |
| RESEND_LIVE_CLEANPOINTS | A stream is joined in mid-transmission, all information from the most recent<br/>cleanpoint up to the current time should be sent before normal streaming begins at the current time. |



### See Also
* module [`groupdocs.metadata.formats.video`](..)
