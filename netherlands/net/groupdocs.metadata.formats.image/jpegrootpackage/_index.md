---
title: JpegRootPackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt het rootpakket dat het werken met metadata in een JPEGafbeelding mogelijk maakt.
type: docs
weight: 1810
url: /nl/net/groupdocs.metadata.formats.image/jpegrootpackage/
---
## JpegRootPackage class

Vertegenwoordigt het rootpakket dat het werken met metadata in een JPEG-afbeelding mogelijk maakt.

```csharp
public class JpegRootPackage : ImageRootPackage, IExif, IIptc, IXmp
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [ExifPackage](../../groupdocs.metadata.formats.image/jpegrootpackage/exifpackage) { get; set; } | Haalt het EXIF-metadatapakket op of stelt het in. |
| [FileType](../../groupdocs.metadata.formats.image/imagerootpackage/filetype) { get; } | Haalt het metadatapakket van het bestandstype op. (2 properties) |
| [ImageResourcePackage](../../groupdocs.metadata.formats.image/jpegrootpackage/imageresourcepackage) { get; } | Krijgt het Photoshop Image Resource-metadatapakket. Afbeeldingsresourceblokken zijn de basisbouweenheid van de native bestandsindeling van Photoshop. |
| [IptcPackage](../../groupdocs.metadata.formats.image/jpegrootpackage/iptcpackage) { get; set; } | Haalt het IPTC-metadatapakket op of stelt het in. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [MakerNotePackage](../../groupdocs.metadata.formats.image/jpegrootpackage/makernotepackage) { get; } | Haalt het MakerNote-metadatapakket op of stelt het in. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [XmpPackage](../../groupdocs.metadata.formats.image/jpegrootpackage/xmppackage) { get; set; } | Haalt het XMP-metadatapakket op of stelt het in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Voegt bekende metadata-eigenschappen toe die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bepaalt of het pakket een metadata-eigenschap bevat met de opgegeven naam. |
| [DetectBarcodeTypes](../../groupdocs.metadata.formats.image/jpegrootpackage/detectbarcodetypes)() | Extraheert de typen streepjescodes die in de afbeelding worden weergegeven. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Zoekt de metadata-eigenschappen die voldoen aan het opgegeven predikaat. De zoekopdracht is recursief, dus het heeft ook invloed op alle geneste pakketten. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Retourneert een enumerator die de verzameling herhaalt. |
| [RemoveImageResourcePackage](../../groupdocs.metadata.formats.image/jpegrootpackage/removeimageresourcepackage)() | Verwijdert metadatapakket Photoshop Image Resource. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat. |
| override [Sanitize](../../groupdocs.metadata.formats.image/jpegrootpackage/sanitize)() | Verwijdert beschrijfbare metadata-eigenschappen uit het pakket. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Opmerkingen

**Kom meer te weten**

* [Werken met metadata in JPEG-afbeeldingen](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG+images)
* [Werken met EXIF-metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)
* [Werken met XMP-metagegevens](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)
* [Werken met IPTC IIM-metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Zie ook

* class [ImageRootPackage](../imagerootpackage)
* interface [IExif](../../groupdocs.metadata.standards.exif/iexif)
* interface [IIptc](../../groupdocs.metadata.standards.iptc/iiptc)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* naamruimte [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
