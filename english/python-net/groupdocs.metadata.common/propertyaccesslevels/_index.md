---
title: PropertyAccessLevels enumeration
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.common/propertyaccesslevels/
is_root: false
weight: 220
---

## PropertyAccessLevels enumeration

Defines access levels for metadata properties.



The PropertyAccessLevels type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| READ | The property is read-only. |
| UPDATE | It is possible to update the property using the [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties) method. |
| REMOVE | The property can be removed through the [`MetadataPackage.remove_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/remove_properties) method. |
| ADD | It is possible to update the property using the [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) method. |
| FULL | Grants full access to the property. |
| ADD_OR_UPDATE | It is allowed to add and update the property. All other operations are restricted. |



### See Also
* module [`groupdocs.metadata.common`](..)
