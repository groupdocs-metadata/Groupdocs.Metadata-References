---
title: Fb2PublishInfo class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 30
url: /python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/
is_root: false
---

## Fb2PublishInfo class

Information about the paper (or other) publication on the basis of which the FB2.x document was created. It is not recommended to fill in data from an arbitrary publication if the source is unknown, except for the case when verification was carried out on it and the document was brought to the form of this publication. If the source is unknown, it is better to omit this element altogether.



**Inheritance:** [`Fb2PublishInfo`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Fb2PublishInfo type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/count) | Gets the number of metadata properties. |
| [book_name](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/book_name) | The title of the original (paper) book. |
| [publisher](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/publisher) | The title of the original (paper) book. |
| [city](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/city) | City, place of publication of the original (paper) book. |
| [year](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/year) | Year of publication of the original (paper) book. |
| [isbn](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/isbn) | ISBN of the original (paper) book. |
| [sequence](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/sequence) | The series of publications that the book belongs to and the number in the series. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### See Also
* module [`groupdocs.metadata.formats.ebook.fb2`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`Fb2PublishInfo`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
