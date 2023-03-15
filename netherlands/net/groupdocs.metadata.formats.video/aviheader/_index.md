---
title: AviHeader
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt de AVIMAINHEADERstructuur in een AVIvideo.
type: docs
weight: 2380
url: /nl/net/groupdocs.metadata.formats.video/aviheader/
---
## AviHeader class

Vertegenwoordigt de AVIMAINHEADER-structuur in een AVI-video.

```csharp
public sealed class AviHeader : CustomPackage
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [AviHeader](aviheader)() | Initialiseert een nieuw exemplaar van het[`AviHeader`](../aviheader) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AviHeaderFlags](../../groupdocs.metadata.formats.video/aviheader/aviheaderflags) { get; } | Krijgt een bitsgewijze combinatie van nul of meer van de AVI-vlaggen. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [Height](../../groupdocs.metadata.formats.video/aviheader/height) { get; } | Krijgt de hoogte van het AVI-bestand in pixels. |
| [InitialFrames](../../groupdocs.metadata.formats.video/aviheader/initialframes) { get; } | Haalt het eerste frame op voor interleaved bestanden.  Non-interleaved bestanden moeten nul specificeren. Als u interleaved-bestanden maakt, specificeert u het aantal frames in het bestand voorafgaand aan het eerste frame van de AVI-reeks in dit lid. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [MaxBytesPerSec](../../groupdocs.metadata.formats.video/aviheader/maxbytespersec) { get; } | Haalt de geschatte maximale gegevenssnelheid van het bestand op.  Deze waarde geeft het aantal bytes per seconde aan dat het systeem moet verwerken om een AVI-reeks als weer te geven, gespecificeerd door de andere parameters in de hoofdheader en streamheader-chunks. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [MicroSecPerFrame](../../groupdocs.metadata.formats.video/aviheader/microsecperframe) { get; } | Krijgt het aantal microseconden tussen frames. Deze waarde geeft de algehele timing voor het bestand aan. |
| [PaddingGranularity](../../groupdocs.metadata.formats.video/aviheader/paddinggranularity) { get; } | Haalt de uitlijning voor gegevens op, in bytes. Vul de gegevens in op veelvouden van deze waarde. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [Streams](../../groupdocs.metadata.formats.video/aviheader/streams) { get; } | Haalt het aantal streams in het bestand op. Een bestand met audio en video heeft bijvoorbeeld twee streams. |
| [SuggestedBufferSize](../../groupdocs.metadata.formats.video/aviheader/suggestedbuffersize) { get; } | Haalt de voorgestelde buffergrootte op voor het lezen van het bestand.  Over het algemeen zou deze grootte groot genoeg moeten zijn om het grootste deel van het bestand te bevatten. Indien ingesteld op nul, of als het te klein is, zal de afspeelsoftware tijdens het afspelen het geheugen opnieuw moeten toewijzen, wat de prestaties zal verminderen. Voor een interleaved bestand moet de buffergrootte groot genoeg zijn om een heel record te lezen, en niet slechts een deel. |
| [TotalFrames](../../groupdocs.metadata.formats.video/aviheader/totalframes) { get; } | Haalt het totale aantal frames met gegevens in het bestand op. |
| [Width](../../groupdocs.metadata.formats.video/aviheader/width) { get; } | Krijgt de breedte van het AVI-bestand in pixels. |

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

* [Werken met metadata in AVI-bestanden](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+AVI+files)

### Zie ook

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* naamruimte [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
