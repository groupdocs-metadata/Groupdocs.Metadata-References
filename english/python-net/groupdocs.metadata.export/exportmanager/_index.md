---
title: ExportManager class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Provides a set of methods that export metadata properties to various formats."
type: docs
url: /python-net/groupdocs.metadata.export/exportmanager/
is_root: false
weight: 40
---


## ExportManager class

Provides a set of methods that export metadata properties to various formats.

The ExportManager type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.export/exportmanager/__init__/#properties) | Initializes a new ExportManager with the given metadata properties. |

### Methods
| Method | Description |
| :- | :- |
| [export](/metadata/python-net/groupdocs.metadata.export/exportmanager/export/#file_path-format-export_options) | Exports the metadata properties to a file. |
| [export](/metadata/python-net/groupdocs.metadata.export/exportmanager/export/#document-format-export_options) | Exports the metadata properties to a stream. |
| [export](/metadata/python-net/groupdocs.metadata.export/exportmanager/export/#file_path-format) | Exports the metadata properties to a file. |
| [export](/metadata/python-net/groupdocs.metadata.export/exportmanager/export/#document-format) | Exports the metadata properties to a stream. |
| [export_file](/metadata/python-net/groupdocs.metadata.export/exportmanager/export_file/) |  |
| [export_stream](/metadata/python-net/groupdocs.metadata.export/exportmanager/export_stream/) |  |
| [export_streams](/metadata/python-net/groupdocs.metadata.export/exportmanager/export_streams/) |  |
| [export_string](/metadata/python-net/groupdocs.metadata.export/exportmanager/export_string/) |  |

### Example

```python
from groupdocs.metadata import Metadata
from groupdocs.metadata.export import ExportManager, ExportFormat

def exporting_metadata_properties():
    with Metadata("input.pdf") as metadata:
        # Collect the whole metadata tree as a list of properties
        properties = list(metadata.find_properties(lambda p: True))

        # Export them to an Excel workbook
        ExportManager(properties).export("export.xlsx", ExportFormat.XLSX)
        print(f"Exported {len(properties)} properties to export.xlsx")
```

### See Also
* module [`groupdocs.metadata.export`](/metadata/python-net/groupdocs.metadata.export/)
