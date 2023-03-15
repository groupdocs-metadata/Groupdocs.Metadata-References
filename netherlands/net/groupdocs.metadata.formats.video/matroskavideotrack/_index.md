---
title: MatroskaVideoTrack
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt videometadata in een Matroskavideo.
type: docs
weight: 2610
url: /nl/net/groupdocs.metadata.formats.video/matroskavideotrack/
---
## MatroskaVideoTrack class

Vertegenwoordigt videometadata in een Matroska-video.

```csharp
public class MatroskaVideoTrack : MatroskaTrack
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlphaMode](../../groupdocs.metadata.formats.video/matroskavideotrack/alphamode) { get; } | Krijgt de alfa-videomodus. Aanwezigheid van dit element geeft aan dat het BlockAdditional-element alfagegevens kan bevatten. |
| [CodecID](../../groupdocs.metadata.formats.video/matroskatrack/codecid) { get; } | Krijgt een ID die overeenkomt met de codec. |
| [CodecName](../../groupdocs.metadata.formats.video/matroskatrack/codecname) { get; } | Haalt een door mensen leesbare string op die de codec specificeert. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [DefaultDuration](../../groupdocs.metadata.formats.video/matroskatrack/defaultduration) { get; } | Krijgt het aantal nanoseconden (niet geschaald via[`TimecodeScale`](../matroskasegment/timecodescale) ) per frame. |
| [DisplayHeight](../../groupdocs.metadata.formats.video/matroskavideotrack/displayheight) { get; } | Haalt de hoogte op van de weer te geven videoframes. Is van toepassing op het videoframe na bijsnijden (PixelCrop* Elements). |
| [DisplayUnit](../../groupdocs.metadata.formats.video/matroskavideotrack/displayunit) { get; } | Krijgt het hoe[`DisplayWidth`](./displaywidth) En[`DisplayHeight`](./displayheight) worden geïnterpreteerd. |
| [DisplayWidth](../../groupdocs.metadata.formats.video/matroskavideotrack/displaywidth) { get; } | Haalt de breedte op van de weer te geven videoframes. Is van toepassing op het videoframe na bijsnijden (PixelCrop* Elements). |
| [FieldOrder](../../groupdocs.metadata.formats.video/matroskavideotrack/fieldorder) { get; } | Gets declareert de veldvolgorde van de video. Als FlagInterlaced niet is ingesteld op 1, MOET dit element worden genegeerd. |
| [FlagEnabled](../../groupdocs.metadata.formats.video/matroskatrack/flagenabled) { get; } | Krijgt de ingeschakelde vlag, waar als de track bruikbaar is. |
| [FlagInterlaced](../../groupdocs.metadata.formats.video/matroskavideotrack/flaginterlaced) { get; } | Krijgt een markering om aan te geven of de video progressief of geïnterlinieerd is en, indien van toepassing, om details over de interliniëring aan te geven. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [Language](../../groupdocs.metadata.formats.video/matroskatrack/language) { get; } | Krijgt de taal van de track in de Matroska-taalvorm. Dit element MOET worden genegeerd als de[`LanguageIetf`](../matroskatrack/languageietf) Element wordt gebruikt in dezelfde TrackEntry. |
| [LanguageIetf](../../groupdocs.metadata.formats.video/matroskatrack/languageietf) { get; } | Haalt de taal van de track op volgens BCP 47 en met behulp van de IANA Language Subtag Registry. Als dit element wordt gebruikt, dan is any[`Language`](../matroskatrack/language) Elementen die in dezelfde TrackEntry worden gebruikt, MOETEN worden genegeerd. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [Name](../../groupdocs.metadata.formats.video/matroskatrack/name) { get; } | Krijgt de voor mensen leesbare tracknaam. |
| [PixelCropBottom](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropbottom) { get; } | Haalt het aantal videopixels op dat onderaan de afbeelding moet worden verwijderd. |
| [PixelCropLeft](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropleft) { get; } | Haalt het aantal videopixels op dat aan de linkerkant van de afbeelding moet worden verwijderd. |
| [PixelCropRight](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropright) { get; } | Haalt het aantal videopixels op dat aan de rechterkant van de afbeelding moet worden verwijderd. |
| [PixelCropTop](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcroptop) { get; } | Haalt het aantal videopixels op dat bovenaan de afbeelding moet worden verwijderd. |
| [PixelHeight](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelheight) { get; } | Krijgt de hoogte van de gecodeerde videoframes in pixels. |
| [PixelWidth](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelwidth) { get; } | Krijgt de breedte van de gecodeerde videoframes in pixels. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [StereoMode](../../groupdocs.metadata.formats.video/matroskavideotrack/stereomode) { get; } | Krijgt de stereo-3D-videomodus. |
| [TrackNumber](../../groupdocs.metadata.formats.video/matroskatrack/tracknumber) { get; } | Krijgt het tracknummer zoals gebruikt in de Block Header. Het gebruik van meer dan 127 tracks wordt niet aangemoedigd, hoewel het ontwerp een onbeperkt aantal toestaat. |
| [TrackType](../../groupdocs.metadata.formats.video/matroskatrack/tracktype) { get; } | Haalt het type track op. |
| [TrackUid](../../groupdocs.metadata.formats.video/matroskatrack/trackuid) { get; } | Krijgt de unieke ID om de track te identificeren. Dit MOET hetzelfde blijven wanneer een directe streamkopie van de track naar een ander bestand wordt gemaakt. |

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

* [Werken met metadata in Matroska (MKV) bestanden](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### Zie ook

* class [MatroskaTrack](../matroskatrack)
* naamruimte [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
