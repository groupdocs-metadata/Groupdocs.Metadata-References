---
title: add method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Adds a frame to the tag."
type: docs
url: /python-net/groupdocs.metadata.formats.audio/id3v2tag/add/
is_root: false
weight: 1010
---


## add {#frame}

Adds a frame to the tag.

```python
def add(self, frame):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| frame | `ID3V2TagFrame` | The frame to be added to the tag. |

| Raises | Description |
| :- | :- |
| `ValueError` | The provided frame is incompatible with the existing frames of the same kind. |

### See Also
* class [`ID3V2Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/)
