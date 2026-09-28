---
title: satellites property
second_title: GroupDocs.Metadata for Python via .NET API References
description: "The GPS satellites used for measurements."
type: docs
url: /python-net/groupdocs.metadata.standards.exif/exifgpspackage/satellites/
is_root: false
weight: 2250
---


## satellites property

The GPS satellites used for measurements.

This tag can be used to describe the number of satellites, their ID number, angle of elevation, azimuth, SNR and other information in ASCII notation. The format is not specified. If the GPS receiver is incapable of taking measurements, the value shall be set to None.

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
* class [`ExifGpsPackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/)
