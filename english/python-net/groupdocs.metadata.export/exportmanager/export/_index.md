---
title: export method
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.export/exportmanager/export/
is_root: false
weight: 20
---

## export {#System.String-groupdocs.metadata.export.ExportFormat}

Exports the metadata properties to a file.



```python
def export(self, file_path, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | System.String | The full name of the output file. |
| format | groupdocs.metadata.export.ExportFormat | The format of the output file. |


## export {#io.RawIOBase-groupdocs.metadata.export.ExportFormat}

Exports the metadata properties to a stream.



```python
def export(self, document, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | The full name of the output file. |
| format | groupdocs.metadata.export.ExportFormat | The format of the output file. |


## export {#System.String-groupdocs.metadata.export.ExportFormat-groupdocs.metadata.export.ExportOptions}

Exports the metadata properties to a file.



```python
def export(self, file_path, format, export_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | System.String | The full name of the output file. |
| format | groupdocs.metadata.export.ExportFormat | The format of the output file. |
| export_options | groupdocs.metadata.export.ExportOptions | Additional options to use when exporting a document. |


## export {#io.RawIOBase-groupdocs.metadata.export.ExportFormat-groupdocs.metadata.export.ExportOptions}

Exports the metadata properties to a stream.



```python
def export(self, document, format, export_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | The full name of the output file. |
| format | groupdocs.metadata.export.ExportFormat | The format of the output file. |
| export_options | groupdocs.metadata.export.ExportOptions | Additional options to use when exporting a document. |



### See Also
* module [`groupdocs.metadata.export`](../../)
* class [`ExportManager`](/metadata/python-net/groupdocs.metadata.export/exportmanager)
