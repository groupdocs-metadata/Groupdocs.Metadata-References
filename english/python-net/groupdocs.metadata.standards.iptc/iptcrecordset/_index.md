---
title: IptcRecordSet class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.standards.iptc/iptcrecordset/
is_root: false
weight: 60
---

## IptcRecordSet class

Represents a collection of IPTC records.



**Inheritance:** [`IptcRecordSet`](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The IptcRecordSet type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/__init__/#) | Initializes a new instance of the [`IptcRecordSet`](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset) class. |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/__init__/#list) | Initializes a new instance of the [`IptcRecordSet`](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/count) | Gets the number of metadata properties. |
| [envelope_record](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/envelope_record) | Gets or sets the Envelope Record. |
| [application_record](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/application_record) | Gets or sets the Application Record. |


### Indexer
| Name | Description |
| :- | :- |
| [index] |  |


### Methods
| Method | Description |
| :- | :- |
| [remove](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/remove/#int-int) | Removes the dataSet with the specified record and dataSet number. |
| [remove](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/remove/#int) | Removes the record with the specified record number. |
| [contains](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [set](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/set/#groupdocs.metadata.standards.iptc.IptcDataSet) | Adds or updates the specified dataSet in the appropriate record. |
| [add](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/add/#groupdocs.metadata.standards.iptc.IptcDataSet) | Adds the specified dataSet to the appropriate record. <br/>The dataSet is considered as repeatable if a dataSet with the specified number already exists. |
| [clear](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/clear/#) | Removes all records from the collection. |
| [to_data_set_list](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/to_data_set_list/#) | Creates a list of dataSets from the package. |
| [to_list](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/to_list/#) | Creates a list from the package. |



### Remarks 


**Learn more** |
|
 |

### Example 


This code sample shows hot to update basic IPTC metadata properties.

### See Also
* module [`groupdocs.metadata.standards.iptc`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`IptcRecordSet`](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
