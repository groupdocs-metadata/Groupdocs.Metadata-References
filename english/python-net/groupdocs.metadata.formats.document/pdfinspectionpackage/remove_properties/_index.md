---
title: remove_properties method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Removes metadata properties satisfying the specified predicate."
type: docs
url: /python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/remove_properties/
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
| predicate | `Func[MetadataProperty, bool]` | A function to test each metadata property for a condition. |

**Returns:** int: The number of affected properties.

### See Also
* class [`PdfInspectionPackage`](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/)
