---
title: language property
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.video/matroskaaudiotrack/language/
is_root: false
weight: 180
---

## language property


Gets the language of the track in the Matroska languages form.
This Element MUST be ignored if the [`MatroskaTrack.language_ietf`](/metadata/python-net/groupdocs.metadata.formats.video/matroskatrack#language_ietf) Element is used in the same TrackEntry.

### Remarks 


Language codes can be either the 3 letters bibliographic ISO-639-2 form (like "fre" for french),
or such a language code followed by a dash and a country code for specialities in languages(like "fre-ca" for Canadian French). 
Country codes are the same as used for internet domains.

### See Also
* module [`groupdocs.metadata.formats.video`](../../)
* class [`MatroskaAudioTrack`](/metadata/python-net/groupdocs.metadata.formats.video/matroskaaudiotrack)
