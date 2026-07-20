---
title: Tags class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "The class provides various sets of tags that mark the most important metadata properties."
type: docs
url: /python-net/groupdocs.metadata.tagging/tags/
is_root: false
weight: 100
---


## Tags class

The class provides various sets of tags that mark the most important metadata properties.

These tags enable finding and updating metadata properties across different packages regardless of the metadata standard or file format.

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
        print(f"Property name: {prop.name}, Property value: {prop.value}")
```

### Guides
Task guides that use `Tags`:

* [Find metadata properties](/metadata/python-net/guides/find-metadata-properties/)
* [Set metadata properties](/metadata/python-net/guides/set-metadata-properties/)
* [Remove metadata properties](/metadata/python-net/guides/remove-metadata-properties/)

### See Also
* module [`groupdocs.metadata.tagging`](/metadata/python-net/groupdocs.metadata.tagging/)
