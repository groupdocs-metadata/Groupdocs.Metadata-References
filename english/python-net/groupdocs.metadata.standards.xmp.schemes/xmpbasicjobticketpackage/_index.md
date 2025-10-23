---
title: XmpBasicJobTicketPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/
is_root: false
weight: 30
---

## XmpBasicJobTicketPackage class

Represents Basic Job-Ticket namespace.



**Inheritance:** [`XmpBasicJobTicketPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage) → 
[`XmpPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage) → 
[`XmpMetadataContainer`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmetadatacontainer) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The XmpBasicJobTicketPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/__init__/#) | Initializes a new instance of the [`XmpBasicJobTicketPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/count) | Gets the number of metadata properties. |
| [prefix](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/prefix) | Gets the xmlns prefix. |
| [namespace_uri](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/namespace_uri) | Gets the namespace URI. |
| [xml_namespace](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/xml_namespace) | Gets the XML namespace. |
| [jobs](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/jobs) | Gets or sets the jobs. |


### Methods
| Method | Description |
| :- | :- |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/set/#System.String-System.String) | Sets string property. |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/set/#System.String-int) | Sets integer property. |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/set/#System.String-bool) | Sets boolean property. |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/set/#System.String-System.DateTime) | Sets DateTime property. |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/set/#System.String-float) | Sets double property. |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/set/#System.String-groupdocs.metadata.standards.xmp.XmpValueBase) | Sets the value inherited from [`XmpValueBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/set/#System.String-groupdocs.metadata.standards.xmp.XmpComplexType) | Sets the value inherited from [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [set](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/set/#System.String-groupdocs.metadata.standards.xmp.XmpArray) | Sets the value inherited from [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray) . |
| [contains](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [get_xmp_representation](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/get_xmp_representation/#) | Converts the XMP value to the XML representation. |
| [remove](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/remove/#System.String) | Removes the property with the specified name. |
| [clear](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/clear/#) | Removes all XMP properties. |



### See Also
* module [`groupdocs.metadata.standards.xmp.schemes`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray)
* class [`XmpBasicJobTicketPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage)
* class [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype)
* class [`XmpMetadataContainer`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmetadatacontainer)
* class [`XmpPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage)
* class [`XmpValueBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpvaluebase)
