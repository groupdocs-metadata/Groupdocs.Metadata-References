---
title: XmpTrailerPI
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt XMPTrailerVerarbeitungsanweisung dar.
type: docs
weight: 3610
url: /de/net/groupdocs.metadata.standards.xmp/xmptrailerpi/
---
## XmpTrailerPI class

Stellt XMP-Trailer-Verarbeitungsanweisung dar.

```csharp
public sealed class XmpTrailerPI : IXmpType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [XmpTrailerPI](xmptrailerpi#constructor)() | Initialisiert eine neue Instanz von[`XmpTrailerPI`](../xmptrailerpi) Klasse. |
| [XmpTrailerPI](xmptrailerpi#constructor_1)(bool) | Initialisiert eine neue Instanz von[`XmpTrailerPI`](../xmptrailerpi) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsWritable](../../groupdocs.metadata.standards.xmp/xmptrailerpi/iswritable) { get; } | Gibt an, ob das Formular direkt geändert werden kann. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmptrailerpi/getxmprepresentation)() | Konvertiert den XMP-Wert in die XML-Darstellung. |

### Bemerkungen

Der Teil end="w" oder end="r" wird von Paketscanning-Prozessoren verwendet, um festzustellen, ob das XMP direkt geändert werden kann.

### Beispiele

Erlaubte Formen des Anhängers PI:

### Siehe auch

* interface [IXmpType](../ixmptype)
* namensraum [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->