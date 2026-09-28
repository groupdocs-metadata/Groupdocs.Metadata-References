---
title: __init__ constructor
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Initializes a new instance of the LoadOptions class."
type: docs
url: /python-net/groupdocs.metadata.options/loadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the [`LoadOptions`](/metadata/python-net/groupdocs.metadata.options/loadoptions/) class.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.metadata.options import LoadOptions

load_options = LoadOptions()
load_options.password = "123"
```

## __init__ {#file_format}

Initializes a new instance of the [`LoadOptions`](/metadata/python-net/groupdocs.metadata.options/loadoptions/) class.

```python
def __init__(self, file_format):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_format | `FileFormat` | The exact type of the file. |

### Example

```python
from groupdocs.metadata.options import LoadOptions
from groupdocs.metadata.common import FileFormat

load_options = LoadOptions(FileFormat.SPREADSHEET)
```

### See Also
* class [`LoadOptions`](/metadata/python-net/groupdocs.metadata.options/loadoptions/)
