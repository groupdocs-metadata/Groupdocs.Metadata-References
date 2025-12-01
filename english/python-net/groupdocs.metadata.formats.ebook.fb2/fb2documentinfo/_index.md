---
title: Fb2DocumentInfo class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/
is_root: false
---

## Fb2DocumentInfo class

Description of information about the work (including translation, but excluding publication).



**Inheritance:** [`Fb2DocumentInfo`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Fb2DocumentInfo type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/count) | Gets the number of metadata properties. |
| [authors](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/authors) | Information about the author of the document |
| [program_used](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/program_used) | The programs that were used in preparing the document are listed. |
| [date](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/date) | Date |
| [src_url](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/src_url) | Where did the original document available online come from |
| [src_ocr](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/src_ocr) | The author of the OCR or original document posted online. |
| [id](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/id) | Gets the Id. |
| [version](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/version) | FB2 document version. |
| [publishers](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/publishers) | Information about the author of the document |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### See Also
* module [`groupdocs.metadata.formats.ebook.fb2`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`Fb2DocumentInfo`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2documentinfo)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
