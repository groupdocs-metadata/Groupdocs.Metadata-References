---
title: remove_properties method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Removes metadata properties satisfying the specified predicate."
type: docs
url: /python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/remove_properties/
is_root: false
weight: 1040
---


## remove_properties {#predicate}

Removes metadata properties satisfying the specified predicate.

```python
def remove_properties(self, predicate):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| predicate | `Func[MetadataProperty, bool]` | A function to test each metadata property for a condition. |

**Returns:** int: The number of affected properties.

### Example

```python
from groupdocs.metadata import Metadata

with Metadata("input.xlsx") as metadata:
    removed = metadata.remove_properties(
        lambda p: p.name is not None and ("Revision" in p.name or "LastPrinted" in p.name)
    )
    print(f"Properties removed: {removed}")
    metadata.save("output.xlsx")
```

### See Also
* class [`SpreadsheetInspectionPackage`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/)
