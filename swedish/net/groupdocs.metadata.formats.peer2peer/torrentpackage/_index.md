---
title: TorrentPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar metadata för torrentdeskriptorfil. Mer information finns påhttps//en.wikipedia.org/wiki/Torrent_filehttps//en.wikipedia.org/wiki/Torrent_file .
type: docs
weight: 2190
url: /sv/net/groupdocs.metadata.formats.peer2peer/torrentpackage/
---
## TorrentPackage class

Representerar metadata för torrentdeskriptorfil. Mer information finns på[https://en.wikipedia.org/wiki/Torrent_file](https://en.wikipedia.org/wiki/Torrent_file) .

```csharp
public sealed class TorrentPackage : CustomPackage
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Announce](../../groupdocs.metadata.formats.peer2peer/torrentpackage/announce) { get; set; } | Hämtar eller ställer in spårarens URL. |
| [Comment](../../groupdocs.metadata.formats.peer2peer/torrentpackage/comment) { get; set; } | Hämtar eller ställer in författarens kommentar. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [CreatedBy](../../groupdocs.metadata.formats.peer2peer/torrentpackage/createdby) { get; set; } | Hämtar eller ställer in namnet och versionen av programmet som används för att skapa torrenten. |
| [CreationDate](../../groupdocs.metadata.formats.peer2peer/torrentpackage/creationdate) { get; set; } | Hämtar eller ställer in datumet för skapandet av torrenten. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [PieceLength](../../groupdocs.metadata.formats.peer2peer/torrentpackage/piecelength) { get; } | Får antalet byte i varje bit. För mer information se . |
| [Pieces](../../groupdocs.metadata.formats.peer2peer/torrentpackage/pieces) { get; } | Får en byte-array som består av sammanlänkningen av alla 20-byte SHA1-hashvärden, en per bit. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [SharedFiles](../../groupdocs.metadata.formats.peer2peer/torrentpackage/sharedfiles) { get; } | Hämtar en array som innehåller delade filinformationsposter. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Lägger till kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar även alla kapslade paket. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestämmer om paketet innehåller en metadataegenskap med det angivna namnet. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Hittar metadataegenskaperna som uppfyller det angivna predikatet. Sökningen är rekursiv så den påverkar också alla kapslade paket. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Tar bort metadataegenskaper som uppfyller det angivna predikatet. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Tar bort skrivbara metadataegenskaper från paketet. Operationen är rekursiv så den påverkar alla kapslade paket också. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Anmärkningar

**Läs mer**

* [Arbeta med TORRENT-filer](https://docs.groupdocs.com/display/metadatanet/Working+with+TORRENT+files)

### Se även

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namnutrymme [GroupDocs.Metadata.Formats.Peer2Peer](../../groupdocs.metadata.formats.peer2peer)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
