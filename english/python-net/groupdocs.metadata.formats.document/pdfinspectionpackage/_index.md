---
title: PdfInspectionPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Contains information about PDF document parts that can be considered as metadata in some cases."
type: docs
url: /python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/
is_root: false
weight: 160
---


## PdfInspectionPackage class

Contains information about PDF document parts that can be considered as metadata in some cases.

Learn more
- [Working with metadata in PDF documents](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)

The PdfInspectionPackage type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [clear_annotations](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/clear_annotations/) | Removes all detected annotations from the document. |
| [clear_attachments](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/clear_attachments/) | Removes all detected attachments from the document. |
| [clear_bookmarks](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/clear_bookmarks/) | Removes all detected bookmarks from the document. |
| [clear_digital_signatures](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/clear_digital_signatures/) | Removes all detected digital signatures from the document. |
| [clear_fields](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/clear_fields/) | Removes all detected form fields from the document. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/remove_properties/#predicate) | Removes metadata properties satisfying the specified predicate. |
| [remove_properties_func](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/remove_properties_func/) |  |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/sanitize/) | Removes writable metadata properties from the package, recursively affecting all nested packages. |
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
| [set_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties/) | Sets known metadata properties satisfying the specified predicate. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [set_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [update_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties/) | Updates known metadata properties that satisfy the specified predicate, recursively affecting all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [update_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### Properties
| Property | Description |
| :- | :- |
| [annotations](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/annotations/) | The annotations as a list. |
| [attachments](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/attachments/) | The attachments of the PDF inspection package as a list. |
| [bookmarks](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/bookmarks/) | The bookmarks as a list. |
| [digital_signatures](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/digital_signatures/) | The digital signatures as a list. |
| [fields](/metadata/python-net/groupdocs.metadata.formats.document/pdfinspectionpackage/fields/) | The form fields as an array. |
| [count](/metadata/python-net/groupdocs.metadata.common/metadatapackage/count/) | The number of metadata properties. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [keys](/metadata/python-net/groupdocs.metadata.common/metadatapackage/keys/) | The collection of metadata property names. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [know_property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/know_property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [metadata_type](/metadata/python-net/groupdocs.metadata.common/metadatapackage/metadata_type/) | The metadata type of the package. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### Example

```python
from groupdocs.metadata import Metadata, PdfRootPackage, Constants

with Metadata(Constants.SignedPdf) as metadata:
    root = metadata.get_root_package(PdfRootPackage)

    root.inspection_package.clear_annotations()
    root.inspection_package.clear_attachments()
    root.inspection_package.clear_fields()
    root.inspection_package.clear_bookmarks()
    root.inspection_package.clear_digital_signatures()

    metadata.save(Constants.OutputPdf)
```

### See Also
* module [`groupdocs.metadata.formats.document`](/metadata/python-net/groupdocs.metadata.formats.document/)
