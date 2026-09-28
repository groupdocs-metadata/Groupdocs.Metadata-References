---
title: remove_properties method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Removes metadata properties satisfying the specified predicate."
type: docs
url: /python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/remove_properties/
is_root: false
weight: 1030
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

def remove_author_properties(input_path, output_path):
    with Metadata(input_path) as metadata:
        affected = metadata.remove_properties(
            lambda p: p.name is not None and "author" in p.name.lower()
        )
        print(f"Removed {affected} properties")
        metadata.save(output_path)
```

### See Also
* class [`PresentationInspectionPackage`](/metadata/python-net/groupdocs.metadata.formats.document/presentationinspectionpackage/)
