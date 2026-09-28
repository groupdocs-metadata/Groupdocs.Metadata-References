---
title: __init__ constructor
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Initializes a new TiffAsciiTag instance."
type: docs
url: /python-net/groupdocs.metadata.formats.image/tiffasciitag/__init__/
is_root: false
weight: 10
---


## __init__ {#tag_id-value}

Initializes a new [`TiffAsciiTag`](/metadata/python-net/groupdocs.metadata.formats.image/tiffasciitag/) instance.

```python
def __init__(self, tag_id, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| tag_id | `TiffTagID` | The tag identifier. |
| value | `str` | The value. |

### Example

```python
from groupdocs.metadata import Metadata
from groupdocs.metadata.formats.image import TiffAsciiTag, TiffTagID
from groupdocs.metadata.standards.exif import ExifPackage

with Metadata("exif.tiff") as metadata:
    root = metadata.get_root_package()
    if getattr(root, "exif_package", None) is None:
        root.exif_package = ExifPackage()
    root.exif_package.set(TiffAsciiTag(TiffTagID.ARTIST, "test artist"))
    root.exif_package.set(TiffAsciiTag(TiffTagID.SOFTWARE, "GroupDocs.Metadata"))
    metadata.save("output.tiff")
```

### See Also
* class [`TiffAsciiTag`](/metadata/python-net/groupdocs.metadata.formats.image/tiffasciitag/)
