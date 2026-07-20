---
title: DocumentTagCategory class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Provides tags that are applied to document-specific properties only."
type: docs
url: /python-net/groupdocs.metadata.tagging/documenttagcategory/
is_root: false
weight: 30
---


## DocumentTagCategory class

Provides tags that are applied to document-specific properties only. The tags can be useful to determine from which part of an office document a property was extracted.

The DocumentTagCategory type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [to_string](/metadata/python-net/groupdocs.metadata.tagging/tagcategory/to_string/) | Returns a string that represents the current object. (inherited from [`TagCategory`](/metadata/python-net/groupdocs.metadata.tagging/tagcategory/)) |

### Properties
| Property | Description |
| :- | :- |
| [built_in](/metadata/python-net/groupdocs.metadata.tagging/documenttagcategory/built_in/) | The tag that indicates that the property it labels is built-in. |
| [field](/metadata/python-net/groupdocs.metadata.tagging/documenttagcategory/field/) | The tag that denotes a property holding information about a form field or calculated field extracted from a document. |
| [hidden_data](/metadata/python-net/groupdocs.metadata.tagging/documenttagcategory/hidden_data/) | The tag indicating a document part that is not visible for regular users. |
| [only_update](/metadata/python-net/groupdocs.metadata.tagging/documenttagcategory/only_update/) | The tag that indicates that the property is not fully removed from the document. |
| [page](/metadata/python-net/groupdocs.metadata.tagging/documenttagcategory/page/) | The tag that denotes a property holding information about a document page. |
| [read_only](/metadata/python-net/groupdocs.metadata.tagging/documenttagcategory/read_only/) | The tag that indicates that the property it labels is read‑only and cannot be changed by GroupDocs.Metadata. |
| [revision](/metadata/python-net/groupdocs.metadata.tagging/documenttagcategory/revision/) | The tag labeling a property containing information about a document revision (tracked change). |
| [statistic](/metadata/python-net/groupdocs.metadata.tagging/documenttagcategory/statistic/) | The tag indicating a property containing document statistics (word count, character count, etc). |
| [user_comment](/metadata/python-net/groupdocs.metadata.tagging/documenttagcategory/user_comment/) | The tag that labels user comments shown in the document content. |

### See Also
* module [`groupdocs.metadata.tagging`](/metadata/python-net/groupdocs.metadata.tagging/)
