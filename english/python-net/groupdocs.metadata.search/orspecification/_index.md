---
title: OrSpecification class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.search/orspecification/
is_root: false
weight: 70
---

## OrSpecification class

Represents a composite specification that uses the logical OR operator to combine two given search specifications.



**Inheritance:** [`OrSpecification`](/metadata/python-net/groupdocs.metadata.search/orspecification) → 
[`Specification`](/metadata/python-net/groupdocs.metadata.search/specification)



The OrSpecification type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [left](/metadata/python-net/groupdocs.metadata.search/orspecification/left) | Gets the left specification. |
| [right](/metadata/python-net/groupdocs.metadata.search/orspecification/right) | Gets the right specification. |


### Methods
| Method | Description |
| :- | :- |
| [is_satisfied_by](/metadata/python-net/groupdocs.metadata.search/orspecification/is_satisfied_by/#groupdocs.metadata.common.MetadataProperty) | Verifies whether a [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty) satisfies the specification. |
| [both](/metadata/python-net/groupdocs.metadata.search/orspecification/both/#groupdocs.metadata.search.Specification) | Combines two search specifications using the logical AND operator. |
| [either](/metadata/python-net/groupdocs.metadata.search/orspecification/either/#groupdocs.metadata.search.Specification) | Combines two search specifications using the logical OR operator. |
| [is_not](/metadata/python-net/groupdocs.metadata.search/orspecification/is_not/#) | Negates the specification. |



### See Also
* module [`groupdocs.metadata.search`](..)
* class [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty)
* class [`OrSpecification`](/metadata/python-net/groupdocs.metadata.search/orspecification)
* class [`Specification`](/metadata/python-net/groupdocs.metadata.search/specification)
