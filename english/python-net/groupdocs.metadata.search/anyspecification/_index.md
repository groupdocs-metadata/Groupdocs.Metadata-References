---
title: AnySpecification class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/groupdocs.metadata.search/anyspecification/
is_root: false
---

## AnySpecification class

Represents a specification that applies no filters to a property.



**Inheritance:** [`AnySpecification`](/metadata/python-net/groupdocs.metadata.search/anyspecification) → 
[`Specification`](/metadata/python-net/groupdocs.metadata.search/specification)



The AnySpecification type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/metadata/python-net/groupdocs.metadata.search/anyspecification/__init__/#) | Constructs a new instance of AnySpecification |


### Methods
| Method | Description |
| :- | :- |
| [`is_satisfied_by(self, candidate)`](/metadata/python-net/groupdocs.metadata.search/anyspecification/is_satisfied_by/#groupdocs.metadata.common.metadataproperty) | Verifies whether a [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty) satisfies the specification. |
| [`both(self, other)`](/metadata/python-net/groupdocs.metadata.search/anyspecification/both/#groupdocs.metadata.search.specification) | Combines two search specifications using the logical AND operator. |
| [`either(self, other)`](/metadata/python-net/groupdocs.metadata.search/anyspecification/either/#groupdocs.metadata.search.specification) | Combines two search specifications using the logical OR operator. |
| [`is_not(self)`](/metadata/python-net/groupdocs.metadata.search/anyspecification/is_not/#) | Negates the specification. |



### See Also
* module [`groupdocs.metadata.search`](..)
* class [`AnySpecification`](/metadata/python-net/groupdocs.metadata.search/anyspecification)
* class [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty)
* class [`Specification`](/metadata/python-net/groupdocs.metadata.search/specification)
