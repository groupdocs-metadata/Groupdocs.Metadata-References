---
title: ContainsTagSpecification class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.search/containstagspecification/
is_root: false
weight: 30
---

## ContainsTagSpecification class

Represents a specification that checks whether the passed property contains the specified tag.



**Inheritance:** [`ContainsTagSpecification`](/metadata/python-net/groupdocs.metadata.search/containstagspecification) → 
[`Specification`](/metadata/python-net/groupdocs.metadata.search/specification)



The ContainsTagSpecification type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.search/containstagspecification/__init__/#groupdocs.metadata.tagging.PropertyTag) | Initializes a new instance of the [`ContainsTagSpecification`](/metadata/python-net/groupdocs.metadata.search/containstagspecification) class. |


### Properties
| Property | Description |
| :- | :- |
| [tag](/metadata/python-net/groupdocs.metadata.search/containstagspecification/tag) | Gets the tag a property must contain to satisfy the specification. |


### Methods
| Method | Description |
| :- | :- |
| [is_satisfied_by](/metadata/python-net/groupdocs.metadata.search/containstagspecification/is_satisfied_by/#groupdocs.metadata.common.MetadataProperty) | Verifies whether a [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty) satisfies the specification. |
| [both](/metadata/python-net/groupdocs.metadata.search/containstagspecification/both/#groupdocs.metadata.search.Specification) | Combines two search specifications using the logical AND operator. |
| [either](/metadata/python-net/groupdocs.metadata.search/containstagspecification/either/#groupdocs.metadata.search.Specification) | Combines two search specifications using the logical OR operator. |
| [is_not](/metadata/python-net/groupdocs.metadata.search/containstagspecification/is_not/#) | Negates the specification. |



### See Also
* module [`groupdocs.metadata.search`](..)
* class [`ContainsTagSpecification`](/metadata/python-net/groupdocs.metadata.search/containstagspecification)
* class [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty)
* class [`Specification`](/metadata/python-net/groupdocs.metadata.search/specification)
