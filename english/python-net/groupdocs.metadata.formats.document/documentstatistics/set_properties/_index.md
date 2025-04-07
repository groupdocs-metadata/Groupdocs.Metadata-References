---
title: set_properties method
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.document/documentstatistics/set_properties/
is_root: false
weight: 70
---

## set_properties {#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue}

Sets known metadata properties satisfying the specification.
The operation is recursive so it affects all nested packages as well.
This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). 
If an existing property satisfies the specification its value is updated. 
If there is a known property missing in the package that satisfies the specification it is added to the package.


### Returns 


The number of affected properties.


```python
def set_properties(self, specification, value):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| specification | groupdocs.metadata.search.Specification | A specification to test each metadata property for a condition. |
| value | groupdocs.metadata.common.PropertyValue | A new value for the filtered properties. |



### See Also
* module [`groupdocs.metadata.formats.document`](../../)
* class [`DocumentStatistics`](/metadata/python-net/groupdocs.metadata.formats.document/documentstatistics)
