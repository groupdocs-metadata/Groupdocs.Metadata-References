---
title: WithNameSpecification class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 90
url: /python-net/groupdocs.metadata.search/withnamespecification/
is_root: false
---

## WithNameSpecification class

Represents a specification that filters properties with a particular name.



**Inheritance:** [`WithNameSpecification`](/metadata/python-net/groupdocs.metadata.search/withnamespecification) → 
[`Specification`](/metadata/python-net/groupdocs.metadata.search/specification)



The WithNameSpecification type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self, property_name)`](/metadata/python-net/groupdocs.metadata.search/withnamespecification/__init__/#system.string) | Initializes a new instance of the [`WithNameSpecification`](/metadata/python-net/groupdocs.metadata.search/withnamespecification) class. |
| [`__init__(self, property_name, ignore_case)`](/metadata/python-net/groupdocs.metadata.search/withnamespecification/__init__/#system.string-bool) | Initializes a new instance of the [`WithNameSpecification`](/metadata/python-net/groupdocs.metadata.search/withnamespecification) class. |


### Properties
| Property | Description |
| :- | :- |
| [property_name](/metadata/python-net/groupdocs.metadata.search/withnamespecification/property_name) | Gets the name of properties that satisfy the specification. |
| [ignore_case](/metadata/python-net/groupdocs.metadata.search/withnamespecification/ignore_case) | Gets a value indicating whether the case of the strings being compared should be ignored. |


### Methods
| Method | Description |
| :- | :- |
| [`is_satisfied_by(self, candidate)`](/metadata/python-net/groupdocs.metadata.search/withnamespecification/is_satisfied_by/#groupdocs.metadata.common.metadataproperty) | Verifies whether a [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty) satisfies the specification. |
| [`both(self, other)`](/metadata/python-net/groupdocs.metadata.search/withnamespecification/both/#groupdocs.metadata.search.specification) | Combines two search specifications using the logical AND operator. |
| [`either(self, other)`](/metadata/python-net/groupdocs.metadata.search/withnamespecification/either/#groupdocs.metadata.search.specification) | Combines two search specifications using the logical OR operator. |
| [`is_not(self)`](/metadata/python-net/groupdocs.metadata.search/withnamespecification/is_not/#) | Negates the specification. |



### See Also
* module [`groupdocs.metadata.search`](..)
* class [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty)
* class [`Specification`](/metadata/python-net/groupdocs.metadata.search/specification)
* class [`WithNameSpecification`](/metadata/python-net/groupdocs.metadata.search/withnamespecification)
