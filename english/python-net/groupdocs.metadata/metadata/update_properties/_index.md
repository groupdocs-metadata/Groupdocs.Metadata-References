---
title: update_properties method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Updates known metadata properties satisfying the specified predicate."
type: docs
url: /python-net/groupdocs.metadata/metadata/update_properties/
is_root: false
weight: 1220
---


## update_properties {#predicate-value}

Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well.

Please note that GroupDocs.Metadata implicitly checks the type of each filtered property. It's impossible to update a property with a value having an inappropriate type.

```python
def update_properties(self, predicate, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| predicate | `Func[MetadataProperty, bool]` | A callable that tests each metadata property for a condition. |
| value | `PropertyValue` | A new `PropertyValue` to assign to the filtered properties. |

**Returns:** int: The number of affected properties.

### See Also
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/)
