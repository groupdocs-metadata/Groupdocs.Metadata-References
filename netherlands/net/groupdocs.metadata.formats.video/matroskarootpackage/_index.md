---
title: MatroskaRootPackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt het rootpakket dat het werken met metadata in een Matroskavideo mogelijk maakt.
type: docs
weight: 2480
url: /nl/net/groupdocs.metadata.formats.video/matroskarootpackage/
---
## MatroskaRootPackage class

Vertegenwoordigt het rootpakket dat het werken met metadata in een Matroska-video mogelijk maakt.

```csharp
public class MatroskaRootPackage : RootMetadataPackage
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Haalt het metadatapakket van het bestandstype op. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [MatroskaPackage](../../groupdocs.metadata.formats.video/matroskarootpackage/matroskapackage) { get; } | Haalt het Matroska-metadatapakket op. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Voegt bekende metadata-eigenschappen toe die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bepaalt of het pakket een metadata-eigenschap bevat met de opgegeven naam. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Zoekt de metadata-eigenschappen die voldoen aan het opgegeven predikaat. De zoekopdracht is recursief, dus het heeft ook invloed op alle geneste pakketten. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Retourneert een enumerator die de verzameling herhaalt. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Verwijdert beschrijfbare metadata-eigenschappen uit het pakket. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Opmerkingen

**Kom meer te weten**

* [Werken met metadata in Matroska (MKV) bestanden](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### Voorbeelden

Dit voorbeeld laat zien hoe ondertitels uit een MKV-video kunnen worden geëxtraheerd.

```csharp
using (Metadata metadata = new Metadata(Constants.MkvWithSubtitles))
{
    var root = metadata.GetRootPackage<MatroskaRootPackage>();

    foreach (var subtitleTrack in root.MatroskaPackage.SubtitleTracks)
    {
        Console.WriteLine(subtitleTrack.LanguageIetf ?? subtitleTrack.Language);
        foreach (MatroskaSubtitle subtitle in subtitleTrack.Subtitles)
        {
            Console.WriteLine("Timecode={0}, Duration={1}", subtitle.Timecode, subtitle.Duration);
            Console.WriteLine(subtitle.Text);
        }
    }
}
```

### Zie ook

* class [RootMetadataPackage](../../groupdocs.metadata.common/rootmetadatapackage)
* naamruimte [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
