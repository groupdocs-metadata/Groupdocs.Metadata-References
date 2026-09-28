---
title: get_root_package method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Gets the root package providing access to all metadata properties extracted from the file."
type: docs
url: /python-net/groupdocs.metadata/metadata/get_root_package/
is_root: false
weight: 1110
---


## get_root_package

Gets the root package providing access to all metadata properties extracted from the file.

Learn more
- [Traverse a whole metadata tree](https://docs.groupdocs.com/display/metadatanet/Traverse+a+whole+metadata+tree)

```python
def get_root_package(self):
    ...
```

**Returns:** The root package providing access to all metadata properties extracted from the file.

### Example

```python
from groupdocs.metadata import Metadata

def remove_exif_metadata():
    with Metadata("exif.jpg") as metadata:
        root = metadata.get_root_package()
        # Assigning None drops the entire EXIF package
        root.exif_package = None
        metadata.save("output.jpg")
```

### See Also
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/)
