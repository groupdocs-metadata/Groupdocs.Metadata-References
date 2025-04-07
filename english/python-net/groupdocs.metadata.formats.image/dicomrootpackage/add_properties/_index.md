---
title: add_properties method
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.image/dicomrootpackage/add_properties/
is_root: false
weight: 20
---

## add_properties {#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue}

Adds known metadata properties satisfying the specification.
The operation is recursive so it affects all nested packages as well.


### Returns 


The number of affected properties.


```python
def add_properties(self, specification, value):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| specification | groupdocs.metadata.search.Specification | A specification to test each metadata property for a condition. |
| value | groupdocs.metadata.common.PropertyValue | A value for the picked properties. |



### See Also
* module [`groupdocs.metadata.formats.image`](../../)
* class [`DicomRootPackage`](/metadata/python-net/groupdocs.metadata.formats.image/dicomrootpackage)
