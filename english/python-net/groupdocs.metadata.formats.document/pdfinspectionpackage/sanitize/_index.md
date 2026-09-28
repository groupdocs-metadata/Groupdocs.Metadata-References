---
title: sanitize method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Removes writable metadata properties from the package, recursively affecting all nested packages."
type: docs
url: /python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/sanitize/
is_root: false
weight: 1080
---


## sanitize

Removes writable metadata properties from the package, recursively affecting all nested packages.

```python
def sanitize(self):
    ...
```

**Returns:** int: The number of affected properties.

### Example

```python
    from groupdocs.metadata import Metadata

    with Metadata("input.pdf") as metadata:
        affected = metadata.sanitize()
        print(f"Removed {affected} properties")
        metadata.save("output.pdf")
    ```

### See Also
* class [`PdfInspectionPackage`](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/)
