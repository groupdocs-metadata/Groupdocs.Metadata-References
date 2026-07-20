---
title: __init__ constructor
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Initializes a new ExportManager with the given metadata properties."
type: docs
url: /python-net/groupdocs.metadata.export/exportmanager/__init__/
is_root: false
weight: 10
---


## __init__ {#properties}

Initializes a new ExportManager with the given metadata properties.

```python
def __init__(self, properties):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| properties | `Iterable[MetadataProperty]` | Iterable[MetadataProperty] – A collection of metadata properties to be exported. |

### Example

```python
from groupdocs.metadata import Metadata
from groupdocs.metadata.export import ExportManager, ExportFormat

with Metadata("input.pdf") as metadata:
    properties = list(metadata.find_properties(lambda p: True))
    ExportManager(properties).export("export.xlsx", ExportFormat.XLSX)
```

### See Also
* class [`ExportManager`](/metadata/python-net/groupdocs.metadata.export/exportmanager/)
