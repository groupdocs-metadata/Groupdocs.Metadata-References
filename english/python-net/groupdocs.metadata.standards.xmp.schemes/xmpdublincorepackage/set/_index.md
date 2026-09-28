---
title: set method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Sets the XMP metadata property to the specified value, using the underlying XmpArray implementation."
type: docs
url: /python-net/groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/set/
is_root: false
weight: 1020
---


## set {#name-value}

Sets the XMP metadata property to the specified value, using the underlying [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray/) implementation.

```python
def set(self, name, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | XMP metadata property name. |
| value | `XmpArray` | XMP metadata property value. |

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

    xmp.schemes.dublin_core.set(
        "dc:subject",
        XmpArray.from_(list(keywords), XmpArrayType.UNORDERED))
    metadata.save(output_path)
```

### See Also
* class [`XmpDublinCorePackage`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/)
