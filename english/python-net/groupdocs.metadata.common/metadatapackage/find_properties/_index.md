---
title: find_properties method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Finds metadata properties that satisfy the specified predicate, searching recursively through all nested packages."
type: docs
url: /python-net/groupdocs.metadata.common/metadatapackage/find_properties/
is_root: false
weight: 1060
---


## find_properties {#predicate}

Finds metadata properties that satisfy the specified predicate, searching recursively through all nested packages.

Learn more:
- More examples demonstrating usages of this method: https://docs.groupdocs.com/display/metadatanet/Extracting+metadata

```python
def find_properties(self, predicate):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| predicate | `Func[MetadataProperty, bool]` | A function to test each metadata property for a condition. |

**Returns:** Iterable[MetadataProperty]: An iterable containing properties from the package that satisfy the condition.

### Example

```python
result = {}
with Metadata(document_path) as metadata:
    for prop in metadata.find_properties(lambda p: p.name is not None):
        key = prop.name
        value = (
            str(prop.interpreted_value)
            if prop.interpreted_value is not None
            else (str(prop.value) if prop.value is not None else "")
        )
        result[key] = value
```

### See Also
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)
