---
title: XmpSchemes class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Provides access to known XMP schemes."
type: docs
url: /python-net/groupdocs.metadata.standards.xmp/xmpschemes/
is_root: false
weight: 340
---


## XmpSchemes class

Provides access to known XMP schemes.

The XmpSchemes type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [basic_job_ticket](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpschemes/basic_job_ticket/) | The BasicJobTicket scheme, representing the XMP job ticket namespace. |
| [camera_raw](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpschemes/camera_raw/) | The Camera Raw scheme. Represents the camera raw namespace. |
| [dublin_core](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpschemes/dublin_core/) | The Dublin Core scheme namespace. |
| [paged_text](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpschemes/paged_text/) | The PagedText scheme, representing the paged text namespace. |
| [pdf](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpschemes/pdf/) | The PDF scheme. |
| [photoshop](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpschemes/photoshop/) | The Photoshop scheme namespace. |
| [xmp_basic](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpschemes/xmp_basic/) | The XMP basic namespace scheme. |
| [xmp_dynamic_media](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpschemes/xmp_dynamic_media/) | The XMP dynamic media scheme (the XMP dynamic media namespace). |
| [xmp_media_management](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpschemes/xmp_media_management/) | The XMP media management schema namespace. |
| [xmp_rights_management](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpschemes/xmp_rights_management/) | The XMP rights management schema namespace. |

### Example

```python
from groupdocs.metadata import Metadata, Constants

with Metadata(Constants.PngWithXmp) as metadata:
    root = metadata.get_root_package()
    if root and root.xmp_package:
        schemes = root.xmp_package.schemes

        if schemes.xmp_basic:
            print(schemes.xmp_basic.creator_tool)
            print(schemes.xmp_basic.create_date)
            print(schemes.xmp_basic.modify_date)
            print(schemes.xmp_basic.label)
            print(schemes.xmp_basic.nickname)

        if schemes.dublin_core:
            print(schemes.dublin_core.format)
            print(schemes.dublin_core.coverage)
            print(schemes.dublin_core.identifier)
            print(schemes.dublin_core.source)

        if schemes.photoshop:
            print(schemes.photoshop.color_mode)
            print(schemes.photoshop.icc_profile)
            print(schemes.photoshop.country)
            print(schemes.photoshop.city)
            print(schemes.photoshop.date_created)
```

### See Also
* module [`groupdocs.metadata.standards.xmp`](/metadata/python-net/groupdocs.metadata.standards.xmp/)
