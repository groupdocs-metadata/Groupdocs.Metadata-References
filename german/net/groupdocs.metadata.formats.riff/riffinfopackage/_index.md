---
title: RiffInfoPackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt das Metadatenpaket dar das Eigenschaften enthält die aus dem RIFFINFOChunk extrahiert wurden.
type: docs
weight: 2220
url: /de/net/groupdocs.metadata.formats.riff/riffinfopackage/
---
## RiffInfoPackage class

Stellt das Metadatenpaket dar, das Eigenschaften enthält, die aus dem RIFF-INFO-Chunk extrahiert wurden.

```csharp
public sealed class RiffInfoPackage : CustomPackage
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Artist](../../groupdocs.metadata.formats.riff/riffinfopackage/artist) { get; } | Ruft den Künstler des ursprünglichen Themas der Datei ab. |
| [Comment](../../groupdocs.metadata.formats.riff/riffinfopackage/comment) { get; } | Ruft den Kommentar zur Datei oder den Betreff der Datei ab. |
| [Copyright](../../groupdocs.metadata.formats.riff/riffinfopackage/copyright) { get; } | Ruft die Copyright-Informationen für die Datei ab. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [CreationDate](../../groupdocs.metadata.formats.riff/riffinfopackage/creationdate) { get; } | Ruft das Datum ab, an dem der Betreff der Datei erstellt wurde. |
| [Engineer](../../groupdocs.metadata.formats.riff/riffinfopackage/engineer) { get; } | Ruft den Namen des Ingenieurs ab, der an der Datei gearbeitet hat. |
| [Genre](../../groupdocs.metadata.formats.riff/riffinfopackage/genre) { get; } | Ruft das Genre des Originalwerks ab. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [Keywords](../../groupdocs.metadata.formats.riff/riffinfopackage/keywords) { get; } | Ruft die Schlüsselwörter ab, die sich auf die Datei oder das Thema der Datei beziehen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [Name](../../groupdocs.metadata.formats.riff/riffinfopackage/name) { get; } | Ruft den Titel des Betreffs der Datei ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [Software](../../groupdocs.metadata.formats.riff/riffinfopackage/software) { get; } | Ruft den Namen des Softwarepakets ab, das zum Erstellen der Datei verwendet wurde. |
| [Source](../../groupdocs.metadata.formats.riff/riffinfopackage/source) { get; } | Ruft den Namen der Person oder Organisation ab, die den ursprünglichen Betreff der Datei bereitgestellt hat. |
| [Subject](../../groupdocs.metadata.formats.riff/riffinfopackage/subject) { get; } | Ruft eine Beschreibung des Dateiinhalts ab, z. B. „Luftaufnahme von Seattle.“ |
| [Technician](../../groupdocs.metadata.formats.riff/riffinfopackage/technician) { get; } | Ruft den Techniker ab, der die betreffende Datei digitalisiert hat. |

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

### Siehe auch

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namensraum [GroupDocs.Metadata.Formats.Riff](../../groupdocs.metadata.formats.riff)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
