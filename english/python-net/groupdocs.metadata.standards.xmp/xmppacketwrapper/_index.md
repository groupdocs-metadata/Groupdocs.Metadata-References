---
title: XmpPacketWrapper class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Contains serialized XMP package including header and trailer."
type: docs
url: /python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/
is_root: false
weight: 280
---


## XmpPacketWrapper class

Contains serialized XMP package including header and trailer. A wrapper consisting of a pair of XML processing instructions (PIs) may be placed around the rdf:RDF element.

Learn more:
- [Working with XMP metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

The XmpPacketWrapper type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/__init__/#header-trailer-xmp_meta) | Initializes a new XmpPacketWrapper instance. |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/__init__/) | Initializes a new instance of the [`XmpPacketWrapper`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/) class. |

### Methods
| Method | Description |
| :- | :- |
| [add_package](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/add_package/#package) | Adds the package. |
| [add_package_xmp_package](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/add_package_xmp_package/) |  |
| [clear_packages](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/clear_packages/) | Removes all [`XmpPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/) inside XMP. |
| [contains_package](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/contains_package/#namespace_uri) | Determines whether a package exists in the XMP wrapper. |
| [contains_package_file](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/contains_package_file/) |  |
| [contains_package_string](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/contains_package_string/) |  |
| [get_package](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/get_package/#namespace_uri) | Gets the package by namespace URI. |
| [get_package_file](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/get_package_file/) |  |
| [get_package_string](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/get_package_string/) |  |
| [get_xmp_representation](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/get_xmp_representation/) | Returns the XMP representation as a string. |
| [remove_package](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/remove_package/#package) | Removes the specified package. |
| [remove_package_xmp_package](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/remove_package_xmp_package/) |  |
| [add_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties/) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [add_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains/) | Returns True if the package contains a metadata property with the specified name; otherwise, False. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains_file](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_file/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains_string](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_string/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [find_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties/) | Finds metadata properties that satisfy the specified predicate, searching recursively through all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [find_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_enumerator](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_enumerator/) | Returns an enumerator that iterates through the collection. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_file](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_file/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_string](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_string/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [remove_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/remove_properties/) | Removes metadata properties satisfying the specified predicate. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [remove_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/remove_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [sanitize](/metadata/python-net/groupdocs.metadata.common/metadatapackage/sanitize/) | Removes writable metadata properties from the package, recursively affecting all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [set_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties/) | Sets known metadata properties satisfying the specified predicate. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [set_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [update_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties/) | Updates known metadata properties that satisfy the specified predicate, recursively affecting all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [update_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### Properties
| Property | Description |
| :- | :- |
| [header_pi](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/header_pi/) | The header processing instruction. |
| [meta](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/meta/) | The XMP meta. |
| [package_count](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/package_count/) | The number of packages inside the XMP structure. |
| [packages](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/packages/) | The XMP packages contained in the packet. |
| [schemes](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/schemes/) | The XMP schemes. Provides access to known XMP schemas. |
| [trailer_pi](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/trailer_pi/) | The trailer processing instruction. |
| [count](/metadata/python-net/groupdocs.metadata.common/metadatapackage/count/) | The number of metadata properties. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [keys](/metadata/python-net/groupdocs.metadata.common/metadatapackage/keys/) | The collection of metadata property names. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [know_property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/know_property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [metadata_type](/metadata/python-net/groupdocs.metadata.common/metadatapackage/metadata_type/) | The metadata type of the package. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### Example

```python
from datetime import date
from groupdocs.metadata import Metadata
from groupdocs.metadata.standards.xmp import XmpArray, XmpArrayType, XmpPackage, XmpPacketWrapper

with Metadata("input.jpg") as metadata:
    root = metadata.get_root_package()
    packet = XmpPacketWrapper()
    custom = XmpPackage("gd", "https://groupdocs.com")
    custom.set("gd:Copyright", "Copyright (C) 2026 GroupDocs. All Rights Reserved.")
    custom.set("gd:CreationDate", date.today())
    custom.set(
        "gd:Company",
        XmpArray.from_(["Aspose", "GroupDocs"], XmpArrayType.ORDERED)
    )
    packet.add_package(custom)
    root.xmp_package = packet
    metadata.save("output.jpg")
```

### See Also
* module [`groupdocs.metadata.standards.xmp`](/metadata/python-net/groupdocs.metadata.standards.xmp/)
