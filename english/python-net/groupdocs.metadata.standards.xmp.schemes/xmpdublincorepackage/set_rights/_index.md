---
title: set_rights method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Sets the resource rights, given in a single language."
type: docs
url: /python-net/groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/set_rights/
is_root: false
weight: 1240
---


## set_rights {#rights}

Sets the resource rights, given in a single language.

```python
def set_rights(self, rights):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| rights | `str` | The rights statements to set. |

### Example

```python
with Metadata(input_path) as metadata:
    root = metadata.get_root_package()
    xmp = getattr(root, "xmp_package", None)
    if xmp is None:
        root.xmp_package = XmpPacketWrapper()
        xmp = root.xmp_package
    if xmp.schemes.dublin_core is None:
        xmp.schemes.dublin_core = XmpDublinCorePackage()
    dc = xmp.schemes.dublin_core
    dc.set_rights(copyright)
    metadata.save(output_path)
```

### See Also
* class [`XmpDublinCorePackage`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/)
