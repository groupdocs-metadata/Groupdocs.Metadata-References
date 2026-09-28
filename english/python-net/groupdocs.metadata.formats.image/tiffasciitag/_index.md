---
title: TiffAsciiTag class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents a TIFF ASCII tag."
type: docs
url: /python-net/groupdocs.metadata.formats.image/tiffasciitag/
is_root: false
weight: 380
---


## TiffAsciiTag class

Represents a TIFF ASCII tag.

The TiffAsciiTag type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.image/tiffasciitag/__init__/#tag_id-value) | Initializes a new [`TiffAsciiTag`](/metadata/python-net/groupdocs.metadata.formats.image/tiffasciitag/) instance. |

### Properties
| Property | Description |
| :- | :- |
| [tag_value](/metadata/python-net/groupdocs.metadata.formats.image/tiffasciitag/tag_value/) | The tag value. |
| [descriptor](/metadata/python-net/groupdocs.metadata.common/metadataproperty/descriptor/) | The descriptor associated with the metadata property. (inherited from [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty/)) |
| [interpreted_value](/metadata/python-net/groupdocs.metadata.common/metadataproperty/interpreted_value/) | The interpreted property value, if available. (inherited from [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty/)) |
| [name](/metadata/python-net/groupdocs.metadata.common/metadataproperty/name/) | The property name. (inherited from [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty/)) |
| [tag_id](/metadata/python-net/groupdocs.metadata.formats.image/tifftag/tag_id/) | The tag id. (inherited from [`TiffTag`](/metadata/python-net/groupdocs.metadata.formats.image/tifftag/)) |
| [tag_type](/metadata/python-net/groupdocs.metadata.formats.image/tifftag/tag_type/) | The type of the tag. (inherited from [`TiffTag`](/metadata/python-net/groupdocs.metadata.formats.image/tifftag/)) |
| [tags](/metadata/python-net/groupdocs.metadata.common/metadataproperty/tags/) | The collection of tags associated with the property. (inherited from [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty/)) |
| [value](/metadata/python-net/groupdocs.metadata.common/metadataproperty/value/) | The property value. (inherited from [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty/)) |

### Example

```python
from groupdocs.metadata import Metadata
from groupdocs.metadata.formats.image import TiffAsciiTag, TiffTagID
from groupdocs.metadata.standards.exif import ExifPackage

def set_custom_exif_tag():
    with Metadata("exif.tiff") as metadata:
        root = metadata.get_root_package()
        if getattr(root, "exif_package", None) is None:
            root.exif_package = ExifPackage()

        root.exif_package.set(TiffAsciiTag(TiffTagID.ARTIST, "test artist"))
        root.exif_package.set(TiffAsciiTag(TiffTagID.SOFTWARE, "GroupDocs.Metadata"))

        metadata.save("output.tiff")
```

### See Also
* module [`groupdocs.metadata.formats.image`](/metadata/python-net/groupdocs.metadata.formats.image/)
