---
title: set_properties method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Sets known metadata properties satisfying the specified predicate."
type: docs
url: /python-net/groupdocs.metadata.common/metadatapackage/set_properties/
is_root: false
weight: 1150
---


## set_properties {#predicate-value}

Sets known metadata properties satisfying the specified predicate.

The operation is recursive, affecting all nested packages as well. This method combines the behavior of [`MetadataPackage.AddProperties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties/) and [`MetadataPackage.UpdateProperties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties/). If an existing property satisfies the predicate, its value is updated; if a known property that satisfies the predicate is missing, it is added to the package.

Please note that GroupDocs.Metadata implicitly checks the type of each filtered property. It's impossible to set a property with a value having inappropriate type.

```python
def set_properties(self, predicate, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| predicate | `Func[MetadataProperty, bool]` | A callable that receives a `MetadataProperty` and returns `bool`, used to test each metadata property for a condition. |
| value | `PropertyValue` | A `PropertyValue` representing the new value for the filtered properties. |

**Returns:** int: The number of affected properties.

### Example

```python
from datetime import datetime

from groupdocs.metadata import Metadata
from groupdocs.metadata.common import PropertyValue
from groupdocs.metadata.tagging import Tags


def set_metadata_properties():
    with Metadata("input.vsdx") as metadata:
        # The value to write into every matching property
        property_value = PropertyValue(datetime.now())
        # set_properties = add-or-update: the predicate selects the
        # "created" and "modified" date/time properties across all packages
        affected = metadata.set_properties(
            lambda p: Tags.time.created in list(p.tags)
            or Tags.time.modified in list(p.tags),
            property_value,
        )
        print(f"Properties set: {affected}")
        # Persist the changes to a new file
        metadata.save("output.vsdx")
```

### See Also
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)
