---
title: AndSpecification class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 10
url: /python-net/groupdocs.metadata.search/andspecification/
is_root: false
---

## AndSpecification class

Represents a composite specification that uses the logical AND operator to combine two given search specifications.



**Inheritance:** [`AndSpecification`](/metadata/python-net/groupdocs.metadata.search/andspecification) → 
[`Specification`](/metadata/python-net/groupdocs.metadata.search/specification)



The AndSpecification type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [left](/metadata/python-net/groupdocs.metadata.search/andspecification/left) | Gets the left specification. |
| [right](/metadata/python-net/groupdocs.metadata.search/andspecification/right) | Gets the right specification. |


### Methods
| Method | Description |
| :- | :- |
| [`is_satisfied_by(self, candidate)`](/metadata/python-net/groupdocs.metadata.search/andspecification/is_satisfied_by/#groupdocs.metadata.common.metadataproperty) | Verifies whether a [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty) satisfies the specification. |
| [`both(self, other)`](/metadata/python-net/groupdocs.metadata.search/andspecification/both/#groupdocs.metadata.search.specification) | Combines two search specifications using the logical AND operator. |
| [`either(self, other)`](/metadata/python-net/groupdocs.metadata.search/andspecification/either/#groupdocs.metadata.search.specification) | Combines two search specifications using the logical OR operator. |
| [`is_not(self)`](/metadata/python-net/groupdocs.metadata.search/andspecification/is_not/#) | Negates the specification. |



### See Also
* module [`groupdocs.metadata.search`](..)
* class [`AndSpecification`](/metadata/python-net/groupdocs.metadata.search/andspecification)
* class [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty)
* class [`Specification`](/metadata/python-net/groupdocs.metadata.search/specification)
