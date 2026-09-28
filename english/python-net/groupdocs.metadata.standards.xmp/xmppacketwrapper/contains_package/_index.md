---
title: contains_package method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Determines whether a package exists in the XMP wrapper."
type: docs
url: /python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/contains_package/
is_root: false
weight: 1040
---


## contains_package {#namespace_uri}

Determines whether a package exists in the XMP wrapper.

```python
def contains_package(self, namespace_uri):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| namespace_uri | `str` | Package namespace URI. |

**Returns:** bool: True if a package with the given namespace URI is found; otherwise False.

| Raises | Description |
| :- | :- |
| `ValueError` | If `namespace_uri` is None. |

### See Also
* class [`XmpPacketWrapper`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/)
