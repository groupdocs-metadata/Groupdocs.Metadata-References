---
title: flags property
second_title: GroupDocs.Metadata for Python via .NET API References
description: "The ZIP entry flags."
type: docs
url: /python-net/groupdocs.metadata.formats.archive/zipfile/flags/
is_root: false
weight: 2030
---


## flags property

The ZIP entry flags.

- Bit 00: encrypted file.
- Bit 01: compression option.
- Bit 02: compression option.
- Bit 03: data descriptor.
- Bit 04: enhanced deflation.
- Bit 05: compressed patched data.
- Bit 06: strong encryption.
- Bits 07‑10: unused.
- Bit 11: language encoding.
- Bit 12: reserved.
- Bit 13: mask header values.
- Bits 14‑15: reserved.

### Definition:
```python
@property
def flags(self):
    ...
```

### See Also
* class [`ZipFile`](/metadata/python-net/groupdocs.metadata.formats.archive/zipfile/)
