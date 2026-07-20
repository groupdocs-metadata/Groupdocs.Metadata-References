---
title: update_properties method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Updates known metadata properties satisfying the specified predicate, recursively affecting all nested packages."
type: docs
url: /python-net/groupdocs.metadata.common/metadatapackage/update_properties/
is_root: false
weight: 1140
---


## update_properties {#predicate-value}

Updates known metadata properties satisfying the specified predicate, recursively affecting all nested packages.

Please note that GroupDocs.Metadata implicitly checks the type of each filtered property. It's impossible to update a property with a value having an inappropriate type.

- More examples demonstrating usages of this method: [Updating metadata](https://docs.groupdocs.com/display/metadatanet/Updating+metadata)

```python
def update_properties(self, predicate, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| predicate | `Func[MetadataProperty, bool]` | A function to test each metadata property for a condition. |
| value | `PropertyValue` | A new value for the filtered properties. |

**Returns:** int: The number of affected properties.

### See Also
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)
