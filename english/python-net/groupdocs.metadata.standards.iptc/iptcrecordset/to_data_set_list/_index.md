---
title: to_data_set_list method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Creates a list of dataSets from the package."
type: docs
url: /python-net/groupdocs.metadata.standards.iptc/iptcrecordset/to_data_set_list/
is_root: false
weight: 1110
---


## to_data_set_list

Creates a list of dataSets from the package.

```python
def to_data_set_list(self):
    ...
```

**Returns:** list[IptcDataSet]: A list that contains all IPTC dataSets from the package.

### Example

```python
    from groupdocs.metadata import Metadata

    def read_iptc_datasets():
        with Metadata("iptc.psd") as metadata:
            root = metadata.get_root_package()
            iptc = getattr(root, "iptc_package", None)
            if iptc is not None:
                for dataset in iptc.to_data_set_list():
                    print(dataset.record_number)       # record (e.g. 1=envelope, 2=application)
                    print(dataset.data_set_number)     # dataset id within the record
                    print(dataset.alternative_name)    # human‑readable name
                    print(dataset.value.raw_value)     # underlying value

    if __name__ == "__main__":
        read_iptc_datasets()
    ```

### See Also
* class [`IptcRecordSet`](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcrecordset/)
