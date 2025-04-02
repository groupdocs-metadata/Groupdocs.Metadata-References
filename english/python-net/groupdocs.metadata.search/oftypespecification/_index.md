---
title: OfTypeSpecification class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.search/oftypespecification/
is_root: false
weight: 60
---

## OfTypeSpecification class

Represents a specification that filters properties of a particular type.



**Inheritance:** [`OfTypeSpecification`](/metadata/python-net/groupdocs.metadata.search/oftypespecification) → 
[`Specification`](/metadata/python-net/groupdocs.metadata.search/specification)



The OfTypeSpecification type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.search/oftypespecification/__init__/#groupdocs.metadata.common.MetadataPropertyType) | Initializes a new instance of the [`OfTypeSpecification`](/metadata/python-net/groupdocs.metadata.search/oftypespecification) class. |


### Properties
| Property | Description |
| :- | :- |
| [property_type](/metadata/python-net/groupdocs.metadata.search/oftypespecification/property_type) | Gets the type of properties that satisfy the specification. |


### Methods
| Method | Description |
| :- | :- |
| [is_satisfied_by](/metadata/python-net/groupdocs.metadata.search/oftypespecification/is_satisfied_by/#groupdocs.metadata.common.MetadataProperty) | Verifies whether a [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty) satisfies the specification. |
| [both](/metadata/python-net/groupdocs.metadata.search/oftypespecification/both/#groupdocs.metadata.search.Specification) | Combines two search specifications using the logical AND operator. |
| [either](/metadata/python-net/groupdocs.metadata.search/oftypespecification/either/#groupdocs.metadata.search.Specification) | Combines two search specifications using the logical OR operator. |
| [is_not](/metadata/python-net/groupdocs.metadata.search/oftypespecification/is_not/#) | Negates the specification. |



### See Also
* module [`groupdocs.metadata.search`](..)
* class [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty)
* class [`OfTypeSpecification`](/metadata/python-net/groupdocs.metadata.search/oftypespecification)
* class [`Specification`](/metadata/python-net/groupdocs.metadata.search/specification)
