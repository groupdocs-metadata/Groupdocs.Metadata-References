---
title: DocumentInfo class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Provides common information about a loaded document."
type: docs
url: /python-net/groupdocs.metadata.common/documentinfo/
is_root: false
weight: 30
---


## DocumentInfo class

Provides common information about a loaded document.

Learn more
- Get document info

The DocumentInfo type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [file_type](/metadata/python-net/groupdocs.metadata.common/documentinfo/file_type/) | The file type of the loaded document. |
| [is_encrypted](/metadata/python-net/groupdocs.metadata.common/documentinfo/is_encrypted/) | The property indicates whether the document is encrypted and requires a password to open. |
| [page_count](/metadata/python-net/groupdocs.metadata.common/documentinfo/page_count/) | The number of pages (slides, worksheets, etc) in the loaded document. |
| [pages](/metadata/python-net/groupdocs.metadata.common/documentinfo/pages/) | The collection of objects representing common information about the document pages (slides, worksheets, etc). |
| [size](/metadata/python-net/groupdocs.metadata.common/documentinfo/size/) | The size of the loaded document in bytes. |

### Example

```python
from groupdocs.metadata import Metadata, Constants, FileFormat

with Metadata(Constants.InputXlsx) as metadata:
    if metadata.FileFormat != FileFormat.Unknown:
        info = metadata.GetDocumentInfo()
        print(f"File format: {info.FileType.FileFormat}")
        print(f"File extension: {info.FileType.Extension}")
        print(f"MIME Type: {info.FileType.MimeType}")
        print(f"Number of pages: {info.PageCount}")
        print(f"Document size: {info.Size} bytes")
        print(f"Is document encrypted: {info.IsEncrypted}")
```

### See Also
* module [`groupdocs.metadata.common`](/metadata/python-net/groupdocs.metadata.common/)
