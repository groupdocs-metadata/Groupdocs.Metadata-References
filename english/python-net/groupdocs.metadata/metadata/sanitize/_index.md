---
title: sanitize method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Removes writable metadata properties from all detected packages, recursively affecting nested packages when possible."
type: docs
url: /python-net/groupdocs.metadata/metadata/sanitize/
is_root: false
weight: 1140
---


## sanitize

Removes writable metadata properties from all detected packages, recursively affecting nested packages when possible.

Learn more:
- Clean metadata (https://docs.groupdocs.com/display/metadatanet/Clean+metadata)

```python
def sanitize(self):
    ...
```

**Returns:** int: The number of affected properties.

### Example

```python
from groupdocs.metadata import Metadata

with Metadata("input.pdf") as metadata:
    removed = metadata.sanitize()
    print(f"Properties removed: {removed}")
    metadata.save("output.pdf")
```

### See Also
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/)
