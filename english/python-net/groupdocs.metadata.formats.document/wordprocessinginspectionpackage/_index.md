---
title: WordProcessingInspectionPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Contains information about document parts that can be considered as metadata in some cases."
type: docs
url: /python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/
is_root: false
weight: 410
---


## WordProcessingInspectionPackage class

Contains information about document parts that can be considered as metadata in some cases.

Learn more

- [Working with metadata in WordProcessing documents](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

The WordProcessingInspectionPackage type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [accept_all_revisions](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/accept_all_revisions/) | Accepts all detected revisions in the document. |
| [clear_comments](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clear_comments/) | Removes all detected user comments from the document. |
| [clear_fields](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clear_fields/) | Removes all detected fields from the document. |
| [clear_hidden_text](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clear_hidden_text/) | Removes all hidden text fragments from the document. |
| [reject_all_revisions](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/reject_all_revisions/) | Rejects all detected revisions in the document. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/remove_properties/#predicate) | Removes metadata properties satisfying the specified predicate. |
| [remove_properties_func](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/remove_properties_func/) |  |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/sanitize/) | Removes writable metadata properties from the package recursively, affecting all nested packages as well. |
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
| [comments](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/comments/) | The user comments. |
| [digital_signatures](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/digital_signatures/) | The digital signatures presented in the document. |
| [fields](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/fields/) | The document fields as a list of document fields. |
| [hidden_text](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/hidden_text/) | The hidden text fragments extracted from the document as a list of strings. |
| [revisions](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/revisions/) | The digital signatures presented in the document. |
| [count](/metadata/python-net/groupdocs.metadata.common/metadatapackage/count/) | The number of metadata properties. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [keys](/metadata/python-net/groupdocs.metadata.common/metadatapackage/keys/) | The collection of metadata property names. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [know_property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/know_property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [metadata_type](/metadata/python-net/groupdocs.metadata.common/metadatapackage/metadata_type/) | The metadata type of the package. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### Example

```python
from groupdocs.metadata import Metadata, WordProcessingRootPackage, Constants

with Metadata(Constants.InputDoc) as metadata:
    root = metadata.get_root_package(WordProcessingRootPackage)

    # Clear various inspection elements
    root.inspection_package.clear_comments()
    root.inspection_package.accept_all_revisions()
    root.inspection_package.clear_fields()
    root.inspection_package.clear_hidden_text()

    metadata.save(Constants.OutputDoc)
```

### See Also
* module [`groupdocs.metadata.formats.document`](/metadata/python-net/groupdocs.metadata.formats.document/)
