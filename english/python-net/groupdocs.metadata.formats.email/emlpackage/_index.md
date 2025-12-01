---
title: EmlPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 50
url: /python-net/groupdocs.metadata.formats.email/emlpackage/
is_root: false
---

## EmlPackage class

Represents EML message metadata.



**Inheritance:** [`EmlPackage`](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage) → 
[`EmailPackage`](/metadata/python-net/groupdocs.metadata.formats.email/emailpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The EmlPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/count) | Gets the number of metadata properties. |
| [subject](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/subject) | Gets or sets the email subject. |
| [recipients](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/recipients) | Gets or sets the array of the email recipients. |
| [carbon_copy_recipients](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/carbon_copy_recipients) | Gets or sets the array of CC (carbon copy) recipients of the email message. |
| [blind_carbon_copy_recipients](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/blind_carbon_copy_recipients) | Gets or sets the array of BCC (blind carbon copy) recipients of the email message. |
| [sender_email_address](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/sender_email_address) | Gets the email address of the sender. |
| [headers](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/headers) | Gets a metadata package containing the email headers. |
| [attachments](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/attachments) | Gets an array of the attached files. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.email`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`EmailPackage`](/metadata/python-net/groupdocs.metadata.formats.email/emailpackage)
* class [`EmlPackage`](/metadata/python-net/groupdocs.metadata.formats.email/emlpackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
