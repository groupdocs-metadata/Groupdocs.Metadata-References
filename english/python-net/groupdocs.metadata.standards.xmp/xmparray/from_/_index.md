---
title: from_ method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "XmpArray.from_ method — GroupDocs.Metadata for Python via .NET."
type: docs
url: /python-net/groupdocs.metadata.standards.xmp/xmparray/from_/
is_root: false
weight: 1010
---


## from_ {#array-type}

```python
def from_(cls, array, type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| array |  |  |
| type | `XmpArrayType` |  |

## from_ {#array-type}

Creates an XmpArray instance from a string array.

```python
def from_(cls, array, type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| array | `list[str]` | The array to create an XmpArray from. |
| type | `XmpArrayType` | The type of the XmpArray. |

**Returns:** XmpArray: An XmpArray containing all the elements from the original array.

### Example

```python
from groupdocs.metadata.standards.xmp import XmpArray, XmpArrayType

arr = XmpArray.from_(["Aspose", "GroupDocs"], XmpArrayType.ORDERED)
```

## from_ {#array-type}

Creates an XmpArray instance from an integer array.

```python
def from_(cls, array, type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| array | `list[int]` | The array to create an XmpArray from. |
| type | `XmpArrayType` | The type of the XmpArray. |

**Returns:** An XmpArray containing all the elements from the original array.

### Example

```python
from groupdocs.metadata.standards.xmp import XmpArray, XmpArrayType

# Create an ordered XMP array from a list of strings
company_array = XmpArray.from_(["Aspose", "GroupDocs"], XmpArrayType.ORDERED)
```

## from_ {#array-type}

Creates an XmpArray instance from a date array.

```python
def from_(cls, array, type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| array | `list[datetime]` | The array to create an XmpArray from. |
| type | `XmpArrayType` | The type of the XmpArray. |

**Returns:** XmpArray: An XmpArray containing all the elements from the original array.

### Example

```python
from groupdocs.metadata.standards.xmp import XmpArray, XmpArrayType

companies = ["Aspose", "GroupDocs"]
xmp_array = XmpArray.from_(companies, XmpArrayType.ORDERED)
```

## from_ {#array-type}

Creates an XmpArray instance from a list.

```python
def from_(cls, array, type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| array | `list[float]` | The list to create an XmpArray from. |
| type | `XmpArrayType` | The type of the XmpArray. |

**Returns:** XmpArray: An XmpArray containing all the elements from the original list.

### Example

```python
from groupdocs.metadata.standards.xmp import XmpArray, XmpArrayType

# Create an ordered XMP array from a list of strings
company_array = XmpArray.from_(["Aspose", "GroupDocs"], XmpArrayType.ORDERED)
```

### See Also
* class [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray/)
