---
title: remove method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Removes the dataSet with the specified record and dataSet number."
type: docs
url: /python-net/groupdocs.metadata.standards.iptc/iptcrecordset/remove/
is_root: false
weight: 1070
---


## remove {#record_number-data_set_number}

Removes the dataSet with the specified record and dataSet number.

```python
def remove(self, record_number, data_set_number):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| record_number | `int` | The record number. |
| data_set_number | `int` | The dataSet number. |

**Returns:** bool: True if the specified IPTC dataSet is found and removed; otherwise, False.

## remove {#record_number}

Removes the record with the specified record number.

```python
def remove(self, record_number):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| record_number | `int` | The record number. |

**Returns:** bool: True if the specified IPTC record is found and removed; otherwise, False.

### See Also
* class [`IptcRecordSet`](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/)
