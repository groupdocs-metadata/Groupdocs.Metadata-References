---
title: update_properties method
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 80
url: /python-net/groupdocs.metadata.formats.fb2/fb2package/update_properties/
is_root: false
---

## update_properties(self, specification, value) {#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue}

Updates known metadata properties satisfying a specification.
The operation is recursive so it affects all nested packages as well.


### Returns 


The number of affected properties.


```python

def update_properties(self, specification, value):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| specification | groupdocs.metadata.search.Specification | A specification to test each metadata property for a condition. |
| value | groupdocs.metadata.common.PropertyValue | A new value for the filtered properties. |
### Remarks

Please note that GroupDocs.Metadata implicitly checks the type of each filtered property. 
It's impossible to update a property with a value having an inappropriate type.


### See Also
* module [`groupdocs.metadata.formats.fb2`](../../)
* class [`Fb2Package`](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package)
