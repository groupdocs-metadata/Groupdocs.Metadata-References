---
title: XmpPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents base abstraction for XMP package."
type: docs
url: /python-net/groupdocs.metadata.standards.xmp/xmppackage/
is_root: false
weight: 270
---


## XmpPackage class

Represents base abstraction for XMP package.

Learn more:
- [Working with XMP metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

The XmpPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/__init__/#prefix-namespace_uri) | Initializes a new XMP package with the specified prefix and namespace URI. |

### Methods
| Method | Description |
| :- | :- |
| [clear](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/clear/) | Removes all XMP properties. |
| [get_xmp_representation](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/get_xmp_representation/) | Converts the XMP value to the XML representation. |
| [remove](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/remove/#name) | Removes the property with the specified name. |
| [remove_file](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/remove_file/) |  |
| [remove_string](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/remove_string/) |  |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/set/#name-value) | Sets a string property. |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/set/#name-value) | Sets an integer property. |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/set/#name-value) | Assigns a boolean XMP metadata property. |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/set/#name-value) | Sets an XMP metadata property. |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/set/#name-value) | Sets a double property. |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/set/#name-value) | Sets the value inherited from [`XmpValueBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpvaluebase/). |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/set/#name-value) | Assigns a value to the specified XMP metadata property. |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/set/#name-value) | Sets the value inherited from [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray/). |
| [set_file](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/set_file/) |  |
| [set_string](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/set_string/) |  |
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
| [namespace_uri](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/namespace_uri/) | The namespace URI. |
| [prefix](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/prefix/) | The XML namespace prefix. |
| [xml_namespace](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/xml_namespace/) | The XML namespace. |
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


def add_custom_xmp_package():
    with Metadata("input.jpg") as metadata:
        root = metadata.get_root_package()
        packet = XmpPacketWrapper()

        custom = XmpPackage("gd", "https://groupdocs.com")
        custom.set("gd:Copyright", "Copyright (C) 2026 GroupDocs. All Rights Reserved.")
        custom.set("gd:CreationDate", date.today())
        custom.set("gd:Company", XmpArray.from_(["Aspose", "GroupDocs"], XmpArrayType.ORDERED))
        packet.add_package(custom)

        root.xmp_package = packet
        metadata.save("output.jpg")
```

### See Also
* module [`groupdocs.metadata.standards.xmp`](/metadata/python-net/groupdocs.metadata.standards.xmp/)
