---
title: get_package method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Gets the package by namespace URI."
type: docs
url: /python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/get_package/
is_root: false
weight: 1070
---


## get_package {#namespace_uri}

Gets the package by namespace URI.

```python
def get_package(self, namespace_uri):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| namespace_uri | `str` | Package schema uri. |

**Returns:** Appropriate `XmpPackage` if package found by `namespace_uri`; otherwise None.

| Raises | Description |
| :- | :- |
| `ValueError` | Namespace URI could not be null. |

### See Also
* class [`XmpPacketWrapper`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/)
