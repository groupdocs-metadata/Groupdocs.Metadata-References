---
title: ExifIfdPackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt de Exif Image File Directory. Exif IFD is een set tags voor het vastleggen van Exifspecifieke attribuutinformatie.
type: docs
weight: 2780
url: /nl/net/groupdocs.metadata.standards.exif/exififdpackage/
---
## ExifIfdPackage class

Vertegenwoordigt de Exif Image File Directory. Exif IFD is een set tags voor het vastleggen van Exif-specifieke attribuutinformatie.

```csharp
public sealed class ExifIfdPackage : ExifDictionaryBasePackage
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BodySerialNumber](../../groupdocs.metadata.standards.exif/exififdpackage/bodyserialnumber) { get; set; } | Haalt of stelt het serienummer van de camerabody in. |
| [CameraOwnerName](../../groupdocs.metadata.standards.exif/exififdpackage/cameraownername) { get; set; } | Krijgt of stelt de naam van de camera-eigenaar in. |
| [CfaPattern](../../groupdocs.metadata.standards.exif/exififdpackage/cfapattern) { get; set; } | Hiermee wordt het geometrische patroon van de kleurfilterarray (CFA) van de beeldsensor opgehaald of ingesteld wanneer een kleurgebiedsensor met één chip wordt gebruikt. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Haalt de TIFF-tag op met de opgegeven id. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [UserComment](../../groupdocs.metadata.standards.exif/exififdpackage/usercomment) { get; set; } | Krijgt of stelt de opmerking van de gebruiker in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Voegt bekende metadata-eigenschappen toe die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Verwijdert alle TIFF-tags die in het pakket zijn opgeslagen. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bepaalt of het pakket een metadata-eigenschap bevat met de opgegeven naam. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Zoekt de metadata-eigenschappen die voldoen aan het opgegeven predikaat. De zoekopdracht is recursief, dus het heeft ook invloed op alle geneste pakketten. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Retourneert een enumerator die de verzameling herhaalt. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Verwijdert de eigenschap met de opgegeven id. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Verwijdert beschrijfbare metadata-eigenschappen uit het pakket. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Voegt de opgegeven tag toe of vervangt deze. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Maakt een lijst van het pakket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Opmerkingen

**Kom meer te weten**

* [Werken met EXIF-metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Zie ook

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* naamruimte [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
