---
title: RiffInfoPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.riff/riffinfopackage/
is_root: false
weight: 10
---

## RiffInfoPackage class

Represents the metadata package containing properties extracted from the RIFF INFO chunk.



**Inheritance:** [`RiffInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The RiffInfoPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/count) | Gets the number of metadata properties. |
| [artist](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/artist) | Gets the artist of the original subject of the file. |
| [comment](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/comment) | Gets the comment about the file or the subject of the file. |
| [copyright](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/copyright) | Gets the copyright information for the file. |
| [creation_date](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/creation_date) | Gets the date the subject of the file was created. |
| [engineer](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/engineer) | Gets the name of the engineer who worked on the file. |
| [genre](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/genre) | Gets the genre of the original work. |
| [keywords](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/keywords) | Gets the keywords that refer to the file or subject of the file. |
| [name](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/name) | Gets the title of the subject of the file. |
| [subject](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/subject) | Gets a description of the file contents, such as "Aerial view of Seattle." |
| [software](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/software) | Gets the name of the software package used to create the file. |
| [source](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/source) | Gets the name of the person or organization who supplied the original subject of the file. |
| [technician](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/technician) | Gets the technician who digitized the subject file. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### See Also
* module [`groupdocs.metadata.formats.riff`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`RiffInfoPackage`](/metadata/python-net/groupdocs.metadata.formats.riff/riffinfopackage)
