---
title: add_properties method
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/groupdocs.metadata.standards.xmp/xmpelementbase/add_properties/
is_root: false
---

## add_properties(self, specification, value) {#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue}

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
* module [`groupdocs.metadata.standards.xmp`](../../)
* class [`XmpElementBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpelementbase)
