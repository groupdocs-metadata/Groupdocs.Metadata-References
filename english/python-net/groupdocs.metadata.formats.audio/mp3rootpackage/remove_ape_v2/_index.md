---
title: remove_ape_v2 method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Removes the APEv2 audio tag."
type: docs
url: /python-net/groupdocs.metadata.formats.audio/mp3rootpackage/remove_ape_v2/
is_root: false
weight: 1010
---


## remove_ape_v2

Removes the APEv2 audio tag.

This feature is not available in trial mode.

```python
def remove_ape_v2(self):
    ...
```

### Example

```python
from groupdocs.metadata import Metadata, MP3RootPackage, Constants

with Metadata(Constants.MP3WithApe) as metadata:
    root = metadata.get_root_package(MP3RootPackage)
    root.remove_ape_v2()
    metadata.save(Constants.OutputMp3)
```

### See Also
* class [`MP3RootPackage`](/metadata/python-net/groupdocs.metadata.formats.audio/mp3rootpackage/)
