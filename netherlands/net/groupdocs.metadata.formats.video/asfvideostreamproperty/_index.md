---
title: AsfVideoStreamProperty
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt metadata van videostreameigenschappen in de ASFmediacontainer.
type: docs
weight: 2370
url: /nl/net/groupdocs.metadata.formats.video/asfvideostreamproperty/
---
## AsfVideoStreamProperty class

Vertegenwoordigt metadata van videostreameigenschappen in de ASF-mediacontainer.

```csharp
public class AsfVideoStreamProperty : AsfBaseStreamProperty
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternateBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/alternatebitrate) { get; } | Haalt de leksnelheid RAlt op, in bits per seconde, van een lekkende bucket die het gegevensgedeelte van de stream bevat zonder te overlopen, exclusief alle overhead van ASF-gegevenspakketten. |
| [AverageBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagebitrate) { get; } | Haalt de gemiddelde bitsnelheid op. |
| [AverageTimePerFrame](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagetimeperframe) { get; } | Haalt de gemiddelde tijdsduur op, gemeten in eenheden van 100 nanoseconden, van elk frame. |
| [Bitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/bitrate) { get; } | Haalt de leksnelheid R op, in bits per seconde, van een lekkende bucket die het gegevensgedeelte van de stream bevat zonder te overlopen, exclusief alle overhead van ASF-gegevenspakketten. |
| [BitsPerPixels](../../groupdocs.metadata.formats.video/asfvideostreamproperty/bitsperpixels) { get; } | Haalt de bits per pixel op. |
| [Compression](../../groupdocs.metadata.formats.video/asfvideostreamproperty/compression) { get; } | Haalt de videocompressie-id. op |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [EndTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/endtime) { get; } | Krijgt de presentatietijd van het laatste object plus de duur van het afspelen, wat aangeeft waar deze digitale mediastream eindigt binnen de context van de tijdlijn van het ASF-bestand als geheel. |
| [Flags](../../groupdocs.metadata.formats.video/asfbasestreamproperty/flags) { get; } | Krijgt de vlaggen. |
| [ImageHeight](../../groupdocs.metadata.formats.video/asfvideostreamproperty/imageheight) { get; } | Krijgt de hoogte van de gecodeerde afbeelding in pixels. |
| [ImageWidth](../../groupdocs.metadata.formats.video/asfvideostreamproperty/imagewidth) { get; } | Krijgt de breedte van de gecodeerde afbeelding in pixels. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [Language](../../groupdocs.metadata.formats.video/asfbasestreamproperty/language) { get; } | Haalt de streamtaal op. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [StartTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/starttime) { get; } | Krijgt de presentatietijd van het eerste object, waarmee wordt aangegeven waar deze digitale mediastream begint binnen de context van de tijdlijn van het ASF-bestand als geheel. |
| [StreamNumber](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamnumber) { get; } | Krijgt het nummer van deze stream. |
| [StreamType](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamtype) { get; } | Krijgt het type van deze stream. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Voegt bekende metadata-eigenschappen toe die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bepaalt of het pakket een metadata-eigenschap bevat met de opgegeven naam. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Zoekt de metadata-eigenschappen die voldoen aan het opgegeven predikaat. De zoekopdracht is recursief, dus het heeft ook invloed op alle geneste pakketten. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Retourneert een enumerator die de verzameling herhaalt. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Verwijdert beschrijfbare metadata-eigenschappen uit het pakket. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Opmerkingen

**Kom meer te weten**

* [Werken met metagegevens in ASF-bestanden](https://docs.groupdocs.com/display/metadatanet/Working+with+Metadata+in+ASF+Files)

### Zie ook

* class [AsfBaseStreamProperty](../asfbasestreamproperty)
* naamruimte [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
