---
title: IXmp class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Defines base operations intended to work with XMP metadata."
type: docs
url: /python-net/groupdocs.metadata.standards.xmp/ixmp/
is_root: false
weight: 10
---


## IXmp class

Defines base operations intended to work with XMP metadata.

Learn more:
- https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata

The IXmp type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [xmp_package](/metadata/python-net/groupdocs.metadata.standards.xmp/ixmp/xmp_package/) | The XMP metadata package. |

### Example

```python
from groupdocs.metadata import Metadata, Constants, IXmp

with Metadata(Constants.PngWithXmp) as metadata:
    root = metadata.get_root_package()
    if isinstance(root, IXmp) and root.xmp_package is not None:
        basic = root.xmp_package.schemes.xmp_basic
        if basic is not None:
            print(basic.creator_tool)
            print(basic.create_date)
            print(basic.modify_date)
            print(basic.label)
            print(basic.nickname)

        dublin = root.xmp_package.schemes.dublin_core
        if dublin is not None:
            print(dublin.format)
            print(dublin.coverage)
            print(dublin.identifier)
            print(dublin.source)

        photoshop = root.xmp_package.schemes.photoshop
        if photoshop is not None:
            print(photoshop.color_mode)
            print(photoshop.icc_profile)
            print(photoshop.country)
            print(photoshop.city)
            print(photoshop.date_created)
```

### See Also
* module [`groupdocs.metadata.standards.xmp`](/metadata/python-net/groupdocs.metadata.standards.xmp/)
