---
title: ID3V2AttachedPictureFrame constructor
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/__init__/
is_root: false
weight: 10
---

## __init__ {#bytes}

Initializes a new instance of the [`ID3V2AttachedPictureFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe) class.



```python
def __init__(self, picture_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| picture_data | bytes | The picture data. |


## __init__ {#groupdocs.metadata.formats.audio.ID3V2AttachedPictureType-str-bytes}

Initializes a new instance of the [`ID3V2AttachedPictureFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe) class.



```python
def __init__(self, picture_type, description, picture_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| picture_type | [`ID3V2AttachedPictureType`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpicturetype) | The type of the picture. |
| description | str | The description of the picture. |
| picture_data | bytes | The picture data. |


## __init__ {#groupdocs.metadata.formats.audio.ID3V2EncodingType-str-groupdocs.metadata.formats.audio.ID3V2AttachedPictureType-str-bytes}

Initializes a new instance of the [`ID3V2AttachedPictureFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe) class.



```python
def __init__(self, encoding, mime_type, picture_type, description, picture_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| encoding | [`ID3V2EncodingType`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2encodingtype) | The frame encoding. |
| mime_type | str | The MIME-type of the image. |
| picture_type | [`ID3V2AttachedPictureType`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpicturetype) | The type of the picture. |
| description | str | The description of the picture. |
| picture_data | bytes | The picture data. |



### See Also
* module [`groupdocs.metadata.formats.audio`](../../)
* class [`ID3V2AttachedPictureFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe)
