---
title: XmpTrailerPI
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar XMPtrailerbearbetningsinstruktion.
type: docs
weight: 3610
url: /sv/net/groupdocs.metadata.standards.xmp/xmptrailerpi/
---
## XmpTrailerPI class

Representerar XMP-trailerbearbetningsinstruktion.

```csharp
public sealed class XmpTrailerPI : IXmpType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [XmpTrailerPI](xmptrailerpi#constructor)() | Initierar en ny instans av[`XmpTrailerPI`](../xmptrailerpi) class. |
| [XmpTrailerPI](xmptrailerpi#constructor_1)(bool) | Initierar en ny instans av[`XmpTrailerPI`](../xmptrailerpi) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [IsWritable](../../groupdocs.metadata.standards.xmp/xmptrailerpi/iswritable) { get; } | Indikerar om formuläret kan ändras på plats. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmptrailerpi/getxmprepresentation)() | Konverterar XMP-värdet till xml-representationen. |

### Anmärkningar

End="w" eller end="r"-delen ska användas av paketavsökningsprocessorer för att avgöra om XMP kan modifieras på plats.

### Exempel

Tillåtna former av trailer PI:

### Se även

* interface [IXmpType](../ixmptype)
* namnutrymme [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->