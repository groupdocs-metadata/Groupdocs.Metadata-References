---
title: MP3RootPackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt das RootPaket dar das die Arbeit mit Metadaten in einem MP3Audio ermöglicht.
type: docs
weight: 580
url: /de/net/groupdocs.metadata.formats.audio/mp3rootpackage/
---
## MP3RootPackage class

Stellt das Root-Paket dar, das die Arbeit mit Metadaten in einem MP3-Audio ermöglicht.

```csharp
public class MP3RootPackage : RootMetadataPackage, IXmp
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ApeV2](../../groupdocs.metadata.formats.audio/mp3rootpackage/apev2) { get; } | Ruft die Metadaten von APE v2 ab. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Ruft das Dateityp-Metadatenpaket ab. |
| [ID3V1](../../groupdocs.metadata.formats.audio/mp3rootpackage/id3v1) { get; set; } | Ruft das ID3v1-Metadaten-Tag ab oder setzt es. Weitere Informationen finden Sie unter[http://id3.org/ID3v1](http://id3.org/ID3v1) . |
| [ID3V2](../../groupdocs.metadata.formats.audio/mp3rootpackage/id3v2) { get; set; } | Ruft das ID3v2-Metadaten-Tag ab oder legt es fest. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [Lyrics3V2](../../groupdocs.metadata.formats.audio/mp3rootpackage/lyrics3v2) { get; set; } | Ruft das Lyrics3v2-Metadaten-Tag ab oder legt es fest. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [MpegAudioPackage](../../groupdocs.metadata.formats.audio/mp3rootpackage/mpegaudiopackage) { get; } | Ruft das MPEG-Audio-Metadatenpaket ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [XmpPackage](../../groupdocs.metadata.formats.audio/mp3rootpackage/xmppackage) { get; set; } | Ruft das XMP-Metadatenpaket ab oder legt es fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [RemoveApeV2](../../groupdocs.metadata.formats.audio/mp3rootpackage/removeapev2)() | Entfernt das APEv2-Audio-Tag. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| override [Sanitize](../../groupdocs.metadata.formats.audio/mp3rootpackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Bemerkungen

**Mehr erfahren**

* [Arbeiten mit MP3-Metadaten](https://docs.groupdocs.com/display/metadatanet/Working+with+MP3+metadata)
* [Arbeiten mit XMP-Metadaten](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Siehe auch

* class [RootMetadataPackage](../../groupdocs.metadata.common/rootmetadatapackage)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* namensraum [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
