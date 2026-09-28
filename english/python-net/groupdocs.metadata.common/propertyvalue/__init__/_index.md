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
int_prop = PropertyValue(42)

# The same constructor can also accept other types, e.g., a datetime
date_prop = PropertyValue(datetime.now())
```

## __init__ {#value}

Initializes a new PropertyValue with a long integer value.

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

Initializes a PropertyValue with a double (float) value.

```python
def __init__(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | `float` | A float value. |

## __init__ {#value}

Initializes a new PropertyValue with a string value.

```python
def __init__(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | `str` | A string value. |

### Example

```python
from datetime import datetime
from groupdocs.metadata.common import PropertyValue

property_value = PropertyValue(datetime.now())
```

## __init__ {#value}

Initializes a new PropertyValue with the given value.

```python
def __init__(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | `Any` | The value to store. |

### Example

```python
    from datetime import datetime
    from groupdocs.metadata.common import PropertyValue

    # Create a PropertyValue containing the current date and time
    prop_val = PropertyValue(datetime.now())
    ```

## __init__ {#value}

Initializes a PropertyValue with a datetime value.

```python
def __init__(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | `datetime` | A datetime value. |

### Example

```python
from datetime import datetime
from groupdocs.metadata.common import PropertyValue

prop_val = PropertyValue(datetime.now())
```

## __init__ {#value}

Initializes a new PropertyValue instance with a `timedelta` value.

```python
def __init__(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | `timedelta` | A `timedelta` value. |

## __init__ {#values}

Initializes a new PropertyValue with a list of strings.

```python
def __init__(self, values):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| values | `list[str]` | A list of strings. |

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

Initializes a new PropertyValue with an array of double values.

```python
def __init__(self, values):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| values | `list[float]` | A list of float values. |

## __init__ {#values}

Initializes a new PropertyValue with an array of integer values.

```python
def __init__(self, values):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| values | `list[int]` | An array of integer values. |

## __init__ {#values}

Initializes a new PropertyValue with an array of long values.

```python
def __init__(self, values):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| values | `list[int]` | An array of long values. |

## __init__ {#values}

Initializes a new PropertyValue instance with an array of unsigned 16‑bit integer values.

```python
def __init__(self, values):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| values | `list[System.UInt16]` | An array of unsigned 16‑bit integer values. |

### See Also
* class [`PropertyValue`](/metadata/python-net/groupdocs.metadata.common/propertyvalue/)
