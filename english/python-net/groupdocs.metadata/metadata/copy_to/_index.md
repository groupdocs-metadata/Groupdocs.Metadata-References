---
title: copy_to method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Copy known metadata properties from source package to destination package."
type: docs
url: /python-net/groupdocs.metadata/metadata/copy_to/
is_root: false
weight: 1030
---


## copy_to {#metadata}

Copy known metadata properties from source package to destination package.

If the package types do not match, an error will be returned.

```python
def copy_to(self, metadata):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| metadata | `MetadataPackage` | A destination metadata package. |

### Example

```python
from groupdocs.metadata import Metadata

def copy_metadata():
    with Metadata("source.pdf") as source_metadata, Metadata("dest.pdf") as destination_metadata:
        source_metadata.copy_to(destination_metadata)
        source_metadata.save()
```

## copy_to {#metadata-tags}

Copy known metadata properties from source package to destination package.

If the package types do not match, an error will be returned.

```python
def copy_to(self, metadata, tags):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| metadata | `MetadataPackage` | A destination metadata package. |
| tags | `List[PropertyTag]` | A list of the tags. |

**Returns:** The number of affected properties.

### Example

```python
from groupdocs.metadata import Metadata, Tags

def copy_properties():
    with Metadata("source.pdf") as source_metadata, Metadata("dest.pdf") as destination_metadata:
        tags = [Tags.Content.Album]
        affected = source_metadata.copy_to(destination_metadata, tags)
        print(f"Affected properties: {affected}")
```

### See Also
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/)
