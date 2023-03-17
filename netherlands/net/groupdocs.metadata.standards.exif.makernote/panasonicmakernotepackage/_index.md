---
title: PanasonicMakerNotePackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt PANASONIC MakerNotemetadata.
type: docs
weight: 2850
url: /nl/net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/
---
## PanasonicMakerNotePackage class

Vertegenwoordigt PANASONIC MakerNote-metadata.

```csharp
public class PanasonicMakerNotePackage : MakerNotePackage
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AccessorySerialNumber](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/accessoryserialnumber) { get; } | Haalt het serienummer van het accessoire op. |
| [AccessoryType](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/accessorytype) { get; } | Krijgt het type accessoire. |
| [AFMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/afmode) { get; } | Krijgt de AF-modus. |
| [Audio](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/audio) { get; } | Krijgt de audiomodus. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [FirmwareVersion](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/firmwareversion) { get; } | Haalt de firmwareversie op. |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/focusmode) { get; } | Krijgt de scherpstelmodus. |
| [ImageQuality](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/imagequality) { get; } | Krijgt de beeldkwaliteit. |
| [ImageStabilization](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/imagestabilization) { get; } | Krijgt de beeldstabilisatiemodus. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Haalt de TIFF-tag op met de opgegeven id. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [LensSerialNumber](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/lensserialnumber) { get; } | Haalt het serienummer van de lens op. |
| [LensType](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/lenstype) { get; } | Krijgt het type lens. |
| [MacroMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/macromode) { get; } | Krijgt de macromodus. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [ShootingMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/shootingmode) { get; } | Krijgt de opnamemodus. |
| [WhiteBalance](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/whitebalance) { get; } | Krijgt de witbalans. |

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

### Zie ook

* class [MakerNotePackage](../makernotepackage)
* naamruimte [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
