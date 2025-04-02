---
title: get_package method
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper/get_package/
is_root: false
weight: 80
---

## get_package {#str}

Gets package by namespace uri.


### Returns 


Appropriate [`XmpPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage) if package found by `namespace_uri`; otherwise null.


```python
def get_package(self, namespace_uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| namespace_uri | str | Package schema uri. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Namespace URI could not be null. |





### See Also
* module [`groupdocs.metadata.standards.xmp`](../../)
* class [`XmpPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage)
* class [`XmpPacketWrapper`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppacketwrapper)
