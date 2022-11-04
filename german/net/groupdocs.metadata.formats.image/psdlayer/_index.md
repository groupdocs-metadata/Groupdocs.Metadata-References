---
title: PsdLayer
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt eine Ebene in einer PSDDatei dar.
type: docs
weight: 1900
url: /de/net/groupdocs.metadata.formats.image/psdlayer/
---
## PsdLayer class

Stellt eine Ebene in einer PSD-Datei dar.

```csharp
public sealed class PsdLayer : CustomPackage
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BitsPerPixel](../../groupdocs.metadata.formats.image/psdlayer/bitsperpixel) { get; } | Ruft den Bit-pro-Pixel-Wert ab. |
| [Bottom](../../groupdocs.metadata.formats.image/psdlayer/bottom) { get; } | Ruft die Position der untersten Ebene ab. |
| [ChannelCount](../../groupdocs.metadata.formats.image/psdlayer/channelcount) { get; } | Ruft die Anzahl der Kanäle ab. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [Flags](../../groupdocs.metadata.formats.image/psdlayer/flags) { get; } | Ruft die Layer-Flags ab. |
| [Height](../../groupdocs.metadata.formats.image/psdlayer/height) { get; } | Ruft die Höhe ab. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [Left](../../groupdocs.metadata.formats.image/psdlayer/left) { get; } | Ruft die Position der linken Ebene ab. |
| [Length](../../groupdocs.metadata.formats.image/psdlayer/length) { get; } | Ruft die Gesamtschichtlänge in Bytes ab. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [Name](../../groupdocs.metadata.formats.image/psdlayer/name) { get; } | Ruft den Ebenennamen ab. |
| [Opacity](../../groupdocs.metadata.formats.image/psdlayer/opacity) { get; } | Ruft die Deckkraft der Ebene ab. 0 = transparent, 255 = undurchsichtig. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [Right](../../groupdocs.metadata.formats.image/psdlayer/right) { get; } | Ruft die richtige Ebenenposition ab. |
| [Top](../../groupdocs.metadata.formats.image/psdlayer/top) { get; } | Ruft die Position der obersten Ebene ab. |
| [Width](../../groupdocs.metadata.formats.image/psdlayer/width) { get; } | Ruft die Breite ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Bemerkungen

**Mehr erfahren**

* [Arbeiten mit Metadaten in PSD-Bildern](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PSD+images)

### Siehe auch

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namensraum [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
