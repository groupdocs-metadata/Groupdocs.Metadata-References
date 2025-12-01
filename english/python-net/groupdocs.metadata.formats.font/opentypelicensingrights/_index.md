---
title: OpenTypeLicensingRights enumeration
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 120
url: /python-net/groupdocs.metadata.formats.font/opentypelicensingrights/
is_root: false
---

## OpenTypeLicensingRights enumeration

Indicates font embedding licensing rights for the font.



The OpenTypeLicensingRights type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| NONE | The undefined licensing rights. |
| USAGE_PERMISSIONS_MASK | Usage permissions mask. |
| INSTALLABLE_EMBEDDING | Installable embedding.<br/>The font may be embedded, and may be permanently installed for use on a remote systems, or for use by other users. |
| RESTRICTED_LICENSE_EMBEDDING | Restricted License embedding.<br/>The font must not be modified, embedded or exchanged in any manner without first obtaining explicit permission of the legal owner. |
| PREVIEW_AND_PRINT_EMBEDDING | Preview and Print embedding.<br/>The font may be embedded, and may be temporarily loaded on other systems for purposes of viewing or printing the document.<br/>Documents containing Preview & Print fonts must be opened “read-only”; no edits can be applied to the document. |
| EDITABLE_EMBEDDING | Editable embedding.<br/>The font may be embedded, and may be temporarily loaded on other systems. <br/>As with Preview and Print embedding, documents containing Editable fonts may be opened for reading.<br/>In addition, editing is permitted, including ability to format new text using the embedded font, and changes may be saved. |
| NO_SUBSETTING | No subsetting.<br/>When this bit is set, the font may not be subsetted prior to embedding. Other embedding restrictions specified in bits 0 to 3 and bit 9 also apply. |
| BITMAP_EMBEDDING_ONLY | Bitmap embedding only.<br/>When this bit is set, only bitmaps contained in the font may be embedded. No outline data may be embedded. <br/>If there are no bitmaps available in the font, then the font is considered unembeddable and the embedding services will fail. <br/>Other embedding restrictions specified in bits 0-3 and 8 also apply. |



### See Also
* module [`groupdocs.metadata.formats.font`](..)
