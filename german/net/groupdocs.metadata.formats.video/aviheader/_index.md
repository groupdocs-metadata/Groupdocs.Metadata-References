---
title: AviHeader
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Repräsentiert die AVIMAINHEADERStruktur in einem AVIVideo.
type: docs
weight: 2380
url: /de/net/groupdocs.metadata.formats.video/aviheader/
---
## AviHeader class

Repräsentiert die AVIMAINHEADER-Struktur in einem AVI-Video.

```csharp
public sealed class AviHeader : CustomPackage
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [AviHeader](aviheader)() | Initialisiert eine neue Instanz von[`AviHeader`](../aviheader) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AviHeaderFlags](../../groupdocs.metadata.formats.video/aviheader/aviheaderflags) { get; } | Ruft eine bitweise Kombination von null oder mehr der AVI-Flags ab. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [Height](../../groupdocs.metadata.formats.video/aviheader/height) { get; } | Ruft die Höhe der AVI-Datei in Pixel ab. |
| [InitialFrames](../../groupdocs.metadata.formats.video/aviheader/initialframes) { get; } | Ruft den Anfangsframe für Interleaved-Dateien ab.  Nicht verschachtelte Dateien sollten Null angeben. Wenn Sie Interleaved-Dateien erstellen, geben Sie die Anzahl der Frames in der Datei vor dem ersten Frame der AVI-Sequenz in diesem Mitglied an. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [MaxBytesPerSec](../../groupdocs.metadata.formats.video/aviheader/maxbytespersec) { get; } | Ruft die ungefähre maximale Datenrate der Datei ab.  Dieser Wert gibt die Anzahl der Bytes pro Sekunde an, die das System verarbeiten muss, um eine AVI-Sequenz als darzustellen, die von den anderen Parametern angegeben wird, die in den Haupt-Header- und Stream-Header-Blöcken enthalten sind. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [MicroSecPerFrame](../../groupdocs.metadata.formats.video/aviheader/microsecperframe) { get; } | Ruft die Anzahl der Mikrosekunden zwischen Frames ab. Dieser Wert gibt das Gesamttiming für die Datei an. |
| [PaddingGranularity](../../groupdocs.metadata.formats.video/aviheader/paddinggranularity) { get; } | Ruft die Ausrichtung für Daten in Byte ab. Füllen Sie die Daten mit Vielfachen dieses Werts auf. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [Streams](../../groupdocs.metadata.formats.video/aviheader/streams) { get; } | Ruft die Anzahl der Streams in der Datei ab. Beispielsweise hat eine Datei mit Audio und Video zwei Streams. |
| [SuggestedBufferSize](../../groupdocs.metadata.formats.video/aviheader/suggestedbuffersize) { get; } | Ruft die vorgeschlagene Puffergröße zum Lesen der Datei ab.  Im Allgemeinen sollte diese Größe groß genug sein, um den größten Teil der Datei aufzunehmen. Wenn der Wert auf Null gesetzt oder zu klein ist, muss die Wiedergabesoftware während der Wiedergabe Speicher neu zuweisen, was die Leistung verringert. Bei einer verschachtelten Datei sollte die Puffergröße groß genug sein, um einen ganzen Datensatz zu lesen, und nicht nur einen Teil. |
| [TotalFrames](../../groupdocs.metadata.formats.video/aviheader/totalframes) { get; } | Ruft die Gesamtzahl der Datenframes in der Datei ab. |
| [Width](../../groupdocs.metadata.formats.video/aviheader/width) { get; } | Ermittelt die Breite der AVI-Datei in Pixel. |

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

* [Arbeiten mit Metadaten in AVI-Dateien](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+AVI+files)

### Siehe auch

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namensraum [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
