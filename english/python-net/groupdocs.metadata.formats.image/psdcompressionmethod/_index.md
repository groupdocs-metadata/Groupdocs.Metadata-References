---
title: PsdCompressionMethod class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "PsdCompressionMethod enum — GroupDocs.Metadata for Python via .NET API reference."
type: docs
url: /python-net/groupdocs.metadata.formats.image/psdcompressionmethod/
is_root: false
weight: 270
---


## PsdCompressionMethod class

The PsdCompressionMethod type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| [RAW](/metadata/python-net/groupdocs.metadata.formats.image/psdcompressionmethod/raw/) | No compression. The image data stored as raw bytes in RGBA planar order. That means that first all R data is written, then all G is written, then all B and finally all A data is written. |
| [RLE](/metadata/python-net/groupdocs.metadata.formats.image/psdcompressionmethod/rle/) | RLE compressed. The image data starts with the byte counts for all the scan lines (rows * channels), with each count stored as a two-byte value. The RLE compressed data follows, with each scan line compressed separately. The RLE compression is the same compression algorithm used by the Macintosh ROM routine PackBits and the TIFF standard. |
| [ZIP_WITHOUT_PREDICTION](/metadata/python-net/groupdocs.metadata.formats.image/psdcompressionmethod/zip_without_prediction/) | ZIP without prediction. |
| [ZIP_WITH_PREDICTION](/metadata/python-net/groupdocs.metadata.formats.image/psdcompressionmethod/zip_with_prediction/) | ZIP with prediction. |

### See Also
* module [`groupdocs.metadata.formats.image`](/metadata/python-net/groupdocs.metadata.formats.image/)
