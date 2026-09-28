---
title: update_document_statistics method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Recalculates count of pages, paragraphs, words, lines, characters in the document and updates appropriate metadata packages."
type: docs
url: /python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/update_document_statistics/
is_root: false
weight: 1010
---


## update_document_statistics

Recalculates count of pages, paragraphs, words, lines, characters in the document and updates appropriate metadata packages.

Learn more

- Working with metadata in WordProcessing documents: https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents

```python
def update_document_statistics(self):
    ...
```

### Example

```python
from groupdocs.metadata import Metadata, WordProcessingRootPackage

with Metadata(Constants.InputDoc) as metadata:
    root = metadata.get_root_package(WordProcessingRootPackage)
    root.update_document_statistics()
    metadata.save(Constants.OutputDoc)
```

### See Also
* class [`WordProcessingRootPackage`](/metadata/python-net/groupdocs.metadata.formats.document/wordprocessingrootpackage/)
