---
title: IExif class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Defines base operations intended to work with EXIF metadata."
type: docs
url: /python-net/groupdocs.metadata.standards.exif/iexif/
is_root: false
weight: 70
---


## IExif class

Defines base operations intended to work with EXIF metadata.

Learn more:
- Working with EXIF metadata: https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata

The IExif type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [exif_package](/metadata/python-net/groupdocs.metadata.standards.exif/iexif/exif_package/) | The EXIF metadata package associated with the file. |

### Example

```python
from groupdocs.metadata import Metadata, Constants, IExif

with Metadata(Constants.TiffWithExif) as metadata:
    root = metadata.get_root_package()
    if isinstance(root, IExif) and root.exif_package is not None:
        print(root.exif_package.artist)
        print(root.exif_package.copyright)
        print(root.exif_package.image_description)
        print(root.exif_package.make)
        print(root.exif_package.model)
        print(root.exif_package.software)
        print(root.exif_package.image_width)
        print(root.exif_package.image_length)

        print(root.exif_package.exif_ifd_package.body_serial_number)
        print(root.exif_package.exif_ifd_package.camera_owner_name)
        print(root.exif_package.exif_ifd_package.user_comment)

        print(root.exif_package.gps_package.altitude)
        print(root.exif_package.gps_package.latitude_ref)
        print(root.exif_package.gps_package.longitude_ref)
```

### See Also
* module [`groupdocs.metadata.standards.exif`](/metadata/python-net/groupdocs.metadata.standards.exif/)
