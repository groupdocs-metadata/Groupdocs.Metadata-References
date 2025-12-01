---
title: NotSpecification class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 50
url: /python-net/groupdocs.metadata.search/notspecification/
is_root: false
---

## NotSpecification class

Represents a composite specification that negates any other specification.



**Inheritance:** [`NotSpecification`](/metadata/python-net/groupdocs.metadata.search/notspecification) → 
[`Specification`](/metadata/python-net/groupdocs.metadata.search/specification)



The NotSpecification type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [wrapped](/metadata/python-net/groupdocs.metadata.search/notspecification/wrapped) | Gets the base specification to be negated. |


### Methods
| Method | Description |
| :- | :- |
| [`is_satisfied_by(self, candidate)`](/metadata/python-net/groupdocs.metadata.search/notspecification/is_satisfied_by/#groupdocs.metadata.common.metadataproperty) | Verifies whether a [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty) satisfies the specification. |
| [`both(self, other)`](/metadata/python-net/groupdocs.metadata.search/notspecification/both/#groupdocs.metadata.search.specification) | Combines two search specifications using the logical AND operator. |
| [`either(self, other)`](/metadata/python-net/groupdocs.metadata.search/notspecification/either/#groupdocs.metadata.search.specification) | Combines two search specifications using the logical OR operator. |
| [`is_not(self)`](/metadata/python-net/groupdocs.metadata.search/notspecification/is_not/#) | Negates the specification. |



### See Also
* module [`groupdocs.metadata.search`](..)
* class [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty)
* class [`NotSpecification`](/metadata/python-net/groupdocs.metadata.search/notspecification)
* class [`Specification`](/metadata/python-net/groupdocs.metadata.search/specification)
