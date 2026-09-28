---
title: detect_barcode_types method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Extracts the types of the barcodes presented in the image."
type: docs
url: /python-net/groupdocs.metadata.formats.image/jpegrootpackage/detect_barcode_types/
is_root: false
weight: 1010
---


## detect_barcode_types

Extracts the types of the barcodes presented in the image.

Learn more:
- [Working with metadata in JPEG images](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG+images)

```python
def detect_barcode_types(self):
    ...
```

**Returns:** list: An array of barcode types.

### Example

```python
from groupdocs.metadata import Metadata, Constants, JpegRootPackage

with Metadata(Constants.JpegWithBarcodes) as metadata:
    root = metadata.get_root_package(JpegRootPackage)
    barcode_types = root.detect_barcode_types()
    for barcode_type in barcode_types:
        print(barcode_type)
```

### See Also
* class [`JpegRootPackage`](/metadata/python-net/groupdocs.metadata.formats.image/jpegrootpackage/)
