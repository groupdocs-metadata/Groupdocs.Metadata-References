---
title: Metadata class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/groupdocs.metadata/metadata/
is_root: false
---

## Metadata class

Provides the main class to access metadata in all supported formats.



The Metadata type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self, file_path)`](/metadata/python-net/groupdocs.metadata/metadata/__init__/#system.string) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class. |
| [`__init__(self, document)`](/metadata/python-net/groupdocs.metadata/metadata/__init__/#io.rawiobase) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class. |
| [`__init__(self, file_path, load_options)`](/metadata/python-net/groupdocs.metadata/metadata/__init__/#system.string-groupdocs.metadata.options.loadoptions) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class. |
| [`__init__(self, document, load_options)`](/metadata/python-net/groupdocs.metadata/metadata/__init__/#io.rawiobase-groupdocs.metadata.options.loadoptions) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class. |
| [`__init__(self, uri)`](/metadata/python-net/groupdocs.metadata/metadata/__init__/#system.uri) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class. |
| [`__init__(self, uri, load_options)`](/metadata/python-net/groupdocs.metadata/metadata/__init__/#system.uri-groupdocs.metadata.options.loadoptions) | Initializes a new instance of the [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata) class. |


### Properties
| Property | Description |
| :- | :- |
| [file_format](/metadata/python-net/groupdocs.metadata/metadata/file_format) | Gets the type of the loaded file (if recognized). |


### Methods
| Method | Description |
| :- | :- |
| [`save(self)`](/metadata/python-net/groupdocs.metadata/metadata/save/#) | Saves all changes made in the loaded document. |
| [`save(self, document)`](/metadata/python-net/groupdocs.metadata/metadata/save/#io.rawiobase) | Saves the document content into a stream. |
| [`save(self, file_path)`](/metadata/python-net/groupdocs.metadata/metadata/save/#system.string) | Saves the document content to the specified file. |
| [`copy_to(self, metadata)`](/metadata/python-net/groupdocs.metadata/metadata/copy_to/#groupdocs.metadata.common.metadatapackage) | Copy known metadata properties from source package to destination package.<br/>The operation is recursive so it affects all nested packages as well.<br/>If an existing property its value is updated. <br/>If there is a known property missing in a destination package it is added to the package.<br/>If there is a known property missing in a source package it is not remove from destination package. If that need, use Sanitize method before. |
| [`copy_to(self, metadata, tags)`](/metadata/python-net/groupdocs.metadata/metadata/copy_to/#groupdocs.metadata.common.metadatapackage-system.collections.generic.list`1[[groupdocs.metadata.tagging.propertytag]]) |  |
| [`get_root_package(self)`](/metadata/python-net/groupdocs.metadata/metadata/get_root_package/#) | Gets the root package providing access to all metadata properties extracted from the file. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata/metadata/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata/metadata/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata/metadata/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata/metadata/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata/metadata/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`Metadata.add_properties`](/metadata/python-net/groupdocs.metadata/metadata/add_properties) and [`Metadata.update_properties`](/metadata/python-net/groupdocs.metadata/metadata/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata/metadata/sanitize/#) | Removes writable metadata properties from all detected packages or whole packages if possible.<br/>The operation is recursive so it affects all nested packages as well. |
| [`generate_preview(self, preview_options)`](/metadata/python-net/groupdocs.metadata/metadata/generate_preview/#groupdocs.metadata.options.previewoptions) | Creates preview images for specified pages. |
| [`get_document_info(self)`](/metadata/python-net/groupdocs.metadata/metadata/get_document_info/#) | Gets common information about the loaded document. |



### See Also
* module [`groupdocs.metadata`](..)
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata)
