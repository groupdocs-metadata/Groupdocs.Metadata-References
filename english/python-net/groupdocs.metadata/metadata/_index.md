---
title: Metadata class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata/metadata/
is_root: false
weight: 20
---

## Metadata class

Provides the main class to access metadata in all supported formats.



The Metadata type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata/metadata/__init__/#System.String) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class. |
| [__init__](/metadata/python-net/groupdocs.metadata/metadata/__init__/#io.RawIOBase) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class. |
| [__init__](/metadata/python-net/groupdocs.metadata/metadata/__init__/#System.String-groupdocs.metadata.options.LoadOptions) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class. |
| [__init__](/metadata/python-net/groupdocs.metadata/metadata/__init__/#io.RawIOBase-groupdocs.metadata.options.LoadOptions) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class. |
| [__init__](/metadata/python-net/groupdocs.metadata/metadata/__init__/#System.Uri) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class. |
| [__init__](/metadata/python-net/groupdocs.metadata/metadata/__init__/#System.Uri-groupdocs.metadata.options.LoadOptions) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class. |


### Properties
| Property | Description |
| :- | :- |
| [file_format](/metadata/python-net/groupdocs.metadata/metadata/file_format) | Gets the type of the loaded file (if recognized). |


### Methods
| Method | Description |
| :- | :- |
| [save](/metadata/python-net/groupdocs.metadata/metadata/save/#) | Saves all changes made in the loaded document. |
| [save](/metadata/python-net/groupdocs.metadata/metadata/save/#io.RawIOBase) | Saves the document content into a stream. |
| [save](/metadata/python-net/groupdocs.metadata/metadata/save/#System.String) | Saves the document content to the specified file. |
| [copy_to](/metadata/python-net/groupdocs.metadata/metadata/copy_to/#groupdocs.metadata.common.MetadataPackage) | Copy known metadata properties from source package to destination package.<br/>The operation is recursive so it affects all nested packages as well.<br/>If an existing property its value is updated. <br/>If there is a known property missing in a destination package it is added to the package.<br/>If there is a known property missing in a source package it is not remove from destination package. If that need, use Sanitize method before. |
| [copy_to](/metadata/python-net/groupdocs.metadata/metadata/copy_to/#groupdocs.metadata.common.MetadataPackage-System.Collections.Generic.List`1[[GroupDocs.Metadata.Tagging.PropertyTag]]) |  |
| [get_root_package](/metadata/python-net/groupdocs.metadata/metadata/get_root_package/#) | Gets the root package providing access to all metadata properties extracted from the file. |
| [find_properties](/metadata/python-net/groupdocs.metadata/metadata/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata/metadata/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata/metadata/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata/metadata/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata/metadata/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`Metadata.add_properties`](/metadata/python-net/groupdocs.metadata/metadata/add_properties) and [`Metadata.update_properties`](/metadata/python-net/groupdocs.metadata/metadata/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata/metadata/sanitize/#) | Removes writable metadata properties from all detected packages or whole packages if possible.<br/>The operation is recursive so it affects all nested packages as well. |
| [generate_preview](/metadata/python-net/groupdocs.metadata/metadata/generate_preview/#groupdocs.metadata.options.PreviewOptions) | Creates preview images for specified pages. |
| [get_document_info](/metadata/python-net/groupdocs.metadata/metadata/get_document_info/#) | Gets common information about the loaded document. |



### See Also
* module [`groupdocs.metadata`](..)
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata)
