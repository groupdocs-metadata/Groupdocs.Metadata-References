---
title: sanitize method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Removes writable metadata properties from the package."
type: docs
url: /python-net/groupdocs.metadata.formats.audio/mp3rootpackage/sanitize/
is_root: false
weight: 1020
---


## sanitize

Removes writable metadata properties from the package. The operation is recursive and also affects all nested packages.

```python
def sanitize(self):
    ...
```

**Returns:** int: The number of affected properties.

### Example

```python
from groupdocs.metadata import Metadata

def sanitize_file(input_path: str, output_path: str):
    with Metadata(input_path) as metadata:
        affected = metadata.sanitize()
        print(f"Removed {affected} properties")
        metadata.save(output_path)
```

### See Also
* class [`MP3RootPackage`](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/)
