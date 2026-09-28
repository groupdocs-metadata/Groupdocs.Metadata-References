---
title: __init__ constructor
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Initializes a new IptcDataSet instance."
type: docs
url: /python-net/groupdocs.metadata.standards.iptc/iptcdataset/__init__/
is_root: false
weight: 10
---


## __init__ {#record_number-data_set_number-value}

Initializes a new IptcDataSet instance.

```python
def __init__(self, record_number, data_set_number, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| record_number | `int` | The record number. |
| data_set_number | `int` | The dataSet number. |
| value | `list[int]` | A byte array value. |

### Example

```python
from groupdocs.metadata.standards.iptc import IptcDataSet

# Create a custom IPTC dataset with a byte array value
dataset = IptcDataSet(255, 255, bytes([1, 2, 3]))
```

## __init__ {#record_number-data_set_number-value}

Initializes a new IptcDataSet instance.

```python
def __init__(self, record_number, data_set_number, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| record_number | `int` | The record number. |
| data_set_number | `int` | The dataSet number. |
| value | `str` | A string value. |

### Example

```python
from groupdocs.metadata.standards.iptc import IptcDataSet, IptcRecordType, IptcApplicationRecordDataSet

# Create a known IPTC dataset
dataset = IptcDataSet(
    int(IptcRecordType.APPLICATION_RECORD),
    int(IptcApplicationRecordDataSet.BYLINE_TITLE),
    "test code sample",
)

# Create a custom IPTC dataset with raw bytes
custom_dataset = IptcDataSet(255, 255, b"\x01\x02\x03")
```

## __init__ {#record_number-data_set_number-value}

Initializes a new IptcDataSet instance.

```python
def __init__(self, record_number, data_set_number, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| record_number | `int` | The record number. |
| data_set_number | `int` | The dataSet number. |
| value | `int` | An integer value. |

### Example

```python
from groupdocs.metadata.standards.iptc import IptcDataSet

# Create a dataset with record and dataset numbers and a string value
dataset = IptcDataSet(1, 2, "example value")
```

## __init__ {#record_number-data_set_number-value}

Initializes a new IptcDataSet instance.

```python
def __init__(self, record_number, data_set_number, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| record_number | `int` | The record number. |
| data_set_number | `int` | The dataSet number. |
| value | `datetime` | A date value. |

### Example

```python
from groupdocs.metadata import Metadata
from groupdocs.metadata.standards.iptc import (
    IptcDataSet,
    IptcRecordSet,
    IptcRecordType,
    IptcApplicationRecordDataSet,
)

with Metadata("iptc.psd") as metadata:
    root = metadata.get_root_package()
    if getattr(root, "iptc_package", None) is None:
        root.iptc_package = IptcRecordSet()

    # Add a known property using the DataSet API
    root.iptc_package.set(IptcDataSet(
        int(IptcRecordType.APPLICATION_RECORD),
        int(IptcApplicationRecordDataSet.BYLINE_TITLE),
        "test code sample",
    ))

    # Add a fully custom IPTC DataSet
    root.iptc_package.set(IptcDataSet(255, 255, bytes([1, 2, 3])))

    metadata.save("output.psd")
```

### See Also
* class [`IptcDataSet`](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcdataset/)
