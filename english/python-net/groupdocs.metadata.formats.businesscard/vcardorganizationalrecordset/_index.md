---
title: VCardOrganizationalRecordset class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 140
url: /python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/
is_root: false
---

## VCardOrganizationalRecordset class

Represents a set of Organizational vCard records.
These properties are concerned with information associated with
characteristics of the organization or organizational units of 
the object that the vCard represents.



**Inheritance:** [`VCardOrganizationalRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset) → 
[`VCardRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecordset) → 
[`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The VCardOrganizationalRecordset type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/count) | Gets the number of metadata properties. |
| [title_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/title_records) | Gets the positions or jobs of the object. |
| [titles](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/titles) | Gets the positions or jobs of the object. |
| [role_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/role_records) | Gets the functions or parts played in a particular situation by the object. |
| [roles](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/roles) | Gets the functions or parts played in a particular situation by the object. |
| [logo_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logo_records) | Gets the graphic images of the logo associated with the object. |
| [logo_binary_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logo_binary_records) | Gets the graphic images of the logo associated with the object. |
| [binary_logos](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/binary_logos) | Gets the graphic images of the logo associated with the object. |
| [logo_uri_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logo_uri_records) | Gets the URIs of the graphic images of the logo associated with the object. |
| [uri_logos](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/uri_logos) | Gets the URIs of the graphic images of the logo associated with the object. |
| [agent_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agent_records) | Gets the information about another person who will act on behalf of the vCard object. |
| [agent_object_record](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agent_object_record) | Gets the information about another person who will act on behalf of the vCard object. |
| [object_agent](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/object_agent) | Gets the information about another person who will act on behalf of the vCard object. |
| [agent_uri_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agent_uri_records) | Gets the information about another person who will act on behalf of the vCard object. |
| [uri_agents](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/uri_agents) | Gets the information about another person who will act on behalf of the vCard object. |
| [organization_name_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/organization_name_records) | Gets the organizational names and units associated with the object. |
| [organization_names](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/organization_names) | Gets the organizational names and units associated with the object. |
| [member_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/member_records) | Gets the members in the group this vCard represents. |
| [members](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/members) | Gets the members in the group this vCard represents. |
| [relationship_records](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/relationship_records) | Gets the relationships between another entity and the entity represented by this vCard. |
| [relationships](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/relationships) | Gets the relationships between another entity and the entity represented by this vCard. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.businesscard`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`VCardBasePackage`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardbasepackage)
* class [`VCardOrganizationalRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset)
* class [`VCardRecordset`](/metadata/python-net/groupdocs.metadata.formats.businesscard/vcardrecordset)
