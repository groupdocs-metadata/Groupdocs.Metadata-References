---
title: LoadOptions class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Allows a developer to specify additional options (such as a password) when loading a file."
type: docs
url: /python-net/groupdocs.metadata.options/loadoptions/
is_root: false
weight: 20
---


## LoadOptions class

Allows a developer to specify additional options (such as a password) when loading a file.

Learn more

- [Load from a local disk](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
- [Load from a stream](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
- [Load a file of a specific format](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
- [Load a password-protected document](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

The LoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.options/loadoptions/__init__/) | Initializes a new instance of the [`LoadOptions`](/metadata/python-net/groupdocs.metadata.options/loadoptions/) class. |
| [__init__](/metadata/python-net/groupdocs.metadata.options/loadoptions/__init__/#file_format) | Initializes a new instance of the [`LoadOptions`](/metadata/python-net/groupdocs.metadata.options/loadoptions/) class. |

### Properties
| Property | Description |
| :- | :- |
| [file_format](/metadata/python-net/groupdocs.metadata.options/loadoptions/file_format/) | The exact type of the file that is to be loaded. |
| [password](/metadata/python-net/groupdocs.metadata.options/loadoptions/password/) | The password for opening an encrypted document. |

### Example

```python
from groupdocs.metadata import Metadata
from groupdocs.metadata.options import LoadOptions

def load_password_protected_document():
    # Specify the password
    load_options = LoadOptions()
    load_options.password = "123"

    with Metadata("protected.docx", load_options) as metadata:
        print(f"Opened protected {metadata.file_format} document")
```

```python
from groupdocs.metadata import Metadata
from groupdocs.metadata.common import FileFormat
from groupdocs.metadata.options import LoadOptions

def loading_file_of_specific_format():
    load_options = LoadOptions(FileFormat.SPREADSHEET)

    with Metadata("input.xlsx", load_options) as metadata:
        root = metadata.get_root_package()
        print(f"Author: {root.document_properties.author}")
```

### See Also
* module [`groupdocs.metadata.options`](/metadata/python-net/groupdocs.metadata.options/)
