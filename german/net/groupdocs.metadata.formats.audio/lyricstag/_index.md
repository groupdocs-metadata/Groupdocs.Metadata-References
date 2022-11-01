---
title: LyricsTag
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Repräsentiert Lyrics3 v2.00Metadaten. Weitere Informationen finden Sie unterhttp//id3.org/Lyrics3v2 .
type: docs
weight: 570
url: /de/net/groupdocs.metadata.formats.audio/lyricstag/
---
## LyricsTag class

Repräsentiert Lyrics3 v2.00-Metadaten. Weitere Informationen finden Sie unterhttp://id3.org/Lyrics3v2 .

```csharp
public sealed class LyricsTag : CustomPackage
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [LyricsTag](lyricstag)() | Initialisiert eine neue Instanz von[`LyricsTag`](../lyricstag) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AdditionalInfo](../../groupdocs.metadata.formats.audio/lyricstag/additionalinfo) { get; set; } | Ruft die zusätzlichen Informationen ab oder setzt sie. Dieser Wert wird durch das INF-Feld repräsentiert. |
| [Album](../../groupdocs.metadata.formats.audio/lyricstag/album) { get; set; } | Ruft den Albumnamen ab oder legt ihn fest. Dieser Wert wird durch das EAL-Feld dargestellt. |
| [Artist](../../groupdocs.metadata.formats.audio/lyricstag/artist) { get; set; } | Ruft den Künstlernamen ab oder legt ihn fest. Dieser Wert wird durch das EAR-Feld dargestellt. |
| [Author](../../groupdocs.metadata.formats.audio/lyricstag/author) { get; set; } | Ruft den Autor ab oder legt ihn fest. Dieser Wert wird durch das AUT-Feld dargestellt. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [Lyrics](../../groupdocs.metadata.formats.audio/lyricstag/lyrics) { get; set; } | Ruft den Liedtext ab oder legt ihn fest. Dieser Wert wird durch das LYR-Feld dargestellt. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [Track](../../groupdocs.metadata.formats.audio/lyricstag/track) { get; set; } | Ruft den Tracktitel ab oder legt ihn fest. Dieser Wert wird durch das ETT-Feld repräsentiert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [Get](../../groupdocs.metadata.formats.audio/lyricstag/get)(string) | Ruft den Wert des Felds mit der angegebenen ID ab. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [Remove](../../groupdocs.metadata.formats.audio/lyricstag/remove)(string) | Entfernt das Feld mit der angegebenen ID. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [Set](../../groupdocs.metadata.formats.audio/lyricstag/set)(LyricsField) | Fügt das angegebene Liedtext3-Feld hinzu oder ersetzt es. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [ToList](../../groupdocs.metadata.formats.audio/lyricstag/tolist)() | Erstellt eine Liste aus dem Paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Bemerkungen

Lyrics3 v2.00 verwendet Felder zur Darstellung von Informationen. Die Daten in einem Feld können laut Standard aus ASCII-Zeichen im Bereich von 01 bis 254 bestehen. Da die ASCII-Zeichentabelle nur von 00 bis 128 ISO-8859- 1 könnte angenommen werden. Numerische Felder sind je nach Standort 5 oder 6 Zeichen lang und werden mit Nullen aufgefüllt.

**Mehr erfahren**

* [Handhabung des Lyrics-Tags](https://docs.groupdocs.com/display/metadatanet/Handling+the+Lyrics+tag)

### Beispiele

Dieses Codebeispiel zeigt, wie das Liedtext-Tag aus einer MP3-Datei gelesen wird.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithLyrics))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.Lyrics3V2 != null)
    {
        Console.WriteLine(root.Lyrics3V2.Lyrics);
        Console.WriteLine(root.Lyrics3V2.Album);
        Console.WriteLine(root.Lyrics3V2.Artist);
        Console.WriteLine(root.Lyrics3V2.Track);

        // ...

        // Alternativ können Sie eine vollständige Liste von Tag-Feldern durchlaufen
        foreach (var field in root.Lyrics3V2.ToList())
        {
            Console.WriteLine("{0} = {1}", field.ID, field.Data);
        }
    }
}
```

### Siehe auch

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namensraum [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
