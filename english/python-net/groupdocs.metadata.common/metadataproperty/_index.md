---
title: MetadataProperty class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents a metadata property."
type: docs
url: /python-net/groupdocs.metadata.common/metadataproperty/
is_root: false
weight: 120
---


## MetadataProperty class

Represents a metadata property.

The MetadataProperty type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [descriptor](/metadata/python-net/groupdocs.metadata.common/metadataproperty/descriptor/) | The descriptor associated with the metadata property. |
| [interpreted_value](/metadata/python-net/groupdocs.metadata.common/metadataproperty/interpreted_value/) | The interpreted property value, if available. |
| [name](/metadata/python-net/groupdocs.metadata.common/metadataproperty/name/) | The property name. |
| [tags](/metadata/python-net/groupdocs.metadata.common/metadataproperty/tags/) | The collection of tags associated with the property. |
| [value](/metadata/python-net/groupdocs.metadata.common/metadataproperty/value/) | The property value. |

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
* module [`groupdocs.metadata.common`](/metadata/python-net/groupdocs.metadata.common/)
