---
title: update_properties method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Updates known metadata properties satisfying the specified predicate; the operation is recursive and affects all nested packages as well."
type: docs
url: /python-net/groupdocs.metadata/metadata/update_properties/
is_root: false
weight: 1220
---


## update_properties {#predicate-value}

Updates known metadata properties satisfying the specified predicate; the operation is recursive and affects all nested packages as well.

Please note that GroupDocs.Metadata implicitly checks the type of each filtered property. It's impossible to update a property with a value having an inappropriate type.

- More examples demonstrating usages of this method: https://docs.groupdocs.com/display/metadatanet/Updating+metadata

```python
def update_properties(self, predicate, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| predicate | `Func[MetadataProperty, bool]` | A function to test each metadata property for a condition. |
| value | `PropertyValue` | A new value for the filtered properties. |

**Returns:** int: The number of affected properties.

### Example

```python
from datetime import datetime, timedelta
from groupdocs.metadata import Metadata, PropertyValue, Tags

def update_creation_date(file_path, output_path):
    three_days_ago = datetime.now() - timedelta(days=3)
    today = datetime.now()

    with Metadata(file_path) as metadata:
        if metadata.file_format != metadata.FileFormat.Unknown and not metadata.get_document_info().is_encrypted:
            affected = metadata.update_properties(
                lambda p: Tags.time.created in list(p.tags)
                and p.value.type == metadata.MetadataPropertyType.DateTime
                and p.value.to_struct(datetime) < three_days_ago,
                PropertyValue(today)
            )
            print(f"Affected properties: {affected}")
            metadata.save(output_path)
```

### See Also
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/)
