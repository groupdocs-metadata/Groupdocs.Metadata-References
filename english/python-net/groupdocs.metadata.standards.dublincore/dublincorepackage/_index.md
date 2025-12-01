---
title: DublinCorePackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 10
url: /python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/
is_root: false
---

## DublinCorePackage class

Represents a Dublin Core metadata package.



**Inheritance:** [`DublinCorePackage`](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The DublinCorePackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/count) | Gets the number of metadata properties. |
| [contributor](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/contributor) | Gets the contributor Dublin Core element. |
| [coverage](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/coverage) | Gets the coverage Dublin Core element. |
| [creator](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/creator) | Gets the creator Dublin Core element. |
| [date](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/date) | Gets the date Dublin Core element. |
| [description](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/description) | Gets the description Dublin Core element. |
| [format](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/format) | Gets the format Dublin Core element. |
| [language](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/language) | Gets the language Dublin Core element. |
| [publisher](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/publisher) | Gets the publisher Dublin Core element. |
| [relation](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/relation) | Gets the relation Dublin Core element. |
| [source](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/source) | Gets the source Dublin Core element. |
| [subject](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/subject) | Gets the subject Dublin Core element. |
| [title](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/title) | Gets the title Dublin Core element. |
| [type](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/type) | Gets the type Dublin Core element. |
| [rights](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/rights) | Gets the rights Dublin Core element. |
| [identifier](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/identifier) | Gets the identifier Dublin Core element. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### See Also
* module [`groupdocs.metadata.standards.dublincore`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`DublinCorePackage`](/metadata/python-net/groupdocs.metadata.standards.dublincore/dublincorepackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
