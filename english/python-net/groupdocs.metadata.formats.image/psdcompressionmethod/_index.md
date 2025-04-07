---
title: PsdCompressionMethod enumeration
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.image/psdcompressionmethod/
is_root: false
weight: 570
---

## PsdCompressionMethod enumeration

Defines the compression method used for image data.



The PsdCompressionMethod type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| RAW | No compression. The image data stored as raw bytes in RGBA planar order.<br/>That means that first all R data is written, then all G is written, then all B and finally all A data is written. |
| RLE | RLE compressed. The image data starts with the byte counts for all the scan lines (rows * channels), with each<br/>count stored as a two-byte value. The RLE compressed data follows, with each scan line compressed separately.<br/>The RLE compression is the same compression algorithm used by the Macintosh ROM routine PackBits and the TIFF standard. |
| ZIP_WITHOUT_PREDICTION | ZIP without prediction. |
| ZIP_WITH_PREDICTION | ZIP with prediction. |



### See Also
* module [`groupdocs.metadata.formats.image`](..)
