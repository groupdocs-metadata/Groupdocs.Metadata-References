---
title: ExifPackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt een EXIFmetadatapakket Exchangeable Image File Format.
type: docs
weight: 2790
url: /nl/net/groupdocs.metadata.standards.exif/exifpackage/
---
## ExifPackage class

Vertegenwoordigt een EXIF-metadatapakket (Exchangeable Image File Format).

```csharp
public class ExifPackage : ExifDictionaryBasePackage
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [ExifPackage](exifpackage)() | Initialiseert een nieuw exemplaar van het[`ExifPackage`](../exifpackage) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Artist](../../groupdocs.metadata.standards.exif/exifpackage/artist) { get; set; } | Haalt of stelt de naam in van de camera-eigenaar, fotograaf of beeldmaker. |
| [Copyright](../../groupdocs.metadata.standards.exif/exifpackage/copyright) { get; set; } | Krijgt of stelt de copyrightmelding in. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [DateTime](../../groupdocs.metadata.standards.exif/exifpackage/datetime) { get; set; } | Hiermee wordt de datum en tijd van het maken van de afbeelding opgehaald of ingesteld. In de EXIF-standaard is dit de datum en tijd waarop het bestand is gewijzigd. |
| [ExifIfdPackage](../../groupdocs.metadata.standards.exif/exifpackage/exififdpackage) { get; } | Haalt de EXIF IFD-gegevens op. |
| [GpsPackage](../../groupdocs.metadata.standards.exif/exifpackage/gpspackage) { get; } | Haalt de GPS-gegevens op. |
| [ImageDescription](../../groupdocs.metadata.standards.exif/exifpackage/imagedescription) { get; set; } | Hiermee wordt een tekenreeks opgehaald of ingesteld die de titel van de afbeelding geeft. Dit kan een opmerking zijn zoals "Bedrijfspicknick uit 1988" of iets dergelijks. |
| [ImageLength](../../groupdocs.metadata.standards.exif/exifpackage/imagelength) { get; set; } | Haalt het aantal rijen afbeeldingsgegevens op of stelt het in. |
| [ImageWidth](../../groupdocs.metadata.standards.exif/exifpackage/imagewidth) { get; set; } | Hiermee wordt het aantal kolommen met afbeeldingsgegevens opgehaald of ingesteld, gelijk aan het aantal pixels per rij. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Haalt de TIFF-tag op met de opgegeven id. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [Make](../../groupdocs.metadata.standards.exif/exifpackage/make) { get; set; } | Haalt of stelt de fabrikant van de opnameapparatuur in. Dit is de fabrikant van de DSC, scanner, videodigitalizer of andere apparatuur die het beeld heeft gegenereerd. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [Model](../../groupdocs.metadata.standards.exif/exifpackage/model) { get; set; } | Haalt de modelnaam of het modelnummer van de apparatuur op of stelt deze in. Dit is de modelnaam of het nummer van de DSC, scanner, videodigitizer of andere apparatuur die de afbeelding heeft gegenereerd. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [Software](../../groupdocs.metadata.standards.exif/exifpackage/software) { get; set; } | Haalt of stelt de naam en versie in van de software of firmware van de camera of het beeldinvoerapparaat dat wordt gebruikt om het beeld te genereren. |
| [Thumbnail](../../groupdocs.metadata.standards.exif/exifpackage/thumbnail) { get; } | Haalt de afbeeldingsminiatuur op die wordt weergegeven als een reeks bytes. |

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

### Voorbeelden

Dit codevoorbeeld laat zien hoe u algemene EXIF-eigenschappen bijwerkt.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        // Stel het EXIF-pakket in als het ontbreekt
        if (root.ExifPackage == null)
        {
            root.ExifPackage = new ExifPackage();
        }

        root.ExifPackage.Copyright = "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.";
        root.ExifPackage.ImageDescription = "test image";
        root.ExifPackage.Software = "GroupDocs.Metadata";

        // ...

        root.ExifPackage.ExifIfdPackage.BodySerialNumber = "test";
        root.ExifPackage.ExifIfdPackage.CameraOwnerName = "GroupDocs";
        root.ExifPackage.ExifIfdPackage.UserComment = "test comment";

        // ...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Zie ook

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* naamruimte [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
