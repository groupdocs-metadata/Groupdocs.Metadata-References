---
title: remove_image_resource_package method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Removes Photoshop Image Resource metadata package."
type: docs
url: /python-net/groupdocs.metadata.formats.image/jpegrootpackage/remove_image_resource_package/
is_root: false
weight: 1020
---


## remove_image_resource_package

Removes Photoshop Image Resource metadata package.

Learn more

- https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG+images

```python
def remove_image_resource_package(self):
    ...
```

### Example

```python
from groupdocs.metadata import Metadata, Constants, JpegRootPackage

with Metadata(Constants.JpegWithIrb) as metadata:
    root = metadata.get_root_package(JpegRootPackage)
    root.remove_image_resource_package()
    metadata.save(Constants.OutputJpeg)
```

### See Also
* class [`JpegRootPackage`](/metadata/python-net/groupdocs.metadata.formats.image/jpegrootpackage/)
