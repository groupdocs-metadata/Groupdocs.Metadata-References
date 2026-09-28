---
title: remove_properties method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Removes metadata properties satisfying the specified predicate."
type: docs
url: /python-net/groupdocs.metadata.common/metadatapackage/remove_properties/
is_root: false
weight: 1120
---


## remove_properties {#predicate}

Removes metadata properties satisfying the specified predicate.

Learn more:
- More examples demonstrating usages of this method: https://docs.groupdocs.com/display/metadatanet/Removing+metadata

```python
def remove_properties(self, predicate):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| predicate | `Func[MetadataProperty, bool]` | A function to test each metadata property for a condition. |

**Returns:** The number of affected properties.

### Example

```python
with Metadata(input_path) as metadata:
    affected = metadata.remove_properties(
        lambda p: p.name is not None and (
            "Revision" in p.name
            or "TrackedChange" in p.name
            or "LastPrinted" in p.name
            or "TotalEditingTime" in p.name
            or "EditTime" in p.name))
    metadata.save(output_path)
    print(f"Properties removed: {affected}")
```

### See Also
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)
