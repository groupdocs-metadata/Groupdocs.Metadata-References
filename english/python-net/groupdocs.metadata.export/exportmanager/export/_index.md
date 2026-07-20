---
title: export method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Exports the metadata properties to a file."
type: docs
url: /python-net/groupdocs.metadata.export/exportmanager/export/
is_root: false
weight: 1010
---


## export {#file_path-format-export_options}

Exports the metadata properties to a file.

```python
def export(self, file_path, format, export_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The full name of the output file. |
| format | `ExportFormat` | The format of the output file. |
| export_options | `ExportOptions` | Additional options to use when exporting a document. |

### Example

```python
from groupdocs.metadata import Metadata
from groupdocs.metadata.export import ExportManager, ExportFormat

with Metadata("input.pdf") as metadata:
    properties = list(metadata.find_properties(lambda p: True))
    ExportManager(properties).export("export.xlsx", ExportFormat.XLSX)
```

## export {#document-format-export_options}

Exports the metadata properties to a stream.

```python
def export(self, document, format, export_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The full name of the output file. |
| format | `ExportFormat` | The format of the output file. |
| export_options | `ExportOptions` | Additional options to use when exporting a document. |

### Example

```python
from groupdocs.metadata import Metadata
from groupdocs.metadata.export import ExportManager, ExportFormat

with Metadata("input.pdf") as metadata:
    properties = list(metadata.find_properties(lambda p: True))
    ExportManager(properties).export("export.xlsx", ExportFormat.XLSX)
```

## export {#file_path-format}

Exports the metadata properties to a file.

```python
def export(self, file_path, format):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The full name of the output file. |
| format | `ExportFormat` | The format of the output file. |

### Example

```python
from groupdocs.metadata import Metadata
from groupdocs.metadata.export import ExportManager, ExportFormat

with Metadata("input.pdf") as metadata:
    properties = list(metadata.find_properties(lambda p: True))
    ExportManager(properties).export("export.xlsx", ExportFormat.XLSX)
```

## export {#document-format}

Exports the metadata properties to a stream.

```python
def export(self, document, format):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The full name of the output file. |
| format | `ExportFormat` | The format of the output file. |

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
