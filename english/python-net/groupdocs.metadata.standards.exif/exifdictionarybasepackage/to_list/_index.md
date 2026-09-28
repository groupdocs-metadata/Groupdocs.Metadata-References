---
title: to_list method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Creates a list from the package."
type: docs
url: /python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/to_list/
is_root: false
weight: 1080
---


## to_list

Creates a list from the package.

```python
def to_list(self):
    ...
```

**Returns:** list[GroupDocs.Metadata.Standards.Exif.TiffTag]: A list that contains all TIFF tags from the package.

### Example

```python
from groupdocs.metadata import Metadata

with Metadata("exif.jpg") as metadata:
    root = metadata.get_root_package()
    exif = getattr(root, "exif_package", None)
    if exif is not None:
        for tag in exif.to_list():
            print(f"{tag.tag_id} = {tag.value}")
```

### See Also
* class [`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/)
