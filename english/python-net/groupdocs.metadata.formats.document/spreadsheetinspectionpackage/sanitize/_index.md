---
title: sanitize method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Removes writable metadata properties from the package recursively, affecting all nested packages."
type: docs
url: /python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/sanitize/
is_root: false
weight: 1060
---


## sanitize

Removes writable metadata properties from the package recursively, affecting all nested packages.

```python
def sanitize(self):
    ...
```

**Returns:** int: The number of affected properties.

### Example

```python
    from groupdocs.metadata import Metadata

    with Metadata("input.jpg") as metadata:
        removed = metadata.sanitize()
        print(f"Removed {removed} properties")
    ```

### See Also
* class [`SpreadsheetInspectionPackage`](/metadata/python-net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/)
