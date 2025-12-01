---
title: XmpArray class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 30
url: /python-net/groupdocs.metadata.standards.xmp/xmparray/
is_root: false
---

## XmpArray class

Represents base abstraction for XMP array.



**Inheritance:** [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray) → 
[`XmpValueBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpvaluebase) → 
[`PropertyValue`](/metadata/python-net/groupdocs.metadata.common/propertyvalue)



The XmpArray type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self, array_type, items)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray/__init__/#groupdocs.metadata.standards.xmp.xmparraytype-list) | Initializes a new instance of the [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray) class. |
| [`__init__(self, array_type, items)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray/__init__/#groupdocs.metadata.standards.xmp.xmparraytype-list) | Initializes a new instance of the [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray) class. |


### Properties
| Property | Description |
| :- | :- |
| [type](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray/type) | Gets the [`MetadataPropertyType`](/metadata/python-net/groupdocs.metadata.common/metadatapropertytype). |
| [raw_value](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray/raw_value) | Gets the raw value. |
| [array_type](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray/array_type) | Gets the type of the XMP array. |


### Methods
| Method | Description |
| :- | :- |
| [`from_address(, array, type)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray/from_address/#list-groupdocs.metadata.standards.xmp.xmparraytype) | Creates an [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray) instance form a string array. |
| [`from_address(, array, type)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray/from_address/#list-groupdocs.metadata.standards.xmp.xmparraytype) | Creates an [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray) instance form an integer array. |
| [`from_address(, array, type)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray/from_address/#list-groupdocs.metadata.standards.xmp.xmparraytype) | Creates an [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray) instance form a date array. |
| [`from_address(, array, type)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray/from_address/#list-groupdocs.metadata.standards.xmp.xmparraytype) | Creates an [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray) instance form a double array. |
| [`accept_value(self, value_acceptor)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray/accept_value/#groupdocs.metadata.common.valueacceptor) | Extracts the property value using a custom [`ValueAcceptor`](/metadata/python-net/groupdocs.metadata.common/valueacceptor). |
| [`get_xmp_representation(self)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray/get_xmp_representation/#) | Converts XMP value to the xml representation. |



### See Also
* module [`groupdocs.metadata.standards.xmp`](..)
* class [`MetadataPropertyType`](/metadata/python-net/groupdocs.metadata.common/metadatapropertytype)
* class [`PropertyValue`](/metadata/python-net/groupdocs.metadata.common/propertyvalue)
* class [`ValueAcceptor`](/metadata/python-net/groupdocs.metadata.common/valueacceptor)
* class [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray)
* class [`XmpValueBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpvaluebase)
