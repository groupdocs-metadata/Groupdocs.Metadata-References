---
title: XmpLangAlt class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 190
url: /python-net/groupdocs.metadata.standards.xmp/xmplangalt/
is_root: false
---

## XmpLangAlt class

Represents XMP Language Alternative. 



An alternative array of simple text items. Language alternatives facilitate the selection of a simple text item
based on a desired language. Each array item shall have an xml:lang qualifier. Each xml:lang value shall be
unique among the items.



**Inheritance:** [`XmpLangAlt`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmplangalt) → 
[`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray) → 
[`XmpValueBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpvaluebase) → 
[`PropertyValue`](/metadata/python-net/groupdocs.metadata.common/propertyvalue)



The XmpLangAlt type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self, default_value)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmplangalt/__init__/#system.string) | Initializes a new instance of the [`XmpLangAlt`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmplangalt) class. |


### Properties
| Property | Description |
| :- | :- |
| [type](/metadata/python-net/groupdocs.metadata.standards.xmp/xmplangalt/type) | Gets the [`MetadataPropertyType`](/metadata/python-net/groupdocs.metadata.common/metadatapropertytype). |
| [raw_value](/metadata/python-net/groupdocs.metadata.standards.xmp/xmplangalt/raw_value) | Gets the raw value. |
| [array_type](/metadata/python-net/groupdocs.metadata.standards.xmp/xmplangalt/array_type) | Gets the type of the XMP array. |
| [languages](/metadata/python-net/groupdocs.metadata.standards.xmp/xmplangalt/languages) | Gets an array of all languages registered in the instance of [`XmpLangAlt`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmplangalt). |


### Methods
| Method | Description |
| :- | :- |
| [`from_address(, array, type)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmplangalt/from_address/#list-groupdocs.metadata.standards.xmp.xmparraytype) | Creates an [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray) instance form a string array. |
| [`from_address(, array, type)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmplangalt/from_address/#list-groupdocs.metadata.standards.xmp.xmparraytype) | Creates an [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray) instance form an integer array. |
| [`from_address(, array, type)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmplangalt/from_address/#list-groupdocs.metadata.standards.xmp.xmparraytype) | Creates an [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray) instance form a date array. |
| [`from_address(, array, type)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmplangalt/from_address/#list-groupdocs.metadata.standards.xmp.xmparraytype) | Creates an [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray) instance form a double array. |
| [`accept_value(self, value_acceptor)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmplangalt/accept_value/#groupdocs.metadata.common.valueacceptor) | Extracts the property value using a custom [`ValueAcceptor`](/metadata/python-net/groupdocs.metadata.common/valueacceptor). |
| [`get_xmp_representation(self)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmplangalt/get_xmp_representation/#) | Converts XMP value to the xml representation. |
| [`contains(self, language)`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmplangalt/contains/#system.string) | Determines whether the [`XmpLangAlt`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmplangalt) contains the specified language. |



### See Also
* module [`groupdocs.metadata.standards.xmp`](..)
* class [`MetadataPropertyType`](/metadata/python-net/groupdocs.metadata.common/metadatapropertytype)
* class [`PropertyValue`](/metadata/python-net/groupdocs.metadata.common/propertyvalue)
* class [`ValueAcceptor`](/metadata/python-net/groupdocs.metadata.common/valueacceptor)
* class [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray)
* class [`XmpLangAlt`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmplangalt)
* class [`XmpValueBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpvaluebase)
