---
title: add_properties method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Adds known metadata properties satisfying the specified predicate, recursively affecting all nested packages."
type: docs
url: /python-net/groupdocs.metadata/metadata/add_properties/
is_root: false
weight: 1010
---


## add_properties {#predicate-value}

Adds known metadata properties satisfying the specified predicate, recursively affecting all nested packages.

Learn more

- More examples demonstrating usages of this method: Adding metadata (https://docs.groupdocs.com/display/metadatanet/Adding+metadata)

```python
def add_properties(self, predicate, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| predicate | `Func[MetadataProperty, bool]` | A function to test each metadata property for a condition. |
| value | `PropertyValue` | A value for the picked properties. |

**Returns:** int: The number of affected properties.

### Example

```python
from datetime import datetime
from groupdocs.metadata import Metadata
from groupdocs.metadata.common import PropertyValue
from groupdocs.metadata.tagging import Tags

def add_missing_printed_date():
    with Metadata("input.docx") as metadata:
        property_value = PropertyValue(datetime.now())
        affected = metadata.add_properties(
            lambda p: Tags.time.printed in list(p.tags), property_value
        )
        print(f"Affected properties: {affected}")
        metadata.save("output.docx")
```

### See Also
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/)
