---
title: remove_properties method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Removes metadata properties satisfying the specified predicate."
type: docs
url: /python-net/groupdocs.metadata.common/metadatapackage/remove_properties/
is_root: false
weight: 1090
---


## remove_properties {#predicate}

Removes metadata properties satisfying the specified predicate.

Learn more
- More examples demonstrating usages of this method: https://docs.groupdocs.com/display/metadatanet/Removing+metadata

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
from groupdocs.metadata.common import MetadataPropertyType
from groupdocs.metadata.tagging import Tags

def remove_metadata_properties():
    # Remove all the properties satisfying the predicate:
    #   the property carries the "author" tag, OR
    #   the property carries the "last editor" tag, OR
    #   the property is a string whose value equals "John"
    #   (to wipe any mention of John from the detected metadata)
    with Metadata("input.docx") as metadata:
        affected = metadata.remove_properties(
            lambda p: Tags.person.creator in list(p.tags)
            or Tags.person.editor in list(p.tags)
            or (p.value.type == MetadataPropertyType.STRING and str(p.value) == "John")
        )
        print(f"Properties removed: {affected}")
        metadata.save("output.docx")
```

### See Also
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)
