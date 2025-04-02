---
title: IptcEnvelopeRecord class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/
is_root: false
weight: 40
---

## IptcEnvelopeRecord class

Represents an IPTC Envelope Record.



**Inheritance:** [`IptcEnvelopeRecord`](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord) → 
[`IptcRecord`](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecord) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The IptcEnvelopeRecord type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/__init__/#) | Initializes a new instance of the [`IptcEnvelopeRecord`](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/count) | Gets the number of metadata properties. |
| [record_number](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/record_number) | Gets the record number. |
| [model_version](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/model_version) | Gets or sets a number identifying the version of the information. |
| [destination](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/destination) | Gets or sets the destination. |
| [destinations](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/destinations) | Gets or sets an array of destinations. |
| [file_format](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/file_format) | Gets or sets the file format. |
| [file_format_version](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/file_format_version) | Gets or sets the file format version.<br/>A number representing the particular version of the File Format specified in [`IptcEnvelopeRecord.file_format`](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord#file_format). |
| [service_identifier](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/service_identifier) | Gets or sets the service identifier. |
| [product_id](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/product_id) | Gets or sets the product identifier. |
| [product_ids](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/product_ids) | Gets or sets the product identifiers. |
| [date_sent](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/date_sent) | Gets or sets the date the service sent the material. |


### Indexer
| Name | Description |
| :- | :- |
| [index] |  |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [to_list](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord/to_list/#) | Creates a list from the package. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.standards.iptc`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`IptcEnvelopeRecord`](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecord)
* class [`IptcRecord`](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecord)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
