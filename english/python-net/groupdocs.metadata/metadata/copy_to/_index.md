---
title: copy_to method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Copies known metadata properties from the source package to the destination package recursively, updating existing properties and adding missing ones."
type: docs
url: /python-net/groupdocs.metadata/metadata/copy_to/
is_root: false
weight: 1030
---


## copy_to {#metadata}

Copies known metadata properties from the source package to the destination package recursively, updating existing properties and adding missing ones.

If the package types do not match, an error is returned.

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
| metadata | `MetadataPackage` | Destination metadata package (`Metadata`). |
| tags | `List[PropertyTag]` | List of property tags to copy (`list[PropertyTag]`). |

**Returns:** int: The number of affected properties.

### Example

```python
from groupdocs.metadata import Metadata, Tags

with Metadata("source.pdf") as source_metadata, Metadata("dest.pdf") as destination_metadata:
    tags = [Tags.Content.Album]  # list of PropertyTag objects
    affected = source_metadata.copy_to(destination_metadata, tags)
    print(f"Number of properties copied: {affected}")

    source_metadata.save()
```

### See Also
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/)
