---
title: IDocumentInfo class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Provides common information about a loaded document."
type: docs
url: /python-net/groupdocs.metadata.common/idocumentinfo/
is_root: false
weight: 80
---


## IDocumentInfo class

Provides common information about a loaded document.

Learn more

- https://docs.groupdocs.com/display/metadatanet/Get+document+info

The IDocumentInfo type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [file_type](/metadata/python-net/groupdocs.metadata.common/idocumentinfo/file_type/) | The file type of the loaded document. |
| [is_encrypted](/metadata/python-net/groupdocs.metadata.common/idocumentinfo/is_encrypted/) | The property indicates whether the document is encrypted and requires a password to open. |
| [page_count](/metadata/python-net/groupdocs.metadata.common/idocumentinfo/page_count/) | The number of pages (slides, worksheets, etc) in the loaded document. |
| [pages](/metadata/python-net/groupdocs.metadata.common/idocumentinfo/pages/) | The collection of objects representing common information about the document pages (slides, worksheets, etc). |
| [size](/metadata/python-net/groupdocs.metadata.common/idocumentinfo/size/) | The size of the loaded document in bytes. |

### Example

```python
from groupdocs.metadata import Metadata, Constants, FileFormat

metadata = Metadata(Constants.InputXlsx)
if metadata.file_format != FileFormat.UNKNOWN:
    info = metadata.get_document_info()
    print(f"File format: {info.file_type.file_format}")
    print(f"File extension: {info.file_type.extension}")
    print(f"MIME Type: {info.file_type.mime_type}")
    print(f"Number of pages: {info.page_count}")
    print(f"Document size: {info.size} bytes")
    print(f"Is document encrypted: {info.is_encrypted}")
```

### See Also
* module [`groupdocs.metadata.common`](/metadata/python-net/groupdocs.metadata.common/)
