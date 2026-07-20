---
title: Metadata class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Provides the main class to access metadata in all supported formats."
type: docs
url: /python-net/groupdocs.metadata/metadata/
is_root: false
weight: 50
---


## Metadata class

Provides the main class to access metadata in all supported formats.

The Metadata type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata/metadata/__init__/#file_path) | Initializes a new [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/) instance. |
| [__init__](/metadata/python-net/groupdocs.metadata/metadata/__init__/#document) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/) class. |
| [__init__](/metadata/python-net/groupdocs.metadata/metadata/__init__/#file_path-load_options) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/) class. |
| [__init__](/metadata/python-net/groupdocs.metadata/metadata/__init__/#document-load_options) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/) class. |
| [__init__](/metadata/python-net/groupdocs.metadata/metadata/__init__/#uri) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/) class. |
| [__init__](/metadata/python-net/groupdocs.metadata/metadata/__init__/#uri-load_options) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/) class. |

### Methods
| Method | Description |
| :- | :- |
| [add_properties](/metadata/python-net/groupdocs.metadata/metadata/add_properties/#predicate-value) | Adds known metadata properties satisfying the specified predicate, recursively affecting all nested packages. |
| [add_properties_func](/metadata/python-net/groupdocs.metadata/metadata/add_properties_func/) |  |
| [copy_to](/metadata/python-net/groupdocs.metadata/metadata/copy_to/#metadata) | Copy known metadata properties from source package to destination package. |
| [copy_to](/metadata/python-net/groupdocs.metadata/metadata/copy_to/#metadata-tags) | Copy known metadata properties from source package to destination package. |
| [copy_to_metadata_package](/metadata/python-net/groupdocs.metadata/metadata/copy_to_metadata_package/) |  |
| [dispose](/metadata/python-net/groupdocs.metadata/metadata/dispose/) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [find_properties](/metadata/python-net/groupdocs.metadata/metadata/find_properties/#predicate) | Finds metadata properties that satisfy the specified predicate, searching recursively through all nested packages. |
| [find_properties_func](/metadata/python-net/groupdocs.metadata/metadata/find_properties_func/) |  |
| [generate_preview](/metadata/python-net/groupdocs.metadata/metadata/generate_preview/#preview_options) | Creates preview images for specified pages. |
| [generate_preview_preview_options](/metadata/python-net/groupdocs.metadata/metadata/generate_preview_preview_options/) |  |
| [get_document_info](/metadata/python-net/groupdocs.metadata/metadata/get_document_info/) | Gets common information about the loaded document. |
| [get_root_package](/metadata/python-net/groupdocs.metadata/metadata/get_root_package/) | Gets the root package providing access to all metadata properties extracted from the file. |
| [remove_properties](/metadata/python-net/groupdocs.metadata/metadata/remove_properties/#predicate) | Removes metadata properties satisfying the specified predicate. |
| [remove_properties_func](/metadata/python-net/groupdocs.metadata/metadata/remove_properties_func/) |  |
| [sanitize](/metadata/python-net/groupdocs.metadata/metadata/sanitize/) | Removes writable metadata properties from all detected packages, recursively affecting nested packages when possible. |
| [save](/metadata/python-net/groupdocs.metadata/metadata/save/) | Saves all changes made in the loaded document. |
| [save](/metadata/python-net/groupdocs.metadata/metadata/save/#document) | Saves the document content into a stream. |
| [save](/metadata/python-net/groupdocs.metadata/metadata/save/#file_path) | Saves the document content to the specified file. |
| [save_file](/metadata/python-net/groupdocs.metadata/metadata/save_file/) |  |
| [save_stream](/metadata/python-net/groupdocs.metadata/metadata/save_stream/) |  |
| [save_streams](/metadata/python-net/groupdocs.metadata/metadata/save_streams/) |  |
| [save_string](/metadata/python-net/groupdocs.metadata/metadata/save_string/) |  |
| [set_properties](/metadata/python-net/groupdocs.metadata/metadata/set_properties/#predicate-value) | Sets known metadata properties satisfying the specified predicate. |
| [set_properties_func](/metadata/python-net/groupdocs.metadata/metadata/set_properties_func/) |  |
| [update_properties](/metadata/python-net/groupdocs.metadata/metadata/update_properties/#predicate-value) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [update_properties_func](/metadata/python-net/groupdocs.metadata/metadata/update_properties_func/) |  |

### Properties
| Property | Description |
| :- | :- |
| [file_format](/metadata/python-net/groupdocs.metadata/metadata/file_format/) | The type of the loaded file if recognized; otherwise, `GroupDocs.Metadata.FileFormat.Unknown`. |

### Example

```python
from groupdocs.metadata import Metadata

with Metadata("sample.jpg") as metadata:
    root = metadata.get_root_package()
    # Assign None to drop a metadata package, e.g., EXIF
    root.exif_package = None
    metadata.save("output.jpg")
```

### Guides
Task guides that use `Metadata`:

* [Quick Start Guide](/metadata/python-net/guides/quick-start-guide/)
* [Get document info](/metadata/python-net/guides/get-document-info/)
* [Find metadata properties](/metadata/python-net/guides/find-metadata-properties/)
* [Set metadata properties](/metadata/python-net/guides/set-metadata-properties/)
* [Remove metadata properties](/metadata/python-net/guides/remove-metadata-properties/)
* [Clean metadata](/metadata/python-net/guides/clean-metadata/)

### See Also
* module [`groupdocs.metadata`](/metadata/python-net/groupdocs.metadata/)
