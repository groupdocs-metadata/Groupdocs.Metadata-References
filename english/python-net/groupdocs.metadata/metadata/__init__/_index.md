---
title: Metadata constructor
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata/metadata/__init__/
is_root: false
weight: 10
---

## __init__ {#System.String}

Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class.



```python
def __init__(self, file_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | System.String | A string that contains the full name of the file from which to create a [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) instance. |

### Example 


This example demonstrates how to load a file from a local disk.


## __init__ {#io.RawIOBase}

Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class.



```python
def __init__(self, document):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | A stream that contains the document to load. |

### Example 


This example demonstrates how to load a file from a stream.


## __init__ {#System.Uri}

Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class.



```python
def __init__(self, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| uri | System.Uri | A uri that contains the document to load. |

### Example 


This example demonstrates how to load a file from a uri.


## __init__ {#System.String-groupdocs.metadata.options.LoadOptions}

Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class.



```python
def __init__(self, file_path, load_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | System.String | A string that contains the full name of the file from which to create a [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) instance. |
| load_options | groupdocs.metadata.options.LoadOptions | Additional options to use when loading a document. |

### Example 


This example demonstrates how to load a password-protected document.


## __init__ {#io.RawIOBase-groupdocs.metadata.options.LoadOptions}

Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class.



```python
def __init__(self, document, load_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | A stream that contains the document to load. |
| load_options | groupdocs.metadata.options.LoadOptions | Additional options to use when loading a document. |


## __init__ {#System.Uri-groupdocs.metadata.options.LoadOptions}

Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class.



```python
def __init__(self, uri, load_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| uri | System.Uri | A uri that contains the document to load. |
| load_options | groupdocs.metadata.options.LoadOptions | Additional options to use when loading a document. |



### See Also
* module [`groupdocs.metadata`](../../)
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata)
