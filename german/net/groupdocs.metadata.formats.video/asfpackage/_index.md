---
title: AsfPackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt native Metadaten des ASFMediencontainers dar.
type: docs
weight: 2340
url: /de/net/groupdocs.metadata.formats.video/asfpackage/
---
## AsfPackage class

Stellt native Metadaten des ASF-Mediencontainers dar.

```csharp
public class AsfPackage : CustomPackage
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CodecInformation](../../groupdocs.metadata.formats.video/asfpackage/codecinformation) { get; } | Ruft die Codec-Info-Einträge ab. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [CreationDate](../../groupdocs.metadata.formats.video/asfpackage/creationdate) { get; } | Ruft das Datum und die Uhrzeit der ursprünglichen Erstellung der Datei ab. |
| [FileID](../../groupdocs.metadata.formats.video/asfpackage/fileid) { get; } | Ruft die eindeutige Kennung für diese Datei ab. |
| [Flags](../../groupdocs.metadata.formats.video/asfpackage/flags) { get; } | Ruft die Header-Flags ab. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [MetadataDescriptors](../../groupdocs.metadata.formats.video/asfpackage/metadatadescriptors) { get; } | Ruft die Metadatendeskriptoren ab. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [StreamProperties](../../groupdocs.metadata.formats.video/asfpackage/streamproperties) { get; } | Ruft die Eigenschaften des digitalen Medienstreams ab. |

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

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namensraum [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
