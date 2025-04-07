---
title: import_metadata method
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.importing/importmanager/import_metadata/
is_root: false
weight: 20
---

## import_metadata {#str-groupdocs.metadata.importing.ImportFormat-groupdocs.metadata.importing.ImportOptions}

Imports the metadata properties to a file.



```python
def import_metadata(self, file_path, format, import_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | str | The full name of the input file. |
| format | [`ImportFormat`](/metadata/python-net/groupdocs.metadata.importing/importformat) | The format of the input file. |
| import_options | [`ImportOptions`](/metadata/python-net/groupdocs.metadata.importing/importoptions) | Additional options to use when importing. |


## import_metadata {#io.RawIOBase-groupdocs.metadata.importing.ImportFormat-groupdocs.metadata.importing.ImportOptions}

Imports the metadata properties to a file.



```python
def import_metadata(self, stream, format, import_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The filestream of the input file. |
| format | [`ImportFormat`](/metadata/python-net/groupdocs.metadata.importing/importformat) | The format of the input file. |
| import_options | [`ImportOptions`](/metadata/python-net/groupdocs.metadata.importing/importoptions) | Additional options to use when importing. |



### See Also
* module [`groupdocs.metadata.importing`](../../)
* class [`ImportManager`](/metadata/python-net/groupdocs.metadata.importing/importmanager)
