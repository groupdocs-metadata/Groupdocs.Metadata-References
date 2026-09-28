---
title: __init__ constructor
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Initializes a new ID3V2AttachedPictureFrame."
type: docs
url: /python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/__init__/
is_root: false
weight: 10
---


## __init__ {#encoding-mime_type-picture_type-description-picture_data}

Initializes a new ID3V2AttachedPictureFrame.

```python
def __init__(self, encoding, mime_type, picture_type, description, picture_data):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| encoding | `ID3V2EncodingType` | The frame encoding. |
| mime_type | `str` | The MIME-type of the image. |
| picture_type | `ID3V2AttachedPictureType` | The type of the picture. |
| description | `str` | The description of the picture. |
| picture_data | `list[int]` | The picture data. |

## __init__ {#picture_type-description-picture_data}

Initializes a new ID3V2AttachedPictureFrame instance.

```python
def __init__(self, picture_type, description, picture_data):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| picture_type | `ID3V2AttachedPictureType` | The type of the picture. |
| description | `str` | The description of the picture. |
| picture_data | `list[int]` | The picture data. |

## __init__ {#picture_data}

Initializes a new instance of ID3V2AttachedPictureFrame.

```python
def __init__(self, picture_data):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| picture_data | `list[int]` | The picture data. |

### See Also
* class [`ID3V2AttachedPictureFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/)
