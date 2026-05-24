---
title: Metered class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata/metered/
is_root: false
weight: 70
---


## Metered class

Manages metered (pay-per-use) licensing.

Metered licenses bill on actual consumption (typically pages or
documents processed). Set the public/private key pair once at
application startup; the wrapper reports usage back to the GroupDocs
license server in the background.

The Metered type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [get_consumption_credit](/metadata/python-net/groupdocs.metadata/metered/get_consumption_credit/) | Return the remaining metered credit for the current key. |
| [get_consumption_quantity](/metadata/python-net/groupdocs.metadata/metered/get_consumption_quantity/) | Return the total metered quantity consumed so far. |
| [set_metered_key](/metadata/python-net/groupdocs.metadata/metered/set_metered_key/#public_key-private_key) | Activate metered billing with the given public/private key pair. |

### See Also
* module [`groupdocs.metadata`](/metadata/python-net/groupdocs.metadata/)
