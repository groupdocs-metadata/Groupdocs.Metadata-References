---
title: PsdLayer
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt een laag in een PSDbestand.
type: docs
weight: 1900
url: /nl/net/groupdocs.metadata.formats.image/psdlayer/
---
## PsdLayer class

Vertegenwoordigt een laag in een PSD-bestand.

```csharp
public sealed class PsdLayer : CustomPackage
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BitsPerPixel](../../groupdocs.metadata.formats.image/psdlayer/bitsperpixel) { get; } | Haalt de bits per pixelwaarde op. |
| [Bottom](../../groupdocs.metadata.formats.image/psdlayer/bottom) { get; } | Haalt de positie van de onderste laag op. |
| [ChannelCount](../../groupdocs.metadata.formats.image/psdlayer/channelcount) { get; } | Haalt het aantal kanalen op. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [Flags](../../groupdocs.metadata.formats.image/psdlayer/flags) { get; } | Haalt de laagvlaggen op. |
| [Height](../../groupdocs.metadata.formats.image/psdlayer/height) { get; } | Krijgt de hoogte. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [Left](../../groupdocs.metadata.formats.image/psdlayer/left) { get; } | Krijgt de positie van de linkerlaag. |
| [Length](../../groupdocs.metadata.formats.image/psdlayer/length) { get; } | Krijgt de totale lengte van de laag in bytes. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [Name](../../groupdocs.metadata.formats.image/psdlayer/name) { get; } | Krijgt de naam van de laag. |
| [Opacity](../../groupdocs.metadata.formats.image/psdlayer/opacity) { get; } | Krijgt de laagdekking. 0 = transparant, 255 = ondoorzichtig. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [Right](../../groupdocs.metadata.formats.image/psdlayer/right) { get; } | Krijgt de juiste laagpositie. |
| [Top](../../groupdocs.metadata.formats.image/psdlayer/top) { get; } | Krijgt de positie van de bovenste laag. |
| [Width](../../groupdocs.metadata.formats.image/psdlayer/width) { get; } | Haalt de breedte op. |

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

* [Werken met metadata in PSD-afbeeldingen](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PSD+images)

### Zie ook

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* naamruimte [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
