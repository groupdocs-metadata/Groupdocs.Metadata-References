---
title: save method
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata/metadata/save/
is_root: false
weight: 100
---

## save {#}

Saves all changes made in the loaded document.



```python
def save(self):
    ...
```



### Example 


This example shows how to save the modified content to the underlying source.


## save {#io.RawIOBase}

Saves the document content into a stream.



```python
def save(self, document):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | An output stream for the document. |

### Example 


This example shows how to save a document to the specified stream.


## save {#str}

Saves the document content to the specified file.



```python
def save(self, file_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | str | The full name of the output file. |

### Example 


This example shows how to save a document to the specified location.



### See Also
* module [`groupdocs.metadata`](../../)
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata)
