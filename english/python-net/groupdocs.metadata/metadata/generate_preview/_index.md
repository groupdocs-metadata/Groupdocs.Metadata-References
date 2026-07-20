---
title: generate_preview method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Creates preview images for specified pages."
type: docs
url: /python-net/groupdocs.metadata/metadata/generate_preview/
is_root: false
weight: 1080
---


## generate_preview {#preview_options}

Creates preview images for specified pages.

Learn more:
- [Generate document preview](https://docs.groupdocs.com/display/metadatanet/Generate+document+preview)

```python
def generate_preview(self, preview_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| preview_options | `PreviewOptions` | A set of options for preview generation. |

**Returns:** None.

### Example

```python
from groupdocs.metadata import Metadata, PreviewOptions, Constants

def create_preview():
    with Metadata(Constants.InputDocx) as metadata:
        preview_options = PreviewOptions(
            page_number=lambda page_number: open(
                f"{Constants.OutputPath}\\result_{page_number}.png", "wb"
            )
        )
        preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
        preview_options.page_numbers = [1]

        metadata.generate_preview(preview_options)
```

### See Also
* class [`Metadata`](/metadata/python-net/groupdocs.metadata/metadata/)
