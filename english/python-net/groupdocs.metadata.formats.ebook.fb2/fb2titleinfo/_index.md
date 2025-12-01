---
title: Fb2TitleInfo class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 50
url: /python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/
is_root: false
---

## Fb2TitleInfo class

Description of information about the work (including translation, but excluding publication).



**Inheritance:** [`Fb2TitleInfo`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Fb2TitleInfo type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/count) | Gets the number of metadata properties. |
| [book_title](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/book_title) | The title of the book. It can either match the book title (book-name) or differ (for example, when there are several works under one cover). |
| [authors](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/authors) | Information about the author of the book |
| [genres](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/genres) | Describes the genre of the book. It is used to place the book in the library rubricator, for this reason the list of possible genres is strictly defined. It is allowed to specify several genres. |
| [keywords](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/keywords) | List of keywords for the book. Intended for use by search engines. |
| [date](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/date) | Date |
| [coverpage](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/coverpage) | Contains a link to a graphic image of the book cover. |
| [lang](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/lang) | Language of the book (work) |
| [src_lang](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/src_lang) | Original language (for translations). |
| [translators](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/translators) | Information about the author of the book |
| [sequence](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/sequence) | The series of publications that the book belongs to and the number in the series. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### See Also
* module [`groupdocs.metadata.formats.ebook.fb2`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`Fb2TitleInfo`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
