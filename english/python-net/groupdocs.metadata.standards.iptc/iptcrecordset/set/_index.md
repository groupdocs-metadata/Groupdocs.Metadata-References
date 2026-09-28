---
title: set method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Adds or updates the specified dataset in the appropriate record."
type: docs
url: /python-net/groupdocs.metadata.standards.iptc/iptcrecordset/set/
is_root: false
weight: 1090
---


## set {#data_set}

Adds or updates the specified data_set in the appropriate record.

```python
def set(self, data_set):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| data_set | `IptcDataSet` | The IPTC data_set to add/update. |

### Example

```python
from groupdocs.metadata import Metadata
from groupdocs.metadata.standards.iptc import (
    IptcApplicationRecordDataSet,
    IptcDataSet,
    IptcRecordSet,
    IptcRecordType,
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
* class [`IptcRecordSet`](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/)
