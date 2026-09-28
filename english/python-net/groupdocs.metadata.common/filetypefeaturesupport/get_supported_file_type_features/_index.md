---
title: get_supported_file_type_features method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Gets all registered file type feature support entries keyed by FileType."
type: docs
url: /python-net/groupdocs.metadata.common/filetypefeaturesupport/get_supported_file_type_features/
is_root: false
weight: 1010
---


## get_supported_file_type_features

Gets all registered file type feature support entries keyed by [`FileType`](/metadata/python-net/groupdocs.metadata.common/filetype/).

```python
def get_supported_file_type_features(cls):
    ...
```

**Returns:** A read-only map of supported file types.

## get_supported_file_type_features {#file_type}

Gets feature support for the specified file type.

```python
def get_supported_file_type_features(cls, file_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_type | `FileType` | The file type. |

**Returns:** The support information.

| Raises | Description |
| :- | :- |
| `ValueError` | `file_type` is `FileType.unknown`. |
| `KeyError` | No support information is registered for this file type. |

## get_supported_file_type_features {#extension}

Gets feature support for the specified file extension.

```python
def get_supported_file_type_features(cls, extension):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| extension | `str` | The file extension, with or without a leading dot (e.g. `.pdf` or `pdf`). |

**Returns:** The support information.

| Raises | Description |
| :- | :- |
| `ValueError` | `extension` is null or whitespace. |
| `System.Collections.Generic.KeyNotFoundException` | No support information is registered for this extension. |

### See Also
* class [`FileTypeFeatureSupport`](/metadata/python-net/groupdocs.metadata.common/filetypefeaturesupport/)
