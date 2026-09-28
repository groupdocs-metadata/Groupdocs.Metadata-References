---
title: FileTypeFeatureSupport class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents product feature support information for a specific file extension."
type: docs
url: /python-net/groupdocs.metadata.common/filetypefeaturesupport/
is_root: false
weight: 70
---


## FileTypeFeatureSupport class

Represents product feature support information for a specific file extension.

Use [`FileTypeFeatureSupport.get_supported_file_type_features`](/metadata/python-net/groupdocs.metadata.common/filetypefeaturesupport/get_supported_file_type_features/) to enumerate all registered entries and [`FileTypeFeatureSupport.get_supported_file_type_features`](/metadata/python-net/groupdocs.metadata.common/filetypefeaturesupport/get_supported_file_type_features/)(file_type) or [`FileTypeFeatureSupport.get_supported_file_type_features`](/metadata/python-net/groupdocs.metadata.common/filetypefeaturesupport/get_supported_file_type_features/)(extension) to resolve a single entry.

The FileTypeFeatureSupport type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [get_supported_file_type_features](/metadata/python-net/groupdocs.metadata.common/filetypefeaturesupport/get_supported_file_type_features/) | Gets all registered file type feature support entries keyed by [`FileType`](/metadata/python-net/groupdocs.metadata.common/filetype/). |
| [get_supported_file_type_features](/metadata/python-net/groupdocs.metadata.common/filetypefeaturesupport/get_supported_file_type_features/#file_type) | Gets feature support for the specified file type. |
| [get_supported_file_type_features](/metadata/python-net/groupdocs.metadata.common/filetypefeaturesupport/get_supported_file_type_features/#extension) | Gets feature support for the specified file extension. |
| [get_supported_file_type_features_file](/metadata/python-net/groupdocs.metadata.common/filetypefeaturesupport/get_supported_file_type_features_file/) |  |
| [get_supported_file_type_features_file_type](/metadata/python-net/groupdocs.metadata.common/filetypefeaturesupport/get_supported_file_type_features_file_type/) |  |
| [get_supported_file_type_features_string](/metadata/python-net/groupdocs.metadata.common/filetypefeaturesupport/get_supported_file_type_features_string/) |  |

### Properties
| Property | Description |
| :- | :- |
| [description](/metadata/python-net/groupdocs.metadata.common/filetypefeaturesupport/description/) | The file type description. |
| [extension](/metadata/python-net/groupdocs.metadata.common/filetypefeaturesupport/extension/) | The file extension for this entry (e.g. `.pdf`). |
| [features](/metadata/python-net/groupdocs.metadata.common/filetypefeaturesupport/features/) | The feature support details for this file type. |
| [format_family](/metadata/python-net/groupdocs.metadata.common/filetypefeaturesupport/format_family/) | The documentation family this file type belongs to. |
| [note](/metadata/python-net/groupdocs.metadata.common/filetypefeaturesupport/note/) | The optional remarks about support for this file type. |

### See Also
* module [`groupdocs.metadata.common`](/metadata/python-net/groupdocs.metadata.common/)
