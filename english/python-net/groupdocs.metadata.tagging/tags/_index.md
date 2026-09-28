---
title: Tags class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Provides various sets of tags that mark the most important metadata properties, enabling discovery and update across different packages, standards, and file formats."
type: docs
url: /python-net/groupdocs.metadata.tagging/tags/
is_root: false
weight: 100
---


## Tags class

Provides various sets of tags that mark the most important metadata properties, enabling discovery and update across different packages, standards, and file formats.

The Tags type exposes the following members:

### Example

```python
from groupdocs.metadata import Metadata
from groupdocs.metadata.tagging import Tags

with Metadata("input.pptx") as metadata:
    # Find properties tagged as the last editor or modified date/time
    props = metadata.find_properties(
        lambda p: Tags.person.editor in list(p.tags) or
                  Tags.time.modified in list(p.tags)
    )
    for prop in props:
        print(f"{prop.name}: {prop.value}")
```

### Guides
Task guides that use `Tags`:

* [Find metadata properties](/metadata/python-net/guides/find-metadata-properties/)
* [Set metadata properties](/metadata/python-net/guides/set-metadata-properties/)
* [Remove metadata properties](/metadata/python-net/guides/remove-metadata-properties/)

### See Also
* module [`groupdocs.metadata.tagging`](/metadata/python-net/groupdocs.metadata.tagging/)
