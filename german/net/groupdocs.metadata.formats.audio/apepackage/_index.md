---
title: ApePackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Repräsentiert ein APE v2Metadatenpaket. Weitere Informationen finden Sie unterhttp//wiki.hydrogenaud.io/index.phptitleAPE_keyhttp//wiki.hydrogenaud.io/index.phptitleAPE_key .
type: docs
weight: 380
url: /de/net/groupdocs.metadata.formats.audio/apepackage/
---
## ApePackage class

Repräsentiert ein APE v2-Metadatenpaket. Weitere Informationen finden Sie unter[http://wiki.hydrogenaud.io/index.php?title=APE_key](http://wiki.hydrogenaud.io/index.php?title=APE_key) .

```csharp
public sealed class ApePackage : CustomPackage
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Abstract](../../groupdocs.metadata.formats.audio/apepackage/abstract) { get; } | Ruft den abstrakten Link ab. |
| [Album](../../groupdocs.metadata.formats.audio/apepackage/album) { get; } | Ruft das Album ab. |
| [Artist](../../groupdocs.metadata.formats.audio/apepackage/artist) { get; } | Ruft den Künstler ab. |
| [Bibliography](../../groupdocs.metadata.formats.audio/apepackage/bibliography) { get; } | Ruft das Literaturverzeichnis ab. |
| [Comment](../../groupdocs.metadata.formats.audio/apepackage/comment) { get; } | Ruft den Kommentar ab. |
| [Composer](../../groupdocs.metadata.formats.audio/apepackage/composer) { get; } | Ruft den Komponisten ab. |
| [Conductor](../../groupdocs.metadata.formats.audio/apepackage/conductor) { get; } | Holt den Schaffner. |
| [Copyright](../../groupdocs.metadata.formats.audio/apepackage/copyright) { get; } | erhält das Urheberrecht. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [DebutAlbum](../../groupdocs.metadata.formats.audio/apepackage/debutalbum) { get; } | Holt sich das Debütalbum. |
| [File](../../groupdocs.metadata.formats.audio/apepackage/file) { get; } | Ruft die Datei ab. |
| [Genre](../../groupdocs.metadata.formats.audio/apepackage/genre) { get; } | Ruft das Genre ab. |
| [Isbn](../../groupdocs.metadata.formats.audio/apepackage/isbn) { get; } | Liefert die ISBN-Nummer mit Prüfziffer. Siehe mehr: https://en.wikipedia.org/wiki/International_Standard_Book_Number. |
| [Isrc](../../groupdocs.metadata.formats.audio/apepackage/isrc) { get; } | Ruft die internationale Standardaufzeichnungsnummer ab. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [Language](../../groupdocs.metadata.formats.audio/apepackage/language) { get; } | Ruft die Sprache ab. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [PublicationRight](../../groupdocs.metadata.formats.audio/apepackage/publicationright) { get; } | Erhält die Veröffentlichung richtig. |
| [Publisher](../../groupdocs.metadata.formats.audio/apepackage/publisher) { get; } | Ruft den Publisher ab. |
| [RecordLocation](../../groupdocs.metadata.formats.audio/apepackage/recordlocation) { get; } | Ruft den Aufnahmeort ab. |
| [Subtitle](../../groupdocs.metadata.formats.audio/apepackage/subtitle) { get; } | Ruft den Untertitel ab. |
| [Title](../../groupdocs.metadata.formats.audio/apepackage/title) { get; } | Ruft den Titel ab. |
| [Track](../../groupdocs.metadata.formats.audio/apepackage/track) { get; } | Ruft die Titelnummer ab. |

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

* [Umgang mit dem APEv2-Tag](https://docs.groupdocs.com/display/metadatanet/Handling+the+APEv2+tag)

### Beispiele

Dieses Beispiel zeigt, wie das APEv2-Tag in einer MP3-Datei gelesen wird.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithApe))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ApeV2 != null)
    {
        Console.WriteLine(root.ApeV2.Album);
        Console.WriteLine(root.ApeV2.Title);
        Console.WriteLine(root.ApeV2.Artist);
        Console.WriteLine(root.ApeV2.Composer);
        Console.WriteLine(root.ApeV2.Copyright);
        Console.WriteLine(root.ApeV2.Genre);
        Console.WriteLine(root.ApeV2.Language);

        // ...
    }
}
```

### Siehe auch

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namensraum [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
