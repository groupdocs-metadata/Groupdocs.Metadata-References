---
title: sanitize method
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata/metadata/sanitize/
is_root: false
weight: 90
---

## sanitize {#}

Removes writable metadata properties from all detected packages or whole packages if possible.
The operation is recursive so it affects all nested packages as well.


### Returns 


The number of affected properties.


```python
def sanitize(self):
    ...
```



### Example 


This example demonstrates how to remove all detected metadata packages/properties from a file.



### See Also
* module [`groupdocs.metadata`](../../)
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata)
