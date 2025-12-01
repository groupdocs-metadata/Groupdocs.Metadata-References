---
title: AviHeaderFlags enumeration
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 350
url: /python-net/groupdocs.metadata.formats.video/aviheaderflags/
is_root: false
---

## AviHeaderFlags enumeration

Represents AVI Header flags.



The AviHeaderFlags type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| HAS_INDEX | Indicates the AVI file has an index. |
| MUST_USE_INDEX | Indicates that application should use the index, rather than the physical ordering of the chunks in the file,<br/>to determine the order of presentation of the data. For example, this flag could be used to create a list of frames for editing. |
| IS_INTERLEAVED | Indicates the AVI file is interleaved. |
| TRUST_CK_TYPE | Use CKType to find key frames. |
| WAS_CAPTURE_FILE | Indicates the AVI file is a specially allocated file used for capturing real-time video.<br/>Applications should warn the user before writing over a file with this flag set because the user probably defragmented this file. |
| COPYRIGHTED | Indicates the AVI file contains copyrighted data and software.<br/>When this flag is used, software should not permit the data to be duplicated. |



### See Also
* module [`groupdocs.metadata.formats.video`](..)
