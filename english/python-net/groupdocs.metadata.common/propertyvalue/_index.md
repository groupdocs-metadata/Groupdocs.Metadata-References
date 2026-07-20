---
title: PropertyValue class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "The property value."
type: docs
url: /python-net/groupdocs.metadata.common/propertyvalue/
is_root: false
weight: 190
---


## PropertyValue class

The property value.

The PropertyValue type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.common/propertyvalue/__init__/#value) | Initializes a PropertyValue with an integer value. |
| [__init__](/metadata/python-net/groupdocs.metadata.common/propertyvalue/__init__/#value) | Initializes a PropertyValue with a long value. |
| [__init__](/metadata/python-net/groupdocs.metadata.common/propertyvalue/__init__/#value) | Initializes a new PropertyValue with a boolean value. |
| [__init__](/metadata/python-net/groupdocs.metadata.common/propertyvalue/__init__/#value) | Initializes a PropertyValue with a double value. |
| [__init__](/metadata/python-net/groupdocs.metadata.common/propertyvalue/__init__/#value) | Initializes a PropertyValue with a string value. |
| [__init__](/metadata/python-net/groupdocs.metadata.common/propertyvalue/__init__/#value) | Initializes a new PropertyValue with the given value. |
| [__init__](/metadata/python-net/groupdocs.metadata.common/propertyvalue/__init__/#value) | Initializes a new PropertyValue with a datetime value. |
| [__init__](/metadata/python-net/groupdocs.metadata.common/propertyvalue/__init__/#value) | Initializes a new PropertyValue instance with a datetime.timedelta value. |
| [__init__](/metadata/python-net/groupdocs.metadata.common/propertyvalue/__init__/#values) | Initializes a PropertyValue with a list of strings. |
| [__init__](/metadata/python-net/groupdocs.metadata.common/propertyvalue/__init__/#values) | Initializes a PropertyValue with a byte array. |
| [__init__](/metadata/python-net/groupdocs.metadata.common/propertyvalue/__init__/#values) | Initializes a PropertyValue with an array of double values. |
| [__init__](/metadata/python-net/groupdocs.metadata.common/propertyvalue/__init__/#values) | Initializes a PropertyValue with an array of integer values. |
| [__init__](/metadata/python-net/groupdocs.metadata.common/propertyvalue/__init__/#values) | Initializes a PropertyValue with an array of long values. |
| [__init__](/metadata/python-net/groupdocs.metadata.common/propertyvalue/__init__/#values) | Initializes a PropertyValue with an array of unsigned 16‑bit integer values. |

### Methods
| Method | Description |
| :- | :- |
| [accept_value](/metadata/python-net/groupdocs.metadata.common/propertyvalue/accept_value/#value_acceptor) | Extracts the property value using a custom [`ValueAcceptor`](/metadata/python-net/groupdocs.metadata.common/valueacceptor/). |
| [accept_value_value_acceptor](/metadata/python-net/groupdocs.metadata.common/propertyvalue/accept_value_value_acceptor/) |  |
| [to_array](/metadata/python-net/groupdocs.metadata.common/propertyvalue/to_array/) |  |
| [to_class](/metadata/python-net/groupdocs.metadata.common/propertyvalue/to_class/) |  |
| [to_string](/metadata/python-net/groupdocs.metadata.common/propertyvalue/to_string/) | Returns a string that represents the property value. |
| [to_struct](/metadata/python-net/groupdocs.metadata.common/propertyvalue/to_struct/) |  |
| [to_struct](/metadata/python-net/groupdocs.metadata.common/propertyvalue/to_struct/#default) |  |

### Properties
| Property | Description |
| :- | :- |
| [raw_value](/metadata/python-net/groupdocs.metadata.common/propertyvalue/raw_value/) | The raw value. |
| [type](/metadata/python-net/groupdocs.metadata.common/propertyvalue/type/) | The type of the property, represented by `MetadataPropertyType`. |

### Example

```python
from datetime import datetime
from groupdocs.metadata.common import PropertyValue

# Create a PropertyValue from a datetime object
value = PropertyValue(datetime.now())
print(value)
```

### Guides
Task guides that use `PropertyValue`:

* [Set metadata properties](/metadata/python-net/guides/set-metadata-properties/)

### See Also
* module [`groupdocs.metadata.common`](/metadata/python-net/groupdocs.metadata.common/)
