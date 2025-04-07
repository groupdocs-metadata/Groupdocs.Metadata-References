---
title: additional_info property
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.audio/lyricstag/additional_info/
is_root: false
weight: 140
---

## additional_info property


Gets or sets the additional information.
This value is represented by the INF field.

### Remarks 


This is always three (3) characters long in v2.00, but might be longer in a future standard.
The first byte indicates weather or not a lyrics field is present. "1" for present and "0" for otherwise.
The second character indicates if there is a timestamp in the lyrics. Again "1" for yes and "0" for no.
The third character inhibits tracks for random selection - "1" if inhibited and "0" if not.
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
* module [`groupdocs.metadata.formats.audio`](../../)
* class [`LyricsTag`](/metadata/python-net/groupdocs.metadata.formats.audio/lyricstag)
