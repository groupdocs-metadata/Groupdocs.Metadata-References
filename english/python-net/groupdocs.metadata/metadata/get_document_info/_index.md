---
title: get_document_info method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Gets common information about the loaded document."
type: docs
url: /python-net/groupdocs.metadata/metadata/get_document_info/
is_root: false
weight: 1100
---


## get_document_info

Gets common information about the loaded document.

Learn more:
- https://docs.groupdocs.com/display/metadatanet/Get+document+info

```python
def get_document_info(self):
    ...
```

**Returns:** GroupDocs.Metadata.IDocumentInfo: An object representing common document information.

### Example

```python
from groupdocs.metadata import Metadata

with Metadata("input.xlsx") as metadata:
    info = metadata.get_document_info()
    print(f"File format: {info.file_type.file_format}")
    print(f"File extension: {info.file_type.extension}")
    print(f"MIME Type: {info.file_type.mime_type}")
    print(f"Number of pages: {info.page_count}")
    print(f"Document size: {info.size} bytes")
    print(f"Is document encrypted: {info.is_encrypted}")
```

### See Also
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/)
