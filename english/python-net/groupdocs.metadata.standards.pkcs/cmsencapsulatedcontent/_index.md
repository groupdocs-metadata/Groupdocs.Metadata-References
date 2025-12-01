---
title: CmsEncapsulatedContent class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 40
url: /python-net/groupdocs.metadata.standards.pkcs/cmsencapsulatedcontent/
is_root: false
---

## CmsEncapsulatedContent class

Represents a signed content container, consisting of a content type identifier and the content itself.



**Inheritance:** [`CmsEncapsulatedContent`](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmsencapsulatedcontent) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The CmsEncapsulatedContent type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmsencapsulatedcontent/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmsencapsulatedcontent/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmsencapsulatedcontent/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmsencapsulatedcontent/count) | Gets the number of metadata properties. |
| [content_type](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmsencapsulatedcontent/content_type) | Gets the object identifier uniquely specifies the content type. |
| [content_raw_data](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmsencapsulatedcontent/content_raw_data) | Gets the raw data of content info. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmsencapsulatedcontent/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmsencapsulatedcontent/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmsencapsulatedcontent/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmsencapsulatedcontent/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmsencapsulatedcontent/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmsencapsulatedcontent/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmsencapsulatedcontent/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### See Also
* module [`groupdocs.metadata.standards.pkcs`](..)
* class [`CmsEncapsulatedContent`](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmsencapsulatedcontent)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
