---
title: __init__ constructor
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Initializes a new XMP package with the specified prefix and namespace URI."
type: docs
url: /python-net/groupdocs.metadata.standards.xmp/xmppackage/__init__/
is_root: false
weight: 10
---


## __init__ {#prefix-namespace_uri}

Initializes a new XMP package with the specified prefix and namespace URI.

```python
def __init__(self, prefix, namespace_uri):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| prefix | `str` | XMP prefix, for example `dc:title`. |
| namespace_uri | `str` | Namespace URI. |

### Example

```python
    from groupdocs.metadata.standards.xmp import XmpPackage

    custom = XmpPackage("gd", "https://groupdocs.com")
    ```

### See Also
* class [`XmpPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/)
