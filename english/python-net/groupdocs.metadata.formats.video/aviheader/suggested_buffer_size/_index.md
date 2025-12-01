---
title: suggested_buffer_size property
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 210
url: /python-net/groupdocs.metadata.formats.video/aviheader/suggested_buffer_size/
is_root: false
---

## suggested_buffer_size property


Gets the suggested buffer size for reading the file.


Generally, this size should be large enough to contain the largest chunk in the file. 
If set to zero, or if it is too small, the playback software will have to reallocate memory during playback, which will reduce performance. For an interleaved file, 
the buffer size should be large enough to read an entire record, and not just a chunk.
### Definition:
```python
@property
def suggested_buffer_size(self):
    ...
```

### See Also
* module [`groupdocs.metadata.formats.video`](../../)
* class [`AviHeader`](/metadata/python-net/groupdocs.metadata.formats.video/aviheader)
