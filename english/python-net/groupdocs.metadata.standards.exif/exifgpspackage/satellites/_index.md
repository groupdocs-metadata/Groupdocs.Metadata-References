---
title: satellites property
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 420
url: /python-net/groupdocs.metadata.standards.exif/exifgpspackage/satellites/
is_root: false
---

## satellites property


Gets or sets the GPS satellites used for measurements.
This tag can be used to describe the number of satellites,
their ID number, angle of elevation, azimuth, SNR and other information in ASCII notation. The format is not
specified. If the GPS receiver is incapable of taking measurements, value of the tag shall be set to NULL.
### Definition:
```python
@property
def satellites(self):
    ...
@satellites.setter
def satellites(self, value):
    ...
```

### See Also
* module [`groupdocs.metadata.standards.exif`](../../)
* class [`ExifGpsPackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage)
