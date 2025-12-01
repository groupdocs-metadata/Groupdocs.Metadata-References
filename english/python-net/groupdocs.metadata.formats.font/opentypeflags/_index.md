---
title: OpenTypeFlags enumeration
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 100
url: /python-net/groupdocs.metadata.formats.font/opentypeflags/
is_root: false
---

## OpenTypeFlags enumeration

Represents OpenType font header flags.



The OpenTypeFlags type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| NONE | Undefined, no flags. |
| BASELINE_AT_Y0 | Baseline for font at y=0. |
| LEFT_SIDEBEARING_AT_X0 | Left sidebearing point at x=0 (relevant only for TrueType rasterizers). |
| DEPEND_ON_POINT_SIZE | Instructions may depend on point size. |
| FORCE_TO_INTEGER | Force ppem to integer values for all internal scaler math; may use fractional ppem sizes if this bit is clear. |
| ALTER_ADVANCE_WIDTH | Instructions may alter advance width (the advance widths might not scale linearly). |
| LOSSLESS | Font data is “lossless” as a result of having been subjected to optimizing transformation and/or compression. |
| CONVERTED | Font converted (produce compatible metrics). |
| OPTIMIZED | Font optimized for ClearType™. |
| RESORT | Last Resort font. |



### See Also
* module [`groupdocs.metadata.formats.font`](..)
