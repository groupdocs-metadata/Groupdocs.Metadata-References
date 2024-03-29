---
title: AsfAudioStreamProperty
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Repräsentiert AudioStreamEigenschaftsmetadaten im ASFMediencontainer.
type: docs
weight: 2230
url: /de/net/groupdocs.metadata.formats.video/asfaudiostreamproperty/
---
## AsfAudioStreamProperty class

Repräsentiert Audio-Stream-Eigenschaftsmetadaten im ASF-Mediencontainer.

```csharp
public class AsfAudioStreamProperty : AsfBaseStreamProperty
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternateBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/alternatebitrate) { get; } | Ruft die Leckrate RAlt in Bits pro Sekunde eines Leaky Buckets ab, der den Datenteil des Streams ohne Überlauf enthält, ohne den gesamten ASF-Datenpaket-Overhead. |
| [AverageBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagebitrate) { get; } | Ruft die durchschnittliche Bitrate ab. |
| [AverageTimePerFrame](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagetimeperframe) { get; } | Ruft die durchschnittliche Zeitdauer jedes Frames ab, gemessen in Einheiten von 100 Nanosekunden. |
| [Bitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/bitrate) { get; } | Ruft die Leckrate R in Bits pro Sekunde eines Leaky Buckets ab, der den Datenteil des Streams ohne Überlauf enthält, ohne den gesamten ASF-Datenpaket-Overhead. |
| [BitsPerSample](../../groupdocs.metadata.formats.video/asfaudiostreamproperty/bitspersample) { get; } | Ruft die Anzahl der Bits pro Sample von monauralen Daten ab. |
| [Channels](../../groupdocs.metadata.formats.video/asfaudiostreamproperty/channels) { get; } | Ruft die Anzahl der Audiokanäle ab. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [EndTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/endtime) { get; } | Ruft die Präsentationszeit des letzten Objekts plus die Wiedergabedauer ab und gibt an, wo dieser digitale Medienstrom im Kontext der Zeitleiste der gesamten ASF-Datei endet. |
| [Flags](../../groupdocs.metadata.formats.video/asfbasestreamproperty/flags) { get; } | Ruft die Flags ab. |
| [FormatTag](../../groupdocs.metadata.formats.video/asfaudiostreamproperty/formattag) { get; } | Ruft die eindeutige ID des Codecs ab, der zum Codieren der Audiodaten verwendet wird. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [Language](../../groupdocs.metadata.formats.video/asfbasestreamproperty/language) { get; } | Ruft die Stream-Sprache ab. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [SamplesPerSecond](../../groupdocs.metadata.formats.video/asfaudiostreamproperty/samplespersecond) { get; } | Ruft einen Wert in Hertz (Zyklen pro Sekunde) ab, der die Abtastrate des Audiostreams darstellt. |
| [StartTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/starttime) { get; } | Ruft die Präsentationszeit des ersten Objekts ab und gibt an, wo dieser digitale Medienstrom innerhalb des Kontexts der Zeitachse der gesamten ASF-Datei beginnt. |
| [StreamNumber](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamnumber) { get; } | Ruft die Nummer dieses Streams ab. |
| [StreamType](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamtype) { get; } | Ruft den Typ dieses Streams ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Bemerkungen

**Erfahren Sie mehr**

* [Arbeiten mit Metadaten in ASF-Dateien](https://docs.groupdocs.com/display/metadatanet/Working+with+Metadata+in+ASF+Files)

### Siehe auch

* class [AsfBaseStreamProperty](../asfbasestreamproperty)
* namensraum [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
