---
title: OpenTypeLicensingRights class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "OpenTypeLicensingRights enum — GroupDocs.Metadata for Python via .NET API reference."
type: docs
url: /python-net/groupdocs.metadata.formats.font/opentypelicensingrights/
is_root: false
weight: 70
---


## OpenTypeLicensingRights class

The OpenTypeLicensingRights type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| [NONE](/metadata/python-net/groupdocs.metadata.formats.font/opentypelicensingrights/none/) | The undefined licensing rights. |
| [INSTALLABLE_EMBEDDING](/metadata/python-net/groupdocs.metadata.formats.font/opentypelicensingrights/installable_embedding/) | Installable embedding. The font may be embedded, and may be permanently installed for use on a remote systems, or for use by other users. |
| [RESTRICTED_LICENSE_EMBEDDING](/metadata/python-net/groupdocs.metadata.formats.font/opentypelicensingrights/restricted_license_embedding/) | Restricted License embedding. The font must not be modified, embedded or exchanged in any manner without first obtaining explicit permission of the legal owner. |
| [PREVIEW_AND_PRINT_EMBEDDING](/metadata/python-net/groupdocs.metadata.formats.font/opentypelicensingrights/preview_and_print_embedding/) | Preview and Print embedding. The font may be embedded, and may be temporarily loaded on other systems for purposes of viewing or printing the document. Documents containing Preview &amp; Print fonts must be opened “read-only”; no edits can be applied to the document. |
| [EDITABLE_EMBEDDING](/metadata/python-net/groupdocs.metadata.formats.font/opentypelicensingrights/editable_embedding/) | Editable embedding. The font may be embedded, and may be temporarily loaded on other systems. As with Preview and Print embedding, documents containing Editable fonts may be opened for reading. In addition, editing is permitted, including ability to format new text using the embedded font, and changes may be saved. |
| [USAGE_PERMISSIONS_MASK](/metadata/python-net/groupdocs.metadata.formats.font/opentypelicensingrights/usage_permissions_mask/) | Usage permissions mask. |
| [NO_SUBSETTING](/metadata/python-net/groupdocs.metadata.formats.font/opentypelicensingrights/no_subsetting/) | No subsetting. When this bit is set, the font may not be subsetted prior to embedding. Other embedding restrictions specified in bits 0 to 3 and bit 9 also apply. |
| [BITMAP_EMBEDDING_ONLY](/metadata/python-net/groupdocs.metadata.formats.font/opentypelicensingrights/bitmap_embedding_only/) | Bitmap embedding only. When this bit is set, only bitmaps contained in the font may be embedded. No outline data may be embedded. If there are no bitmaps available in the font, then the font is considered unembeddable and the embedding services will fail. Other embedding restrictions specified in bits 0-3 and 8 also apply. |

### See Also
* module [`groupdocs.metadata.formats.font`](/metadata/python-net/groupdocs.metadata.formats.font/)
