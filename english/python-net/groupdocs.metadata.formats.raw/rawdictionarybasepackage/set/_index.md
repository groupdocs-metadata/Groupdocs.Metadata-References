---
title: set method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Adds or replaces the specified tag."
type: docs
url: /python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage/set/
is_root: false
weight: 1060
---


## set {#tag}

Adds or replaces the specified tag.

```python
def set(self, tag):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| tag | `RawTag` | The tag to set. |

### Example

```python
from groupdocs.metadata import Metadata, Constants, RawAsciiTag

with Metadata(Constants.RawWithExif) as metadata:
    root = metadata.get_root_package()
    if isinstance(root, IExif):
        # Ensure the EXIF package exists
        if root.exif_package is None:
            root.exif_package = ExifPackage()
        # Add a known property (Artist tag)
        root.exif_package.set(RawAsciiTag(0x013B, "test artist"))
        # Add a custom property (ID may intersect with third‑party tools)
        root.exif_package.set(RawAsciiTag(65523, "custom"))
        metadata.save(Constants.OutputRaw)
```

### See Also
* class [`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage/)
