---
title: import_ method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Imports the metadata properties to a file."
type: docs
url: /python-net/groupdocs.metadata.import_/importmanager/import_/
is_root: false
weight: 1010
---


## import_ {#file_path-format-import_options}

Imports the metadata properties to a file.

```python
def import_(self, file_path, format, import_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The full name of the input file. |
| format | `ImportFormat` | The format of the input file. |
| import_options | `ImportOptions` | Additional options to use when importing. |

## import_ {#stream-format-import_options}

Imports the metadata properties to a file.

```python
def import_(self, stream, format, import_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | The filestream of the input file. |
| format | `ImportFormat` | The format of the input file. |
| import_options | `ImportOptions` | Additional options to use when importing. |

### See Also
* class [`ImportManager`](/metadata/python-net/groupdocs.metadata.import_/importmanager/)
