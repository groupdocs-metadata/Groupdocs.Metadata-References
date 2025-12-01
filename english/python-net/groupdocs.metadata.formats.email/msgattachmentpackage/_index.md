---
title: MsgAttachmentPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 70
url: /python-net/groupdocs.metadata.formats.email/msgattachmentpackage/
is_root: false
---

## MsgAttachmentPackage class

Represents a metadata package containing email attachment name and data.



**Inheritance:** [`MsgAttachmentPackage`](/metadata/python-net/groupdocs.metadata.formats.email/msgattachmentpackage) → 
[`EmailAttachmentPackage`](/metadata/python-net/groupdocs.metadata.formats.email/emailattachmentpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The MsgAttachmentPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self, name, content)`](/metadata/python-net/groupdocs.metadata.formats.email/msgattachmentpackage/__init__/#system.string-bytes) | MsgAttachmentPackage constructor |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.email/msgattachmentpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.email/msgattachmentpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.email/msgattachmentpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.email/msgattachmentpackage/count) | Gets the number of metadata properties. |
| [name](/metadata/python-net/groupdocs.metadata.formats.email/msgattachmentpackage/name) | Gets the attachment name. |
| [content](/metadata/python-net/groupdocs.metadata.formats.email/msgattachmentpackage/content) | Gets the last attachment data on byte array. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.email/msgattachmentpackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.email/msgattachmentpackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.email/msgattachmentpackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.email/msgattachmentpackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.email/msgattachmentpackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.email/msgattachmentpackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.email/msgattachmentpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### See Also
* module [`groupdocs.metadata.formats.email`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`EmailAttachmentPackage`](/metadata/python-net/groupdocs.metadata.formats.email/emailattachmentpackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`MsgAttachmentPackage`](/metadata/python-net/groupdocs.metadata.formats.email/msgattachmentpackage)
