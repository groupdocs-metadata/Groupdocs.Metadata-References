---
title: remove method
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.standards.iptc/iptcrecordset/remove/
is_root: false
weight: 70
---

## remove {#int}

Removes the record with the specified record number.


### Returns 


True if the specified IPTC record is found and removed; otherwise, false.


```python
def remove(self, record_number):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| record_number | int | The record number. |


## remove {#int-int}

Removes the dataSet with the specified record and dataSet number.


### Returns 


True if the specified IPTC dataSet is found and removed; otherwise, false.


```python
def remove(self, record_number, data_set_number):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| record_number | int | The record number. |
| data_set_number | int | The dataSet number. |



### See Also
* module [`groupdocs.metadata.standards.iptc`](../../)
* class [`IptcRecordSet`](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset)
