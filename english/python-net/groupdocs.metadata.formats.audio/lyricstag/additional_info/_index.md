---
title: additional_info property
second_title: GroupDocs.Metadata for Python via .NET API References
description: "The additional information represented by the INF field."
type: docs
url: /python-net/groupdocs.metadata.formats.audio/lyricstag/additional_info/
is_root: false
weight: 2010
---


## additional_info property

The additional information represented by the INF field.

This is always three (3) characters long in v2.00, but might be longer in a future standard. The first byte indicates whether a lyrics field is present. "1" for present and "0" otherwise. The second character indicates if there is a timestamp in the lyrics. "1" for yes and "0" for no. The third character inhibits tracks for random selection: "1" if inhibited and "0" if not.

### Definition:
```python
@property
def additional_info(self):
    ...
@additional_info.setter
def additional_info(self, value):
    ...
```

### See Also
* class [`LyricsTag`](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag/)
