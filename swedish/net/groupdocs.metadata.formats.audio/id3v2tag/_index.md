---
title: ID3V2Tag
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar en ID3v2tagg. Mer information finns påhttps//en.wikipedia.org/wiki/ID3ID3v2https//en.wikipedia.org/wiki/ID3ID3v2 .
type: docs
weight: 490
url: /sv/net/groupdocs.metadata.formats.audio/id3v2tag/
---
## ID3V2Tag class

Representerar en ID3v2-tagg. Mer information finns på[https://en.wikipedia.org/wiki/ID3#ID3v2](https://en.wikipedia.org/wiki/ID3#ID3v2) .

```csharp
public sealed class ID3V2Tag : ID3Tag
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ID3V2Tag](id3v2tag)() | Initierar en ny instans av[`ID3V2Tag`](../id3v2tag) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v2tag/album) { get; set; } | Hämtar eller ställer in albumets/filmens/showtiteln. Detta värde representeras av TALB-ramen. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v2tag/artist) { get; set; } | Hämtar eller ställer in huvudartist(erna)/lead artist(er)/solister/uppträdande grupp. Detta värde representeras av TPE1-ramen. |
| [AttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/attachedpictures) { get; set; } | Hämtar eller ställer in de bifogade bilderna direkt relaterade till ljudfilen. Detta värde representeras av APIC-ramen. |
| [Band](../../groupdocs.metadata.formats.audio/id3v2tag/band) { get; set; } | Hämtar eller ställer in bandet/orkestern/ackompanjemanget. Detta värde representeras av TPE2-ramen. |
| [BitsPerMinute](../../groupdocs.metadata.formats.audio/id3v2tag/bitsperminute) { get; set; } | Hämtar eller ställer in antalet slag per minut i huvuddelen av ljudet. Detta värde representeras av TBPM-ramen. |
| [Comments](../../groupdocs.metadata.formats.audio/id3v2tag/comments) { get; set; } | Hämtar eller ställer in användarkommentarer. Detta värde representeras av COMM-ramen. Ramen är avsedd för all typ av fulltextinformation som inte passar i någon annan ram. |
| [Composers](../../groupdocs.metadata.formats.audio/id3v2tag/composers) { get; set; } | Hämtar eller sätter kompositörerna. Namnen separeras med tecknet "/". Detta värde representeras av TCOM-ramen. |
| [ContentType](../../groupdocs.metadata.formats.audio/id3v2tag/contenttype) { get; set; } | Hämtar eller ställer in innehållstypen. Detta värde representeras av TCON-ramen. |
| [Copyright](../../groupdocs.metadata.formats.audio/id3v2tag/copyright) { get; set; } | Hämtar eller ställer in copyrightmeddelandet. Detta värde representeras av TCOP-ramen. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [Date](../../groupdocs.metadata.formats.audio/id3v2tag/date) { get; set; } | Hämtar eller ställer in en numerisk sträng i DDMM-formatet som innehåller datumet för inspelningen. Detta fält är alltid fyra tecken långt. Detta värde representeras av TDAT-ramen. |
| [EncodedBy](../../groupdocs.metadata.formats.audio/id3v2tag/encodedby) { get; set; } | Hämtar eller ställer in namnet på personen eller organisationen som kodade ljudfilen. Detta värde representeras av TENC-ramen. |
| [Isrc](../../groupdocs.metadata.formats.audio/id3v2tag/isrc) { get; set; } | Hämtar eller ställer in International Standard Recording Code (ISRC) (12 tecken). Detta värde representeras av TSRC-ramen. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [LengthInMilliseconds](../../groupdocs.metadata.formats.audio/id3v2tag/lengthinmilliseconds) { get; set; } | Hämtar eller ställer in längden på ljudfilen i millisekunder, representerad som en numerisk sträng. Detta värde representeras av TLEN-ramen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [MusicalKey](../../groupdocs.metadata.formats.audio/id3v2tag/musicalkey) { get; set; } | Hämtar eller ställer in den musikaliska nyckeln där ljudet börjar. Detta värde representeras av TKEY-ramen. |
| [OriginalAlbum](../../groupdocs.metadata.formats.audio/id3v2tag/originalalbum) { get; set; } | Hämtar eller ställer in originalalbumets/filmens/showtiteln. Detta värde representeras av TOAL-ramen. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [Publisher](../../groupdocs.metadata.formats.audio/id3v2tag/publisher) { get; set; } | Hämtar eller ställer in namnet på etiketten eller utgivaren. Detta värde representeras av TPUB-ramen. |
| [SizeInBytes](../../groupdocs.metadata.formats.audio/id3v2tag/sizeinbytes) { get; set; } | Hämtar eller ställer in storleken på ljudfilen i byte, exklusive ID3v2-taggen, representerad som en numerisk sträng. Detta värde representeras av TSIZ-ramen. |
| [SoftwareHardware](../../groupdocs.metadata.formats.audio/id3v2tag/softwarehardware) { get; set; } | Hämtar eller ställer in den använda ljudkodaren och dess inställningar när filen kodades. Detta värde representeras av TSSE-ramen. |
| [Subtitle](../../groupdocs.metadata.formats.audio/id3v2tag/subtitle) { get; set; } | Hämtar eller ställer in undertext/beskrivningsförfining. Detta värde representeras av TIT3-ramen. |
| [TagSize](../../groupdocs.metadata.formats.audio/id3v2tag/tagsize) { get; } | Hämtar storleken på taggen. |
| [Time](../../groupdocs.metadata.formats.audio/id3v2tag/time) { get; set; } | Hämtar eller ställer in en numerisk sträng i formatet HHMM som innehåller tiden för inspelningen. Detta fält är alltid fyra tecken långt. Detta värde representeras av TIME-ramen. |
| [Title](../../groupdocs.metadata.formats.audio/id3v2tag/title) { get; set; } | Hämtar eller ställer in titel/låtnamn/innehållsbeskrivning. Detta värde representeras av TIT2-ramen. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v2tag/tracknumber) { get; set; } | Hämtar eller ställer in en numerisk sträng som innehåller ordningsnumret för ljudfilen på dess ursprungliga inspelning. Detta värde representeras av TRCK-ramen. |
| [TrackPlayCounter](../../groupdocs.metadata.formats.audio/id3v2tag/trackplaycounter) { get; } | Hämtar antalet gånger filen har spelats. Detta värde representeras av PCNT-ramen. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v2tag/version) { get; } | Hämtar ID3-versionen. |
| [Year](../../groupdocs.metadata.formats.audio/id3v2tag/year) { get; set; } | Hämtar eller ställer in en numerisk sträng med ett år för inspelningen. Dessa ramar är alltid fyra tecken långa (till år 10000). Detta värde representeras av TYER-ramen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Add](../../groupdocs.metadata.formats.audio/id3v2tag/add)(ID3V2TagFrame) | Lägger till en ram till taggen. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Lägger till kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar även alla kapslade paket. |
| [Clear](../../groupdocs.metadata.formats.audio/id3v2tag/clear)(string) | Tar bort alla ramar med angivet id. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestämmer om paketet innehåller en metadataegenskap med det angivna namnet. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Hittar metadataegenskaperna som uppfyller det angivna predikatet. Sökningen är rekursiv så den påverkar också alla kapslade paket. |
| [Get](../../groupdocs.metadata.formats.audio/id3v2tag/get)(string) | Får en array av ramar med det angivna id. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| [Remove](../../groupdocs.metadata.formats.audio/id3v2tag/remove)(ID3V2TagFrame) | Tar bort den angivna ramen från taggen. |
| [RemoveAttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/removeattachedpictures)() | Tar bort alla bifogade bilder lagrade i APIC-ramar. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Tar bort metadataegenskaper som uppfyller det angivna predikatet. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Tar bort skrivbara metadataegenskaper från paketet. Operationen är rekursiv så den påverkar alla kapslade paket också. |
| [Set](../../groupdocs.metadata.formats.audio/id3v2tag/set)(ID3V2TagFrame) | Tar bort alla ramar som har samma id som den angivna och lägger till den nya ramen i taggen. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [ToList](../../groupdocs.metadata.formats.audio/id3v2tag/tolist)() | Skapar en lista från paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Anmärkningar

**Läs mer**

* [Hantera ID3v2-taggen](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Exempel

Det här exemplet visar hur man läser ID3v2-taggen i en MP3-fil.

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

### Se även

* class [ID3Tag](../id3tag)
* namnutrymme [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
