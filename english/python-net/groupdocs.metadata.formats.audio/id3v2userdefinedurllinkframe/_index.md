---
title: ID3V2UserDefinedUrlLinkFrame class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/
is_root: false
weight: 150
---

## ID3V2UserDefinedUrlLinkFrame class

Represents a WXXX frame in an [`ID3V2Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag).



**Inheritance:** [`ID3V2UserDefinedUrlLinkFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe) → 
[`ID3V2TagFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The ID3V2UserDefinedUrlLinkFrame type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/__init__/#System.String-System.String) | Initializes a new instance of the [`ID3V2UserDefinedUrlLinkFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe) class. |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/__init__/#groupdocs.metadata.formats.audio.ID3V2EncodingType-System.String-System.String) | Initializes a new instance of the [`ID3V2UserDefinedUrlLinkFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/count) | Gets the number of metadata properties. |
| [id](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/id) | Gets the id of the frame (four characters matching the pattern [A-Z0-9]). |
| [flags](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/flags) | Gets the frame flags. |
| [data](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/data) | Gets the frame data. |
| [encoding](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/encoding) | Gets the encoding of the frame. |
| [description](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/description) | Gets the description. |
| [url](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/url) | Gets the URL. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.audio`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`ID3V2Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag)
* class [`ID3V2TagFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe)
* class [`ID3V2UserDefinedUrlLinkFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
