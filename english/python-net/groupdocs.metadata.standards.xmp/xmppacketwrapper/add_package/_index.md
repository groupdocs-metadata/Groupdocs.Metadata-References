---
title: add_package method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Adds the package."
type: docs
url: /python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/add_package/
is_root: false
weight: 1010
---


## add_package {#package}

Adds the package.

```python
def add_package(self, package):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| package | `XmpPackage` | The XMP package to add. |

**Returns:** None.

### Example

```python
from datetime import date
from groupdocs.metadata import Metadata
from groupdocs.metadata.standards.xmp import XmpArray, XmpArrayType, XmpPackage, XmpPacketWrapper

with Metadata("input.jpg") as metadata:
    root = metadata.get_root_package()
    packet = XmpPacketWrapper()

    custom = XmpPackage("gd", "https://groupdocs.com")
    custom.set("gd:Copyright", "Copyright (C) 2026 GroupDocs. All Rights Reserved.")
    custom.set("gd:CreationDate", date.today())
    custom.set("gd:Company", XmpArray.from_(["Aspose", "GroupDocs"], XmpArrayType.ORDERED))

    packet.add_package(custom)

    root.xmp_package = packet
    metadata.save("output.jpg")
```

### See Also
* class [`XmpPacketWrapper`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/)
