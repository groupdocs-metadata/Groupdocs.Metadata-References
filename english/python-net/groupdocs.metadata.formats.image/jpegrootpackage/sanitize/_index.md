---
title: sanitize method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Removes writable metadata properties from the package recursively, affecting all nested packages."
type: docs
url: /python-net/groupdocs.metadata.formats.image/jpegrootpackage/sanitize/
is_root: false
weight: 1030
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

def remove_metadata(input_path, output_path):
    with Metadata(input_path) as metadata:
        removed = metadata.sanitize()
        metadata.save(output_path)
        return removed
```

### See Also
* class [`JpegRootPackage`](/metadata/python-net/groupdocs.metadata.formats.image/jpegrootpackage/)
