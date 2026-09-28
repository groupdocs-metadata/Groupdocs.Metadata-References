---
title: sanitize method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Removes writable metadata properties from the package."
type: docs
url: /python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/sanitize/
is_root: false
weight: 1050
---


## sanitize

Removes writable metadata properties from the package.

The operation is recursive so it affects all nested packages as well.

```python
def sanitize(self):
    ...
```

**Returns:** int: The number of affected properties.

### Example

```python
    with Metadata(input_path) as metadata:
        affected = metadata.sanitize()
        metadata.save(output_path)
    ```

### See Also
* class [`PresentationInspectionPackage`](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/)
