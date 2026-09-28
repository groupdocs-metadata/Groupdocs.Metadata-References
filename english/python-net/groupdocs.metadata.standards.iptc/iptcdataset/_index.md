---
title: IptcDataSet class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents an IPTC DataSet (metadata property)."
type: docs
url: /python-net/groupdocs.metadata.standards.iptc/iptcdataset/
is_root: false
weight: 40
---


## IptcDataSet class

Represents an IPTC DataSet (metadata property).

Learn more:
- Working with IPTC IIM metadata: https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata

The IptcDataSet type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcdataset/__init__/#record_number-data_set_number-value) | Initializes a new IptcDataSet instance. |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcdataset/__init__/#record_number-data_set_number-value) | Initializes a new IptcDataSet instance. |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcdataset/__init__/#record_number-data_set_number-value) | Initializes a new IptcDataSet instance. |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcdataset/__init__/#record_number-data_set_number-value) | Initializes a new IptcDataSet instance. |

### Properties
| Property | Description |
| :- | :- |
| [alternative_name](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcdataset/alternative_name/) | The alternative name of the dataSet. |
| [data_set_number](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcdataset/data_set_number/) | The data set number. |
| [record_number](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcdataset/record_number/) | The record number. |
| [descriptor](/metadata/python-net/groupdocs.metadata.common/metadataproperty/descriptor/) | The descriptor associated with the metadata property. (inherited from [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty/)) |
| [interpreted_value](/metadata/python-net/groupdocs.metadata.common/metadataproperty/interpreted_value/) | The interpreted property value, if available. (inherited from [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty/)) |
| [name](/metadata/python-net/groupdocs.metadata.common/metadataproperty/name/) | The property name. (inherited from [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty/)) |
| [tags](/metadata/python-net/groupdocs.metadata.common/metadataproperty/tags/) | The collection of tags associated with the property. (inherited from [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty/)) |
| [value](/metadata/python-net/groupdocs.metadata.common/metadataproperty/value/) | The property value. (inherited from [`MetadataProperty`](/metadata/python-net/groupdocs.metadata.common/metadataproperty/)) |

### Example

```python
from groupdocs.metadata import Metadata
from groupdocs.metadata.standards.iptc import (
    IptcApplicationRecordDataSet,
    IptcDataSet,
    IptcRecordSet,
    IptcRecordType,
)

def set_custom_iptc_dataset():
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
* module [`groupdocs.metadata.standards.iptc`](/metadata/python-net/groupdocs.metadata.standards.iptc/)
