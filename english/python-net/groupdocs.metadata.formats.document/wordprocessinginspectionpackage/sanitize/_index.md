---
title: sanitize method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Removes writable metadata properties from the package recursively, affecting all nested packages as well."
type: docs
url: /python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/sanitize/
is_root: false
weight: 1080
---


## sanitize

Removes writable metadata properties from the package recursively, affecting all nested packages as well.

```python
def sanitize(self):
    ...
```

**Returns:** int: The number of affected properties.

### Example

```python
    from groupdocs.metadata import Metadata

    with Metadata("input.docx") as metadata:
        removed = metadata.sanitize()
        print(f"Removed {removed} properties")
        metadata.save("output.docx")
    ```

### See Also
* class [`WordProcessingInspectionPackage`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/)
