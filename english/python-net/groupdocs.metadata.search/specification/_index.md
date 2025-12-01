---
title: Specification class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 80
url: /python-net/groupdocs.metadata.search/specification/
is_root: false
---

## Specification class

Provides a base abstract class for search specifications that can be combined using logical operators.



The Specification type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [`is_satisfied_by(self, candidate)`](/metadata/python-net/groupdocs.metadata.search/specification/is_satisfied_by/#groupdocs.metadata.common.metadataproperty) | Verifies whether a [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty) satisfies the specification. |
| [`both(self, other)`](/metadata/python-net/groupdocs.metadata.search/specification/both/#groupdocs.metadata.search.specification) | Combines two search specifications using the logical AND operator. |
| [`either(self, other)`](/metadata/python-net/groupdocs.metadata.search/specification/either/#groupdocs.metadata.search.specification) | Combines two search specifications using the logical OR operator. |
| [`is_not(self)`](/metadata/python-net/groupdocs.metadata.search/specification/is_not/#) | Negates the specification. |



### See Also
* module [`groupdocs.metadata.search`](..)
* class [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty)
