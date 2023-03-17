---
title: ID3V2Tag
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt een ID3v2tag. Meer informatie vindt u ophttps//en.wikipedia.org/wiki/ID3ID3v2https//en.wikipedia.org/wiki/ID3ID3v2 .
type: docs
weight: 490
url: /nl/net/groupdocs.metadata.formats.audio/id3v2tag/
---
## ID3V2Tag class

Vertegenwoordigt een ID3v2-tag. Meer informatie vindt u op[https://en.wikipedia.org/wiki/ID3#ID3v2](https://en.wikipedia.org/wiki/ID3#ID3v2) .

```csharp
public sealed class ID3V2Tag : ID3Tag
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [ID3V2Tag](id3v2tag)() | Initialiseert een nieuw exemplaar van het[`ID3V2Tag`](../id3v2tag) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v2tag/album) { get; set; } | Haalt de album/film/showtitel op of stelt deze in. Deze waarde wordt vertegenwoordigd door het TALB-frame. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v2tag/artist) { get; set; } | Haalt of stelt de hoofdartiest(en)/hoofdartiest(en)/solist(en)/optredende groep in. Deze waarde wordt vertegenwoordigd door het TPE1-frame. |
| [AttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/attachedpictures) { get; set; } | Haalt of stelt de bijgevoegde afbeeldingen direct gerelateerd aan het audiobestand in. Deze waarde wordt vertegenwoordigd door het APIC-frame. |
| [Band](../../groupdocs.metadata.formats.audio/id3v2tag/band) { get; set; } | Haalt of stelt de band/orkest/begeleiding in. Deze waarde wordt vertegenwoordigd door het TPE2-frame. |
| [BitsPerMinute](../../groupdocs.metadata.formats.audio/id3v2tag/bitsperminute) { get; set; } | Hiermee wordt het aantal beats per minuut in het hoofdgedeelte van de audio opgehaald of ingesteld. Deze waarde wordt weergegeven door het TBPM-frame. |
| [Comments](../../groupdocs.metadata.formats.audio/id3v2tag/comments) { get; set; } | Ontvangt of stelt de gebruikerscommentaar in. Deze waarde wordt weergegeven door het COMM-frame. Het frame is bedoeld voor alle soorten volledige tekstinformatie die niet in een ander frame past. |
| [Composers](../../groupdocs.metadata.formats.audio/id3v2tag/composers) { get; set; } | Haalt of stelt de componisten in. De namen worden gescheiden door het teken "/". Deze waarde wordt weergegeven door het TCOM-frame. |
| [ContentType](../../groupdocs.metadata.formats.audio/id3v2tag/contenttype) { get; set; } | Hiermee wordt het inhoudstype opgehaald of ingesteld. Deze waarde wordt weergegeven door het TCON-frame. |
| [Copyright](../../groupdocs.metadata.formats.audio/id3v2tag/copyright) { get; set; } | Haalt het copyrightbericht op of stelt het in. Deze waarde wordt vertegenwoordigd door het TCOP-frame. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [Date](../../groupdocs.metadata.formats.audio/id3v2tag/date) { get; set; } | Haalt of stelt een numerieke string in de DDMM-indeling in die de datum voor de opname bevat. Dit veld is altijd vier tekens lang. Deze waarde wordt weergegeven door het TDAT-frame. |
| [EncodedBy](../../groupdocs.metadata.formats.audio/id3v2tag/encodedby) { get; set; } | Haalt of stelt de naam in van de persoon of organisatie die het audiobestand heeft gecodeerd. Deze waarde wordt vertegenwoordigd door het TENC-frame. |
| [Isrc](../../groupdocs.metadata.formats.audio/id3v2tag/isrc) { get; set; } | Haalt de International Standard Recording Code (ISRC) (12 tekens) op of stelt deze in. Deze waarde wordt vertegenwoordigd door het TSRC-frame. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [LengthInMilliseconds](../../groupdocs.metadata.formats.audio/id3v2tag/lengthinmilliseconds) { get; set; } | Hiermee wordt de lengte van het audiobestand in milliseconden opgehaald of ingesteld, weergegeven als een numerieke reeks. Deze waarde wordt weergegeven door het TLEN-frame. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [MusicalKey](../../groupdocs.metadata.formats.audio/id3v2tag/musicalkey) { get; set; } | Haalt of stelt de toonsoort in waarin het geluid begint. Deze waarde wordt vertegenwoordigd door het TKEY-frame. |
| [OriginalAlbum](../../groupdocs.metadata.formats.audio/id3v2tag/originalalbum) { get; set; } | Haalt of stelt de originele titel van het album/de film/show in. Deze waarde wordt vertegenwoordigd door het TOAL-frame. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [Publisher](../../groupdocs.metadata.formats.audio/id3v2tag/publisher) { get; set; } | Haalt de naam van het label of de uitgever op of stelt deze in. Deze waarde wordt vertegenwoordigd door het TPUB-frame. |
| [SizeInBytes](../../groupdocs.metadata.formats.audio/id3v2tag/sizeinbytes) { get; set; } | Hiermee wordt de grootte van het audiobestand in bytes opgehaald of ingesteld, exclusief de ID3v2-tag, weergegeven als een numerieke tekenreeks. Deze waarde wordt weergegeven door het TSIZ-frame. |
| [SoftwareHardware](../../groupdocs.metadata.formats.audio/id3v2tag/softwarehardware) { get; set; } | Haalt of stelt de gebruikte audio-encoder en de instellingen ervan in toen het bestand werd gecodeerd. Deze waarde wordt vertegenwoordigd door het TSSE-frame. |
| [Subtitle](../../groupdocs.metadata.formats.audio/id3v2tag/subtitle) { get; set; } | Haalt de verfijning van de ondertitel/beschrijving op of stelt deze in. Deze waarde wordt vertegenwoordigd door het TIT3-frame. |
| [TagSize](../../groupdocs.metadata.formats.audio/id3v2tag/tagsize) { get; } | Krijgt de grootte van de tag. |
| [Time](../../groupdocs.metadata.formats.audio/id3v2tag/time) { get; set; } | Haalt of stelt een numerieke reeks in de UUMM-indeling op die de tijd voor de opname bevat. Dit veld is altijd vier tekens lang. Deze waarde wordt weergegeven door het frame TIME. |
| [Title](../../groupdocs.metadata.formats.audio/id3v2tag/title) { get; set; } | Haalt de titel/naam van het nummer/beschrijving van de inhoud op of stelt deze in. Deze waarde wordt vertegenwoordigd door het TIT2-frame. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v2tag/tracknumber) { get; set; } | Haalt een numerieke reeks op of stelt deze in met het bestelnummer van het audiobestand op de oorspronkelijke opname. Deze waarde wordt vertegenwoordigd door het TRCK-frame. |
| [TrackPlayCounter](../../groupdocs.metadata.formats.audio/id3v2tag/trackplaycounter) { get; } | Krijgt het aantal keren dat het bestand is afgespeeld. Deze waarde wordt vertegenwoordigd door het PCNT-frame. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v2tag/version) { get; } | Krijgt de ID3-versie. |
| [Year](../../groupdocs.metadata.formats.audio/id3v2tag/year) { get; set; } | Haalt of stelt een numerieke reeks in met een jaartal van de opname. Dit frame is altijd vier tekens lang (tot het jaar 10000). Deze waarde wordt weergegeven door het TYER-frame. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Add](../../groupdocs.metadata.formats.audio/id3v2tag/add)(ID3V2TagFrame) | Voegt een frame toe aan de tag. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Voegt bekende metadata-eigenschappen toe die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Clear](../../groupdocs.metadata.formats.audio/id3v2tag/clear)(string) | Verwijdert alle frames met de opgegeven id. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bepaalt of het pakket een metadata-eigenschap bevat met de opgegeven naam. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Zoekt de metadata-eigenschappen die voldoen aan het opgegeven predikaat. De zoekopdracht is recursief, dus het heeft ook invloed op alle geneste pakketten. |
| [Get](../../groupdocs.metadata.formats.audio/id3v2tag/get)(string) | Krijgt een reeks frames met de opgegeven id. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Retourneert een enumerator die de verzameling herhaalt. |
| [Remove](../../groupdocs.metadata.formats.audio/id3v2tag/remove)(ID3V2TagFrame) | Verwijdert het opgegeven frame uit de tag. |
| [RemoveAttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/removeattachedpictures)() | Verwijdert alle bijgevoegde afbeeldingen die zijn opgeslagen in APIC-frames. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Verwijdert beschrijfbare metadata-eigenschappen uit het pakket. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Set](../../groupdocs.metadata.formats.audio/id3v2tag/set)(ID3V2TagFrame) | Verwijdert alle frames met dezelfde id als de opgegeven en voegt het nieuwe frame toe aan de tag. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [ToList](../../groupdocs.metadata.formats.audio/id3v2tag/tolist)() | Maakt een lijst van het pakket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Opmerkingen

**Kom meer te weten**

* [Omgaan met de ID3v2-tag](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Voorbeelden

In dit voorbeeld ziet u hoe u de ID3v2-tag in een MP3-bestand leest.

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

### Zie ook

* class [ID3Tag](../id3tag)
* naamruimte [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
