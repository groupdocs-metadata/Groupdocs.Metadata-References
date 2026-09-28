---
title: __init__ constructor
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Initializes a new XmpPacketWrapper instance."
type: docs
url: /python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/__init__/
is_root: false
weight: 10
---


## __init__ {#header-trailer-xmp_meta}

Initializes a new XmpPacketWrapper instance.

```python
def __init__(self, header, trailer, xmp_meta):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| header | `XmpHeaderPI` | XMP header processing instruction. |
| trailer | `XmpTrailerPI` | XMP trailer processing instruction. |
| xmp_meta | `XmpMeta` | Instance of `XmpMeta`. |

### Example

```python
    from groupdocs.metadata.standards.xmp import XmpPacketWrapper

    packet = XmpPacketWrapper()
    ```

## __init__

Initializes a new instance of the [`XmpPacketWrapper`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/) class.

```python
def __init__(self):
    ...
```

### See Also
* class [`XmpPacketWrapper`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/)
