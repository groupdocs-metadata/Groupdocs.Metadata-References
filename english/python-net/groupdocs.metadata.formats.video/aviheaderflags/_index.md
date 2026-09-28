---
title: AviHeaderFlags class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "AviHeaderFlags enum — GroupDocs.Metadata for Python via .NET API reference."
type: docs
url: /python-net/groupdocs.metadata.formats.video/aviheaderflags/
is_root: false
weight: 170
---


## AviHeaderFlags class

The AviHeaderFlags type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| [HAS_INDEX](/metadata/python-net/groupdocs.metadata.formats.video/aviheaderflags/has_index/) | Indicates the AVI file has an index. |
| [MUST_USE_INDEX](/metadata/python-net/groupdocs.metadata.formats.video/aviheaderflags/must_use_index/) | Indicates that application should use the index, rather than the physical ordering of the chunks in the file, to determine the order of presentation of the data. For example, this flag could be used to create a list of frames for editing. |
| [IS_INTERLEAVED](/metadata/python-net/groupdocs.metadata.formats.video/aviheaderflags/is_interleaved/) | Indicates the AVI file is interleaved. |
| [TRUST_CK_TYPE](/metadata/python-net/groupdocs.metadata.formats.video/aviheaderflags/trust_ck_type/) | Use CKType to find key frames. |
| [WAS_CAPTURE_FILE](/metadata/python-net/groupdocs.metadata.formats.video/aviheaderflags/was_capture_file/) | Indicates the AVI file is a specially allocated file used for capturing real-time video. Applications should warn the user before writing over a file with this flag set because the user probably defragmented this file. |
| [COPYRIGHTED](/metadata/python-net/groupdocs.metadata.formats.video/aviheaderflags/copyrighted/) | Indicates the AVI file contains copyrighted data and software. When this flag is used, software should not permit the data to be duplicated. |

### See Also
* module [`groupdocs.metadata.formats.video`](/metadata/python-net/groupdocs.metadata.formats.video/)
