---
title: set_properties method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Sets known metadata properties satisfying the specified predicate."
type: docs
url: /python-net/groupdocs.metadata.common/metadatapackage/set_properties/
is_root: false
weight: 1120
---


## set_properties {#predicate-value}

Sets known metadata properties satisfying the specified predicate.

Please note that GroupDocs.Metadata implicitly checks the type of each filtered property. It's impossible to set a property with a value having inappropriate type.

- [Set metadata properties](https://docs.groupdocs.com/display/metadatanet/Set+metadata+properties)

```python
def set_properties(self, predicate, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| predicate | `Func[MetadataProperty, bool]` | A function to test each metadata property for a condition. |
| value | `PropertyValue` | A new value for the filtered properties. |

**Returns:** int: The number of affected properties.

### Example

```python
from datetime import datetime

from groupdocs.metadata import Metadata
from groupdocs.metadata.common import PropertyValue
from groupdocs.metadata.tagging import Tags


def set_metadata_properties():
    with Metadata("input.vsdx") as metadata:
        property_value = PropertyValue(datetime.now())
        affected = metadata.set_properties(
            lambda p: Tags.time.created in list(p.tags)
            or Tags.time.modified in list(p.tags),
            property_value,
        )
        print(f"Properties set: {affected}")
        metadata.save("output.vsdx")
```

### See Also
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)
