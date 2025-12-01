---
title: altitude_ref property
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 150
url: /python-net/groupdocs.metadata.standards.exif/exifgpspackage/altitude_ref/
is_root: false
---

## altitude_ref property


Gets or sets the altitude used as the reference altitude. If the reference is sea level and the altitude is above sea level, 0 is given.
If the altitude is below sea level, a value of 1 is given and the altitude is indicated as an absolute value in the [`ExifGpsPackage.altitude`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage#altitude) tag.
### Definition:
```python
@property
def altitude_ref(self):
    ...
@altitude_ref.setter
def altitude_ref(self, value):
    ...
```

### See Also
* module [`groupdocs.metadata.standards.exif`](../../)
* class [`ExifGpsPackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage)
