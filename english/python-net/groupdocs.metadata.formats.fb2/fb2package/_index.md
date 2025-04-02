---
title: Fb2Package class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.fb2/fb2package/
is_root: false
weight: 10
---

## Fb2Package class

Represents metadata in a Fb2 e-book.



**Inheritance:** [`Fb2Package`](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Fb2Package type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package/count) | Gets the number of metadata properties. |
| [title_info](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package/title_info) | Description of information about the work (including translation, but excluding publication). |
| [src_title_info](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package/src_title_info) | Description of information about the work in the original language (not available for the original book). |
| [document_info](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package/document_info) | Description of information about a specific FB2.x document (creator(s), history, etc.). |
| [publish_info](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package/publish_info) | Information about the paper (or other) publication on the basis of which the FB2.x document was created. It is not recommended to fill in data from an arbitrary publication if the source is unknown, except for the case when verification was carried out on it and the document was brought to the form of this publication. If the source is unknown, it is better to omit this element altogether. |
| [custom_info](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package/custom_info) | Some information about the document that is not provided in the rest of the description. This may be either just some information from the author or some information that may be useful to some FB2 software. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.fb2`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`Fb2Package`](/metadata/python-net/groupdocs.metadata.formats.fb2/fb2package)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
