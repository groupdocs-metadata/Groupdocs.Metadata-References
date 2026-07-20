---
title: PreviewOptions class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Provides options to set requirements and stream delegates for preview generation."
type: docs
url: /python-net/groupdocs.metadata.options/previewoptions/
is_root: false
weight: 40
---


## PreviewOptions class

Provides options to set requirements and stream delegates for preview generation.

Learn more

- Generate document preview: https://docs.groupdocs.com/display/metadatanet/Generate+document+preview

The PreviewOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.options/previewoptions/__init__/#create_page_stream) | Initializes a new instance of the [`PreviewOptions`](/metadata/python-net/groupdocs.metadata.options/previewoptions/) class causing the output stream to be closed. |
| [__init__](/metadata/python-net/groupdocs.metadata.options/previewoptions/__init__/#create_page_stream-release_page_stream) | Initializes a new instance of PreviewOptions class causing the output stream to be returned to the client for further use. |

### Properties
| Property | Description |
| :- | :- |
| [cache_folder](/metadata/python-net/groupdocs.metadata.options/previewoptions/cache_folder/) | The cache folder. |
| [create_page_stream](/metadata/python-net/groupdocs.metadata.options/previewoptions/create_page_stream/) | The page stream creation delegate. |
| [height](/metadata/python-net/groupdocs.metadata.options/previewoptions/height/) | The page preview height. |
| [max_disk_space_for_cache](/metadata/python-net/groupdocs.metadata.options/previewoptions/max_disk_space_for_cache/) | The maximum available disk space for cache in bytes. The default value is 1073741824. |
| [max_memory_for_cache](/metadata/python-net/groupdocs.metadata.options/previewoptions/max_memory_for_cache/) | The maximum available memory for cache in bytes. |
| [page_numbers](/metadata/python-net/groupdocs.metadata.options/previewoptions/page_numbers/) | The page numbers to generate previews as a list of int. |
| [preview_format](/metadata/python-net/groupdocs.metadata.options/previewoptions/preview_format/) | The preview image format. |
| [release_page_stream](/metadata/python-net/groupdocs.metadata.options/previewoptions/release_page_stream/) | The page preview completion delegate. |
| [resolution](/metadata/python-net/groupdocs.metadata.options/previewoptions/resolution/) | The page preview resolution. |
| [width](/metadata/python-net/groupdocs.metadata.options/previewoptions/width/) | The page preview width. |

### See Also
* module [`groupdocs.metadata.options`](/metadata/python-net/groupdocs.metadata.options/)
