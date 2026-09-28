---
title: ExifPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents an EXIF metadata package (Exchangeable Image File Format)."
type: docs
url: /python-net/groupdocs.metadata.standards.exif/exifpackage/
is_root: false
weight: 60
---


## ExifPackage class

Represents an EXIF metadata package (Exchangeable Image File Format).

Learn more
- Working with EXIF metadata (https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

The ExifPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/__init__/) | Initializes a new instance of the [`ExifPackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/) class. |

### Methods
| Method | Description |
| :- | :- |
| [add_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties/) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [add_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [clear](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear/) | Removes all TIFF tags stored in the package. (inherited from [`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/)) |
| [contains](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains/) | Returns True if the package contains a metadata property with the specified name; otherwise, False. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains_file](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_file/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains_string](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_string/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [find_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties/) | Finds metadata properties that satisfy the specified predicate, searching recursively through all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [find_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/get/) |  (inherited from [`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/)) |
| [get_enumerator](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_enumerator/) | Returns an enumerator that iterates through the collection. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_file](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_file/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_string](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_string/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_tiff_tag_id](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/get_tiff_tag_id/) |  (inherited from [`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/)) |
| [remove](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove/) | Removes the property with the specified id. (inherited from [`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/)) |
| [remove_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/remove_properties/) | Removes metadata properties satisfying the specified predicate. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [remove_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/remove_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [remove_tiff_tag_id](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove_tiff_tag_id/) |  (inherited from [`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/)) |
| [sanitize](/metadata/python-net/groupdocs.metadata.common/metadatapackage/sanitize/) | Removes writable metadata properties from the package, recursively affecting all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [set](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/set/) | Adds or replaces the specified tag. (inherited from [`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/)) |
| [set_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties/) | Sets known metadata properties satisfying the specified predicate. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [set_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [set_tiff_tag](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/set_tiff_tag/) |  (inherited from [`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/)) |
| [to_list](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/to_list/) | Creates a list from the package. (inherited from [`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/)) |
| [update_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties/) | Updates known metadata properties that satisfy the specified predicate, recursively affecting all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [update_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### Properties
| Property | Description |
| :- | :- |
| [artist](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/artist/) | The name of the camera owner, photographer, or image creator. |
| [copyright](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/copyright/) | The copyright notice. |
| [date_time](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/date_time/) | The date and time of image creation. In the EXIF standard, it is the date and time the file was changed. |
| [exif_ifd_package](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/exif_ifd_package/) | The EXIF IFD data. |
| [gps_package](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/gps_package/) | The GPS data. |
| [image_description](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/image_description/) | The image description, a character string giving the title of the image. It may be a comment such as "1988 company picnic" or similar. |
| [image_length](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/image_length/) | The number of rows of image data. |
| [image_width](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/image_width/) | The number of columns of image data, equal to the number of pixels per row. |
| [make](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/make/) | The manufacturer of the recording equipment that generated the image. |
| [model](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/model/) | The model name or model number of the equipment. |
| [orientation](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/orientation/) | The orientation. |
| [software](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/software/) | The name and version of the software or firmware of the camera or image input device used to generate the image. |
| [thumbnail](/metadata/python-net/groupdocs.metadata.standards.exif/exifpackage/thumbnail/) | The image thumbnail represented as an array of bytes. |
| [count](/metadata/python-net/groupdocs.metadata.common/metadatapackage/count/) | The number of metadata properties. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [keys](/metadata/python-net/groupdocs.metadata.common/metadatapackage/keys/) | The collection of metadata property names. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [know_property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/know_property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [metadata_type](/metadata/python-net/groupdocs.metadata.common/metadatapackage/metadata_type/) | The metadata type of the package. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### Example

```python
from groupdocs.metadata import Metadata
from groupdocs.metadata.standards.exif import ExifPackage


def update_exif_properties():
    with Metadata("input.jpg") as metadata:
        root = metadata.get_root_package()
        # Create an EXIF package if the image doesn't have one yet
        if getattr(root, "exif_package", None) is None:
            root.exif_package = ExifPackage()

        # Assign top-level EXIF properties
        root.exif_package.copyright = "Copyright (C) 2026 GroupDocs. All Rights Reserved."
        root.exif_package.image_description = "test image"
        root.exif_package.software = "GroupDocs.Metadata"

        # Assign properties on the EXIF IFD sub-package
        root.exif_package.exif_ifd_package.body_serial_number = "test"
        root.exif_package.exif_ifd_package.camera_owner_name = "GroupDocs"
        root.exif_package.exif_ifd_package.user_comment = "test comment"

        # Persist the changes
        metadata.save("output.jpg")
```

### See Also
* module [`groupdocs.metadata.standards.exif`](/metadata/python-net/groupdocs.metadata.standards.exif/)
