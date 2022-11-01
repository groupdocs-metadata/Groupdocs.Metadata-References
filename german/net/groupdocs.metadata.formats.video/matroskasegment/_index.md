---
title: MatroskaSegment
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt ein SEGMENTINFOElement dar das allgemeine Informationen über das SEGMENT in einem MatroskaVideo enthält.
type: docs
weight: 2490
url: /de/net/groupdocs.metadata.formats.video/matroskasegment/
---
## MatroskaSegment class

Stellt ein SEGMENTINFO-Element dar, das allgemeine Informationen über das SEGMENT in einem Matroska-Video enthält.

```csharp
public class MatroskaSegment : MatroskaBasePackage
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [DateUtc](../../groupdocs.metadata.formats.video/matroskasegment/dateutc) { get; } | Ruft das Datum und die Uhrzeit ab, zu der das Segment von der Muxing-Anwendung oder -Bibliothek erstellt wurde. |
| [Duration](../../groupdocs.metadata.formats.video/matroskasegment/duration) { get; } | Ruft die Dauer des SEGMENTS ab. Siehe bitte[`TimecodeScale`](./timecodescale) für weitere Informationen. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [MuxingApp](../../groupdocs.metadata.formats.video/matroskasegment/muxingapp) { get; } | Ruft den vollständigen Namen der Anwendung oder Bibliothek ab, gefolgt von der Versionsnummer. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [ScaledDuration](../../groupdocs.metadata.formats.video/matroskasegment/scaledduration) { get; } | Ruft die skalierte Dauer des SEGMENTS ab. |
| [SegmentFilename](../../groupdocs.metadata.formats.video/matroskasegment/segmentfilename) { get; } | Ruft den Dateinamen ab, der diesem Segment entspricht. |
| [SegmentUid](../../groupdocs.metadata.formats.video/matroskasegment/segmentuid) { get; } | Ruft die eindeutige 128-Bit-Nummer ab, die ein SEGMENT identifiziert. Offensichtlich kann eine Datei nur dann von einer anderen Datei referenziert werden, wenn eine SEGMENTUID vorhanden ist, jedoch ist die Wiedergabe ohne diese UID möglich. |
| [TimecodeScale](../../groupdocs.metadata.formats.video/matroskasegment/timecodescale) { get; } | Ruft den Timecode-Skalenwert ab. Jeder skalierte Timecode in einer MATROSKA-Datei wird mit TIMECODESCALE multipliziert, um den Timecode in Nanosekunden zu erhalten. Beachten Sie, dass nicht alle Timecodes skaliert sind! |
| [Title](../../groupdocs.metadata.formats.video/matroskasegment/title) { get; } | Ruft den allgemeinen Namen des Segments ab. |
| [WritingApp](../../groupdocs.metadata.formats.video/matroskasegment/writingapp) { get; } | Ruft den vollständigen Namen der Anwendung ab, gefolgt von der Versionsnummer. |

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

* [Arbeiten mit Metadaten in Matroska-Dateien (MKV).](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### Siehe auch

* class [MatroskaBasePackage](../matroskabasepackage)
* namensraum [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
