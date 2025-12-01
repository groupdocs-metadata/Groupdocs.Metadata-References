---
title: CadPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/groupdocs.metadata.formats.cad/cadpackage/
is_root: false
---

## CadPackage class

Represents CAD (Computer-aided design) metadata.



**Inheritance:** [`CadPackage`](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The CadPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/count) | Gets the number of metadata properties. |
| [acad_version](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/acad_version) | Gets the AutoCAD drawing database version number. |
| [height](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/height) | Gets the drawing height. |
| [width](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/width) | Gets the drawing width. |
| [author](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/author) | Gets the drawing author. |
| [comments](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/comments) | Gets the user comments. |
| [hyperlink_base](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/hyperlink_base) | Gets the hyperlink base. |
| [keywords](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/keywords) | Gets the keywords. |
| [last_saved_by](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/last_saved_by) | Gets the name of the last editor. |
| [revision_number](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/revision_number) | Gets the revision number. |
| [subject](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/subject) | Gets the subject. |
| [title](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/title) | Gets the title. |
| [created_date_time](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/created_date_time) | Gets the date and time when the drawing was created. |
| [modified_date_time](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/modified_date_time) | Gets the date and time when the drawing was modified. |
| [custom_properties](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/custom_properties) | Gets the package containing custom metadata properties. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.cad`](..)
* class [`CadPackage`](/metadata/python-net/groupdocs.metadata.formats.cad/cadpackage)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
