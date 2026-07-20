---
title: __init__ constructor
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Initializes a PropertyValue with an integer value."
type: docs
url: /python-net/groupdocs.metadata.common/propertyvalue/__init__/
is_root: false
weight: 10
---


## __init__ {#value}

Initializes a PropertyValue with an integer value.

```python
def __init__(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | `int` | An integer value. |

### Example

```python
from datetime import datetime
from groupdocs.metadata.common import PropertyValue

# Integer value
int_prop = PropertyValue(123)

# DateTime value (also supported)
date_prop = PropertyValue(datetime.now())
```

## __init__ {#value}

Initializes a PropertyValue with a long value.

```python
def __init__(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | `int` | A long integer value. |

## __init__ {#value}

Initializes a new PropertyValue with a boolean value.

```python
def __init__(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | `bool` | A boolean value. |

## __init__ {#value}

Initializes a PropertyValue with a double value.

```python
def __init__(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | `float` | A double value. |

## __init__ {#value}

Initializes a PropertyValue with a string value.

```python
def __init__(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | `str` | A str value. |

## __init__ {#value}

Initializes a new PropertyValue with the given value.

```python
def __init__(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | `Any` | An object value. |

### Example

```python
from datetime import datetime
from groupdocs.metadata.common import PropertyValue

property_value = PropertyValue(datetime.now())
```

## __init__ {#value}

Initializes a new PropertyValue with a datetime value.

```python
def __init__(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | `datetime` | A `datetime` value to store. |

### Example

```python
from datetime import datetime
from groupdocs.metadata.common import PropertyValue

pv = PropertyValue(datetime.now())
```

## __init__ {#value}

Initializes a new PropertyValue instance with a datetime.timedelta value.

```python
def __init__(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | `timedelta` | A datetime.timedelta value. |

## __init__ {#values}

Initializes a PropertyValue with a list of strings.

```python
def __init__(self, values):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| values | `list[str]` | A string array. |

## __init__ {#values}

Initializes a PropertyValue with a byte array.

```python
def __init__(self, values):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| values | `list[int]` | A byte array. |

## __init__ {#values}

Initializes a PropertyValue with an array of double values.

```python
def __init__(self, values):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| values | `list[float]` | A list of float values. |

## __init__ {#values}

Initializes a PropertyValue with an array of integer values.

```python
def __init__(self, values):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| values | `list[int]` | An array of integer values. |

## __init__ {#values}

Initializes a PropertyValue with an array of long values.

```python
def __init__(self, values):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| values | `list[int]` | An array of long values. |

## __init__ {#values}

Initializes a PropertyValue with an array of unsigned 16‑bit integer values.

```python
def __init__(self, values):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| values | `list[System.UInt16]` | An array of ushort values. |

### See Also
* class [`PropertyValue`](/metadata/python-net/groupdocs.metadata.common/propertyvalue/)
