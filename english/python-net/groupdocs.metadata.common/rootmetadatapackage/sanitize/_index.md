---
title: sanitize method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Removes writable metadata properties from the package recursively, affecting all nested packages as well."
type: docs
url: /python-net/groupdocs.metadata.common/rootmetadatapackage/sanitize/
is_root: false
weight: 1010
---


## sanitize

Removes writable metadata properties from the package recursively, affecting all nested packages as well.

Learn more:
- https://docs.groupdocs.com/display/metadatanet/Clean+metadata

```python
def sanitize(self):
    ...
```

**Returns:** int: The number of affected properties.

### Example

```python
from groupdocs.metadata import Metadata

def sanitize_file(input_path, output_path):
    with Metadata(input_path) as metadata:
        affected = metadata.sanitize()
        metadata.save(output_path)
        return affected
```

### See Also
* class [`RootMetadataPackage`](/metadata/python-net/groupdocs.metadata.common/rootmetadatapackage/)
