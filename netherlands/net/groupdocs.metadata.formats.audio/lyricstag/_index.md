---
title: LyricsTag
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt Lyrics3 v2.00 metadata. Meer informatie vindt u ophttp//id3.org/Lyrics3v2 .
type: docs
weight: 570
url: /nl/net/groupdocs.metadata.formats.audio/lyricstag/
---
## LyricsTag class

Vertegenwoordigt Lyrics3 v2.00 metadata. Meer informatie vindt u ophttp://id3.org/Lyrics3v2 .

```csharp
public sealed class LyricsTag : CustomPackage
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [LyricsTag](lyricstag)() | Initialiseert een nieuw exemplaar van het[`LyricsTag`](../lyricstag) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AdditionalInfo](../../groupdocs.metadata.formats.audio/lyricstag/additionalinfo) { get; set; } | Haalt de aanvullende informatie op of stelt deze in. Deze waarde wordt vertegenwoordigd door het INF-veld. |
| [Album](../../groupdocs.metadata.formats.audio/lyricstag/album) { get; set; } | Hiermee wordt de albumnaam opgehaald of ingesteld. Deze waarde wordt vertegenwoordigd door het EAL-veld. |
| [Artist](../../groupdocs.metadata.formats.audio/lyricstag/artist) { get; set; } | Haalt de naam van de artiest op of stelt deze in. Deze waarde wordt vertegenwoordigd door het veld EAR. |
| [Author](../../groupdocs.metadata.formats.audio/lyricstag/author) { get; set; } | Haalt de auteur op of stelt deze in. Deze waarde wordt vertegenwoordigd door het veld AUT. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [Lyrics](../../groupdocs.metadata.formats.audio/lyricstag/lyrics) { get; set; } | Haalt de songtekst op of stelt deze in. Deze waarde wordt vertegenwoordigd door het LYR-veld. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [Track](../../groupdocs.metadata.formats.audio/lyricstag/track) { get; set; } | Haalt de tracktitel op of stelt deze in. Deze waarde wordt vertegenwoordigd door het ETT-veld. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Voegt bekende metadata-eigenschappen toe die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bepaalt of het pakket een metadata-eigenschap bevat met de opgegeven naam. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Zoekt de metadata-eigenschappen die voldoen aan het opgegeven predikaat. De zoekopdracht is recursief, dus het heeft ook invloed op alle geneste pakketten. |
| [Get](../../groupdocs.metadata.formats.audio/lyricstag/get)(string) | Haalt de waarde op van het veld met de opgegeven id. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Retourneert een enumerator die de verzameling herhaalt. |
| [Remove](../../groupdocs.metadata.formats.audio/lyricstag/remove)(string) | Verwijdert het veld met de opgegeven id. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Verwijdert beschrijfbare metadata-eigenschappen uit het pakket. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Set](../../groupdocs.metadata.formats.audio/lyricstag/set)(LyricsField) | Voegt het opgegeven Lyrics3-veld toe of vervangt het. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [ToList](../../groupdocs.metadata.formats.audio/lyricstag/tolist)() | Maakt een lijst van het pakket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Opmerkingen

Lyrics3 v2.00 gebruikt velden om informatie weer te geven. De gegevens in een veld kunnen volgens de standaard bestaan uit ASCII-tekens in het bereik van 01 tot 254. Aangezien de ASCII-tekenkaart alleen is gedefinieerd van 00 tot 128 ISO-8859- 1 mag worden aangenomen. Numerieke velden zijn 5 of 6 tekens lang, afhankelijk van de locatie, en worden opgevuld met nullen.

**Kom meer te weten**

* [Omgaan met de Lyrics-tag](https://docs.groupdocs.com/display/metadatanet/Handling+the+Lyrics+tag)

### Voorbeelden

Dit codevoorbeeld laat zien hoe je de Lyrics-tag uit een MP3-bestand kunt lezen.

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

        // U kunt ook een volledige lijst met tagvelden doorlopen
        foreach (var field in root.Lyrics3V2.ToList())
        {
            Console.WriteLine("{0} = {1}", field.ID, field.Data);
        }
    }
}
```

### Zie ook

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* naamruimte [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
