---
title: __init__ constructor
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Initializes a new Metadata instance."
type: docs
url: /python-net/groupdocs.metadata/metadata/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initializes a new [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/) instance.

Learn more:
- [Load from a local disk](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
- [Load from a stream](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
- [Load a file of a specific format](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
- [Load a password-protected document](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

```python
def __init__(self, file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | A string that contains the full name of the file from which to create a `Metadata` instance. |

### Example

```python
from groupdocs.metadata import Metadata

with Metadata("example.jpg") as metadata:
    # Extract, edit or remove metadata here
    pass
```

## __init__ {#document}

Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/) class.

- [Load from a local disk](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
- [Load from a stream](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
- [Load a file of a specific format](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
- [Load a password-protected document](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

```python
def __init__(self, document):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | A stream that contains the document to load. |

### Example

```python
from groupdocs.metadata import Metadata

def load_from_stream():
    with open("input.docx", "rb") as stream:
        with Metadata(stream) as metadata:
            # Extract, edit or remove metadata here
            pass
```

## __init__ {#file_path-load_options}

Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/) class.

Learn more

- [Load from a local disk](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
- [Load from a stream](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
- [Load a file of a specific format](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
- [Load a password-protected document](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

```python
def __init__(self, file_path, load_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | A string that contains the full name of the file from which to create a `Metadata` instance. |
| load_options | `LoadOptions` | Additional options to use when loading a document. |

### Example

```python
from groupdocs.metadata import Metadata, LoadOptions

load_options = LoadOptions(password="123")
with Metadata("protected.docx", load_options) as metadata:
    # Extract, edit or remove metadata here
    pass
```

## __init__ {#document-load_options}

Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/) class.

Learn more:
- Load from a local disk: https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk
- Load from a stream: https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream
- Load a file of a specific format: https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format
- Load a password-protected document: https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document

```python
def __init__(self, document, load_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | A stream that contains the document to load. |
| load_options | `LoadOptions` | Additional options to use when loading a document. |

## __init__ {#uri}

Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/) class.

Learn more

- Load from a local disk: https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk
- Load from a stream: https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream
- Load a file of a specific format: https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format
- Load a password-protected document: https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document

```python
def __init__(self, uri):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| uri | `str` | A uri that contains the document to load. |

### Example

```python
from groupdocs.metadata import Metadata

with Metadata(uri) as metadata:
    # Extract, edit or remove metadata here
```

## __init__ {#uri-load_options}

Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/) class.

Learn more

- [Load from a local disk](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
- [Load from a stream](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
- [Load a file of a specific format](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
- [Load a password-protected document](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

```python
def __init__(self, uri, load_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| uri | `str` | A uri that contains the document to load. |
| load_options | `LoadOptions` | Additional options to use when loading a document. |

### Example

```python
from groupdocs.metadata import Metadata

with Metadata("example.jpg") as metadata:
    root = metadata.get_root_package()
    # manipulate metadata packages, e.g., remove EXIF
    # root.exif_package = None
    metadata.save("output.jpg")
```

### See Also
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/)
