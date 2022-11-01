---
title: ID3V2Tag
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Repräsentiert ein ID3v2Tag. Weitere Informationen finden Sie unterhttps//en.wikipedia.org/wiki/ID3ID3v2https//en.wikipedia.org/wiki/ID3ID3v2 .
type: docs
weight: 490
url: /de/net/groupdocs.metadata.formats.audio/id3v2tag/
---
## ID3V2Tag class

Repräsentiert ein ID3v2-Tag. Weitere Informationen finden Sie unter[https://en.wikipedia.org/wiki/ID3#ID3v2](https://en.wikipedia.org/wiki/ID3#ID3v2) .

```csharp
public sealed class ID3V2Tag : ID3Tag
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ID3V2Tag](id3v2tag)() | Initialisiert eine neue Instanz von[`ID3V2Tag`](../id3v2tag) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v2tag/album) { get; set; } | Ruft den Titel des Albums/Films/der Sendung ab oder legt ihn fest. Dieser Wert wird durch den TALB-Rahmen dargestellt. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v2tag/artist) { get; set; } | Ermittelt oder legt den/die Lead Artist(s)/Lead Performer/Solist(s)/Performing Group fest. Dieser Wert wird durch den TPE1-Rahmen dargestellt. |
| [AttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/attachedpictures) { get; set; } | Ruft die angehängten Bilder ab oder legt sie fest, die sich direkt auf die Audiodatei beziehen. Dieser Wert wird durch den APIC-Rahmen dargestellt. |
| [Band](../../groupdocs.metadata.formats.audio/id3v2tag/band) { get; set; } | Ruft Band/Orchester/Begleitung ab oder stellt sie ein. Dieser Wert wird durch den TPE2-Rahmen repräsentiert. |
| [BitsPerMinute](../../groupdocs.metadata.formats.audio/id3v2tag/bitsperminute) { get; set; } | Ruft die Anzahl der Beats pro Minute im Hauptteil des Audios ab oder legt sie fest. Dieser Wert wird durch den TBPM-Frame dargestellt. |
| [Comments](../../groupdocs.metadata.formats.audio/id3v2tag/comments) { get; set; } | Ruft die Benutzerkommentare ab oder setzt sie. Dieser Wert wird durch den COMM-Rahmen dargestellt. Der Rahmen ist für jede Art von Volltextinformationen gedacht, die in keinen anderen Rahmen passen. |
| [Composers](../../groupdocs.metadata.formats.audio/id3v2tag/composers) { get; set; } | Holt oder setzt die Composer. Die Namen werden mit dem Zeichen „/“ getrennt. Dieser Wert wird durch den TCOM-Frame dargestellt. |
| [ContentType](../../groupdocs.metadata.formats.audio/id3v2tag/contenttype) { get; set; } | Ruft den Inhaltstyp ab oder legt ihn fest. Dieser Wert wird durch den TCON-Rahmen dargestellt. |
| [Copyright](../../groupdocs.metadata.formats.audio/id3v2tag/copyright) { get; set; } | Ruft die Urheberrechtsmeldung ab oder legt sie fest. Dieser Wert wird durch den TCOP-Rahmen dargestellt. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [Date](../../groupdocs.metadata.formats.audio/id3v2tag/date) { get; set; } | Liest oder setzt eine numerische Zeichenfolge im DDMM-Format, die das Datum für die Aufzeichnung enthält. Dieses Feld ist immer vier Zeichen lang. Dieser Wert wird durch den TDAT-Rahmen dargestellt. |
| [EncodedBy](../../groupdocs.metadata.formats.audio/id3v2tag/encodedby) { get; set; } | Ruft den Namen der Person oder Organisation ab, die die Audiodatei codiert hat, oder legt diesen fest. Dieser Wert wird durch den TENC-Rahmen dargestellt. |
| [Isrc](../../groupdocs.metadata.formats.audio/id3v2tag/isrc) { get; set; } | Ruft den International Standard Recording Code (ISRC) (12 Zeichen) ab oder legt ihn fest. Dieser Wert wird durch den TSRC-Rahmen dargestellt. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [LengthInMilliseconds](../../groupdocs.metadata.formats.audio/id3v2tag/lengthinmilliseconds) { get; set; } | Ruft die Länge der Audiodatei in Millisekunden ab oder legt sie fest, dargestellt als numerische Zeichenfolge. Dieser Wert wird durch den TLEN-Frame dargestellt. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [MusicalKey](../../groupdocs.metadata.formats.audio/id3v2tag/musicalkey) { get; set; } | Ruft die Tonart ab, in der der Ton beginnt, oder legt sie fest. Dieser Wert wird durch den TKEY-Rahmen dargestellt. |
| [OriginalAlbum](../../groupdocs.metadata.formats.audio/id3v2tag/originalalbum) { get; set; } | Ruft den Originaltitel des Albums/Films/der Sendung ab oder legt ihn fest. Dieser Wert wird durch den TOAL-Frame dargestellt. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [Publisher](../../groupdocs.metadata.formats.audio/id3v2tag/publisher) { get; set; } | Ruft den Namen des Labels oder Herausgebers ab oder legt ihn fest. Dieser Wert wird durch den TPUB-Rahmen dargestellt. |
| [SizeInBytes](../../groupdocs.metadata.formats.audio/id3v2tag/sizeinbytes) { get; set; } | Ruft die Größe der Audiodatei in Bytes ab oder legt sie fest, ohne das ID3v2-Tag, dargestellt als numerische Zeichenfolge. Dieser Wert wird durch den TSIZ-Frame dargestellt. |
| [SoftwareHardware](../../groupdocs.metadata.formats.audio/id3v2tag/softwarehardware) { get; set; } | Ermittelt oder setzt den verwendeten Audio-Encoder und seine Einstellungen beim Encodieren der Datei. Dieser Wert wird durch den TSSE-Frame dargestellt. |
| [Subtitle](../../groupdocs.metadata.formats.audio/id3v2tag/subtitle) { get; set; } | Ruft die Subtitle/Description-Verfeinerung ab oder legt sie fest. Dieser Wert wird durch den TIT3-Frame repräsentiert. |
| [TagSize](../../groupdocs.metadata.formats.audio/id3v2tag/tagsize) { get; } | Ruft die Größe des Tags ab. |
| [Time](../../groupdocs.metadata.formats.audio/id3v2tag/time) { get; set; } | Liest oder setzt eine numerische Zeichenfolge im HHMM-Format, die die Zeit für die Aufzeichnung enthält. Dieses Feld ist immer vier Zeichen lang. Dieser Wert wird durch den Rahmen TIME dargestellt. |
| [Title](../../groupdocs.metadata.formats.audio/id3v2tag/title) { get; set; } | Ruft Titel/Songname/Inhaltsbeschreibung ab oder legt sie fest. Dieser Wert wird durch den TIT2-Rahmen repräsentiert. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v2tag/tracknumber) { get; set; } | Erhält oder setzt eine numerische Zeichenkette, die die Ordnungsnummer der Audiodatei auf ihrer Originalaufnahme enthält. Dieser Wert wird durch den TRCK-Rahmen dargestellt. |
| [TrackPlayCounter](../../groupdocs.metadata.formats.audio/id3v2tag/trackplaycounter) { get; } | Ruft ab, wie oft die Datei abgespielt wurde. Dieser Wert wird durch den PCNT-Rahmen dargestellt. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v2tag/version) { get; } | Ruft die ID3-Version ab. |
| [Year](../../groupdocs.metadata.formats.audio/id3v2tag/year) { get; set; } | Liest oder setzt eine numerische Zeichenkette mit einem Jahr der Aufnahme. Dieser Rahmen ist immer vier Zeichen lang (bis zum Jahr 10000). Dieser Wert wird durch den TYER-Rahmen dargestellt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../groupdocs.metadata.formats.audio/id3v2tag/add)(ID3V2TagFrame) | Fügt dem Tag einen Rahmen hinzu. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [Clear](../../groupdocs.metadata.formats.audio/id3v2tag/clear)(string) | Entfernt alle Frames mit der angegebenen ID. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [Get](../../groupdocs.metadata.formats.audio/id3v2tag/get)(string) | Ruft ein Array von Frames mit der angegebenen ID ab. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [Remove](../../groupdocs.metadata.formats.audio/id3v2tag/remove)(ID3V2TagFrame) | Entfernt den angegebenen Frame aus dem Tag. |
| [RemoveAttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/removeattachedpictures)() | Entfernt alle angehängten Bilder, die in APIC-Frames gespeichert sind. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [Set](../../groupdocs.metadata.formats.audio/id3v2tag/set)(ID3V2TagFrame) | Entfernt alle Frames mit derselben ID wie der angegebene und fügt den neuen Frame zum Tag hinzu. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [ToList](../../groupdocs.metadata.formats.audio/id3v2tag/tolist)() | Erstellt eine Liste aus dem Paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Bemerkungen

**Mehr erfahren**

* [Umgang mit dem ID3v2-Tag](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Beispiele

Dieses Beispiel zeigt, wie das ID3v2-Tag in einer MP3-Datei gelesen wird.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V2 != null)
    {
        Console.WriteLine(root.ID3V2.Album);
        Console.WriteLine(root.ID3V2.Artist);
        Console.WriteLine(root.ID3V2.Band);
        Console.WriteLine(root.ID3V2.Title);
        Console.WriteLine(root.ID3V2.Composers);
        Console.WriteLine(root.ID3V2.Copyright);
        Console.WriteLine(root.ID3V2.Publisher);
        Console.WriteLine(root.ID3V2.OriginalAlbum);
        Console.WriteLine(root.ID3V2.MusicalKey);

        if (root.ID3V2.AttachedPictures != null)
        {
            foreach (var attachedPicture in root.ID3V2.AttachedPictures)
            {
                Console.WriteLine(attachedPicture.AttachedPictureType);
                Console.WriteLine(attachedPicture.MimeType);
                Console.WriteLine(attachedPicture.Description);

                // ...
            }
        }

        // ...
    }
}
```

### Siehe auch

* class [ID3Tag](../id3tag)
* namensraum [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
