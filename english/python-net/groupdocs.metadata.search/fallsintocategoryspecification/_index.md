---
title: FallsIntoCategorySpecification class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.search/fallsintocategoryspecification/
is_root: false
weight: 40
---

## FallsIntoCategorySpecification class

Represents a specification that verifies whether the passed property falls into a particular category
(i.e. contains tags from the specified category).



**Inheritance:** [`FallsIntoCategorySpecification`](/metadata/python-net/groupdocs.metadata.search/fallsintocategoryspecification) → 
[`Specification`](/metadata/python-net/groupdocs.metadata.search/specification)



The FallsIntoCategorySpecification type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.search/fallsintocategoryspecification/__init__/#groupdocs.metadata.tagging.TagCategory) | Initializes a new instance of the [`FallsIntoCategorySpecification`](/metadata/python-net/groupdocs.metadata.search/fallsintocategoryspecification) class. |


### Properties
| Property | Description |
| :- | :- |
| [category](/metadata/python-net/groupdocs.metadata.search/fallsintocategoryspecification/category) | Gets the category into which a property must fall to satisfy the specification. |


### Methods
| Method | Description |
| :- | :- |
| [is_satisfied_by](/metadata/python-net/groupdocs.metadata.search/fallsintocategoryspecification/is_satisfied_by/#groupdocs.metadata.common.MetadataProperty) | Verifies whether a [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty) satisfies the specification. |
| [both](/metadata/python-net/groupdocs.metadata.search/fallsintocategoryspecification/both/#groupdocs.metadata.search.Specification) | Combines two search specifications using the logical AND operator. |
| [either](/metadata/python-net/groupdocs.metadata.search/fallsintocategoryspecification/either/#groupdocs.metadata.search.Specification) | Combines two search specifications using the logical OR operator. |
| [is_not](/metadata/python-net/groupdocs.metadata.search/fallsintocategoryspecification/is_not/#) | Negates the specification. |



### See Also
* module [`groupdocs.metadata.search`](..)
* class [`FallsIntoCategorySpecification`](/metadata/python-net/groupdocs.metadata.search/fallsintocategoryspecification)
* class [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty)
* class [`Specification`](/metadata/python-net/groupdocs.metadata.search/specification)
