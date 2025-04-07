---
title: PDBHeader class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/
is_root: false
weight: 40
---

## PDBHeader class

Represents metadata in a Mobi e-book.



**Inheritance:** [`PDBHeader`](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The PDBHeader type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/count) | Gets the number of metadata properties. |
| [name](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/name) | Gets the Mobi e-book name. |
| [attributes](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/attributes) | Gets the mobi attributes. |
| [version](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/version) | Gets the Mobi version. |
| [creation_date](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/creation_date) | Gets the creation date. |
| [modification_date](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/modification_date) | Gets the modification date. |
| [last_backup_date](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/last_backup_date) | Gets the last backup date. |
| [modification_number](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/modification_number) | Gets the modification number. |
| [app_info_id](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/app_info_id) | Gets the app info ID. |
| [sort_info_id](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/sort_info_id) | Gets the sort info ID. |
| [type](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/type) | Gets the type. |
| [creator](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/creator) | Gets the creator. |
| [unique_id_seed](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/unique_id_seed) | Gets the unique ID seed. |
| [next_record_list](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/next_record_list) |  |
| [num_records](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/num_records) | Gets the num records. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.ebook.mobi`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`PDBHeader`](/metadata/python-net/groupdocs.metadata.formats.ebook.mobi/pdbheader)
