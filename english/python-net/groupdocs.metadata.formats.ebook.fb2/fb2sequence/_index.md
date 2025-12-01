---
title: Fb2Sequence class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 40
url: /python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence/
is_root: false
---

## Fb2Sequence class

Represents an information about the sequence of the book.



**Inheritance:** [`Fb2Sequence`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Fb2Sequence type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self, name, number, lang)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence/__init__/#system.string-int-system.string) | Constructs a new instance of Fb2Sequence |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence/count) | Gets the number of metadata properties. |
| [name](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence/name) | Series title |
| [number](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence/number) | Book number in the series. |
| [lang](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence/lang) | Gets the language. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### See Also
* module [`groupdocs.metadata.formats.ebook.fb2`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`Fb2Sequence`](/metadata/python-net/groupdocs.metadata.formats.ebook.fb2/fb2sequence)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
