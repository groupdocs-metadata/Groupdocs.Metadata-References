---
title: XmpDate class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents Date in XMP packet."
type: docs
url: /python-net/groupdocs.metadata.standards.xmp/xmpdate/
is_root: false
weight: 150
---


## XmpDate class

Represents Date in XMP packet.

A date-time value is represented using a subset of the formats defined in Date and Time Formats:

- YYYY
- YYYY-MM
- YYYY-MM-DD
- YYYY-MM-DDThh:mmTZD
- YYYY-MM-DDThh:mm:ssTZD
- YYYY-MM-DDThh:mm:ss.sTZD

The XmpDate type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate/__init__/#date_time) | Initializes a new instance of XmpDate. |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate/__init__/#date_string) | Initializes a new instance of XmpDate. |

### Methods
| Method | Description |
| :- | :- |
| [get_xmp_representation](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate/get_xmp_representation/) | Returns the string containing the value in XMP format. |
| [accept_value](/metadata/python-net/groupdocs.metadata.common/propertyvalue/accept_value/) | Extracts the property value using a custom [`ValueAcceptor`](/metadata/python-net/groupdocs.metadata.common/valueacceptor/). (inherited from [`PropertyValue`](/metadata/python-net/groupdocs.metadata.common/propertyvalue/)) |
| [accept_value_value_acceptor](/metadata/python-net/groupdocs.metadata.common/propertyvalue/accept_value_value_acceptor/) |  (inherited from [`PropertyValue`](/metadata/python-net/groupdocs.metadata.common/propertyvalue/)) |
| [to_array](/metadata/python-net/groupdocs.metadata.common/propertyvalue/to_array/) |  (inherited from [`PropertyValue`](/metadata/python-net/groupdocs.metadata.common/propertyvalue/)) |
| [to_class](/metadata/python-net/groupdocs.metadata.common/propertyvalue/to_class/) |  (inherited from [`PropertyValue`](/metadata/python-net/groupdocs.metadata.common/propertyvalue/)) |
| [to_string](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpvaluebase/to_string/) | Returns a string that represents the property value. (inherited from [`XmpValueBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpvaluebase/)) |
| [to_struct](/metadata/python-net/groupdocs.metadata.common/propertyvalue/to_struct/) |  (inherited from [`PropertyValue`](/metadata/python-net/groupdocs.metadata.common/propertyvalue/)) |

### Properties
| Property | Description |
| :- | :- |
| [format](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate/format/) | The format string for the current XMP date value. |
| [value](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate/value/) | The DateTime value of the XMP date. |
| [raw_value](/metadata/python-net/groupdocs.metadata.common/propertyvalue/raw_value/) | The raw value. (inherited from [`PropertyValue`](/metadata/python-net/groupdocs.metadata.common/propertyvalue/)) |
| [type](/metadata/python-net/groupdocs.metadata.common/propertyvalue/type/) | The type of the property. (inherited from [`PropertyValue`](/metadata/python-net/groupdocs.metadata.common/propertyvalue/)) |

### Fields
| Field | Description |
| :- | :- |
| [ISO_8601_FORMAT](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpdate/iso_8601_format/) | The ISO 8601 (roundtrip) format string. |

### See Also
* module [`groupdocs.metadata.standards.xmp`](/metadata/python-net/groupdocs.metadata.standards.xmp/)
