---
title: save method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Saves all changes made in the loaded document."
type: docs
url: /python-net/groupdocs.metadata/metadata/save/
is_root: false
weight: 1150
---


## save

Saves all changes made in the loaded document.

Learn more:
- Save a modified file to the original source: https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+the+original+source
- Save a modified file to a specified location: https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+specified+location
- Save a modified file to a stream: https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+stream

```python
def save(self):
    ...
```

### Example

```python
from groupdocs.metadata import Metadata

def save_changes():
    with Metadata("input.ppt") as metadata:
        # edit or remove metadata here
        metadata.save()
```

## save {#document}

Saves the document content into a stream.

Learn more:
- https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+the+original+source
- https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+specified+location
- https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+stream

```python
def save(self, document):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | An output stream for the document. |

### Example

```python
import io
from groupdocs.metadata import Metadata

def save_to_stream():
    # Prepare an in‑memory stream
    stream = io.BytesIO()
    with Metadata("input.png") as metadata:
        # Edit or remove metadata here
        metadata.save(stream)
    # The stream now contains the modified file data
    stream.seek(0)
    with open("output.png", "wb") as f:
        f.write(stream.read())
```

## save {#file_path}

Saves the document content to the specified file.

Learn more:
- Save a modified file to the original source: https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+the+original+source
- Save a modified file to a specified location: https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+specified+location
- Save a modified file to a stream: https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+stream

```python
def save(self, file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The full name of the output file. |

### Example

```python
from groupdocs.metadata import Metadata

def save_modified_file():
    with Metadata("input.jpg") as metadata:
        # edit or remove metadata here
        metadata.save("output.jpg")
```

### See Also
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/)
