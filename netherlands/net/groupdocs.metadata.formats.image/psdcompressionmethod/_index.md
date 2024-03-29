---
title: PsdCompressionMethod
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Definieert de compressiemethode die wordt gebruikt voor afbeeldingsgegevens.
type: docs
weight: 1890
url: /nl/net/groupdocs.metadata.formats.image/psdcompressionmethod/
---
## PsdCompressionMethod enumeration

Definieert de compressiemethode die wordt gebruikt voor afbeeldingsgegevens.

```csharp
public enum PsdCompressionMethod
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Raw | `0` | Geen compressie. De afbeeldingsgegevens worden opgeslagen als onbewerkte bytes in RGBA-planaire volgorde. Dat betekent dat eerst alle R-gegevens worden geschreven, vervolgens alle G-gegevens, vervolgens alle B-gegevens en ten slotte alle A-gegevens. |
| Rle | `1` | RLE gecomprimeerd. De beeldgegevens beginnen met de bytetellingen voor alle scanlijnen (rijen * kanalen), waarbij elke telling wordt opgeslagen als een waarde van twee bytes. De RLE-gecomprimeerde gegevens volgen, waarbij elke scanregel afzonderlijk wordt gecomprimeerd. De RLE-compressie is hetzelfde compressie-algoritme dat wordt gebruikt door de Macintosh ROM-routine PackBits en de TIFF-standaard. |
| ZipWithoutPrediction | `2` | ZIP zonder voorspelling. |
| ZipWithPrediction | `3` | ZIP met voorspelling. |

### Zie ook

* naamruimte [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
