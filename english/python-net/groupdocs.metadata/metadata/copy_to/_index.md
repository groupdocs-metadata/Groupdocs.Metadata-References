---
title: copy_to method
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata/metadata/copy_to/
is_root: false
weight: 30
---

## copy_to {#groupdocs.metadata.common.MetadataPackage}

Copy known metadata properties from source package to destination package.
The operation is recursive so it affects all nested packages as well.
If an existing property its value is updated. 
If there is a known property missing in a destination package it is added to the package.
If there is a known property missing in a source package it is not remove from destination package. If that need, use Sanitize method before.



```python
def copy_to(self, metadata):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| metadata | groupdocs.metadata.common.MetadataPackage | A destination metadata package. |

### Example 


This example demonstrates how to copy metadata properties from source package to destination package.


## copy_to {#groupdocs.metadata.common.MetadataPackage-System.Collections.Generic.List<GroupDocs.Metadata.Tagging.PropertyTag>}





```python
def copy_to(self, metadata, tags):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| metadata | groupdocs.metadata.common.MetadataPackage |  |
| tags | System.Collections.Generic.List<GroupDocs.Metadata.Tagging.PropertyTag> |  |



### See Also
* module [`groupdocs.metadata`](../../)
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata)
