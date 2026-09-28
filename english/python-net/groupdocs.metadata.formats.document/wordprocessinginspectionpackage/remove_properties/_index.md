---
title: remove_properties method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Removes metadata properties satisfying the specified predicate."
type: docs
url: /python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/remove_properties/
is_root: false
weight: 1060
---


## remove_properties {#predicate}

Removes metadata properties satisfying the specified predicate.

```python
def remove_properties(self, predicate):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| predicate | `Func[MetadataProperty, bool]` | A function that receives a metadata property and returns True if the property should be removed. |

**Returns:** int: The number of properties that were removed.

### Example

```python
from groupdocs.metadata import Metadata

with Metadata("input.docx") as metadata:
    affected = metadata.remove_properties(
        lambda p: p.name is not None and (
            "Revision" in p.name or
            "TrackedChange" in p.name or
            "LastPrinted" in p.name
        )
    )
    print(f"Properties removed: {affected}")
    metadata.save("output.docx")
```

### See Also
* class [`WordProcessingInspectionPackage`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/)
