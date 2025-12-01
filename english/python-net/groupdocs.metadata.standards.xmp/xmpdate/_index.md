---
title: XmpDate class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 110
url: /python-net/groupdocs.metadata.standards.xmp/xmpdate/
is_root: false
---

## XmpDate class

Represents Date in XMP packet.



**Inheritance:** [`XmpDate`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate) → 
[`XmpValueBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpvaluebase) → 
[`PropertyValue`](/metadata/python-net/groupdocs.metadata.common/propertyvalue)



The XmpDate type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self, date_time)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate/__init__/#system.datetime) | Initializes a new instance of the [`XmpDate`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate) class. |
| [`__init__(self, date_string)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate/__init__/#system.string) | Initializes a new instance of the [`XmpDate`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate) class. |


### Properties
| Property | Description |
| :- | :- |
| [type](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate/type) | Gets the [`MetadataPropertyType`](/metadata/python-net/groupdocs.metadata.common/metadatapropertytype). |
| [raw_value](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate/raw_value) | Gets the raw value. |
| [value](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate/value) | Gets the value. |
| [format](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate/format) | Gets format string for current value. |
| [ISO_8601_FORMAT](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate/iso_8601_format) | The ISO 8601 (roundtrip) format string. |


### Methods
| Method | Description |
| :- | :- |
| [`accept_value(self, value_acceptor)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate/accept_value/#groupdocs.metadata.common.valueacceptor) | Extracts the property value using a custom [`ValueAcceptor`](/metadata/python-net/groupdocs.metadata.common/valueacceptor). |
| [`get_xmp_representation(self)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate/get_xmp_representation/#) | Returns string contained value in XMP format. |



### Remarks 


A date-time value is represented using a subset of the formats as defined in Date and Time Formats:
YYYY
YYYY-MM
YYYY-MM-DD
YYYY-MM-DDThh:mmTZD
YYYY-MM-DDThh:mm:ssTZD
YYYY-MM-DDThh:mm:ss.sTZD

### See Also
* module [`groupdocs.metadata.standards.xmp`](..)
* class [`MetadataPropertyType`](/metadata/python-net/groupdocs.metadata.common/metadatapropertytype)
* class [`PropertyValue`](/metadata/python-net/groupdocs.metadata.common/propertyvalue)
* class [`ValueAcceptor`](/metadata/python-net/groupdocs.metadata.common/valueacceptor)
* class [`XmpDate`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate)
* class [`XmpValueBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpvaluebase)
