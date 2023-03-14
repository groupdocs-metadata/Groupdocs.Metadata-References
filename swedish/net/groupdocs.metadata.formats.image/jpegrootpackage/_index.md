---
title: JpegRootPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar rotpaketet som tillåter arbete med metadata i en JPEGbild.
type: docs
weight: 1810
url: /sv/net/groupdocs.metadata.formats.image/jpegrootpackage/
---
## JpegRootPackage class

Representerar rotpaketet som tillåter arbete med metadata i en JPEG-bild.

```csharp
public class JpegRootPackage : ImageRootPackage, IExif, IIptc, IXmp
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [ExifPackage](../../groupdocs.metadata.formats.image/jpegrootpackage/exifpackage) { get; set; } | Hämtar eller ställer in EXIF-metadatapaketet. |
| [FileType](../../groupdocs.metadata.formats.image/imagerootpackage/filetype) { get; } | Hämtar filtypens metadatapaket. (2 properties) |
| [ImageResourcePackage](../../groupdocs.metadata.formats.image/jpegrootpackage/imageresourcepackage) { get; } | Får metadatapaketet Photoshop Image Resource. Bildresursblock är den grundläggande byggnadsenheten i Photoshops ursprungliga filformat. |
| [IptcPackage](../../groupdocs.metadata.formats.image/jpegrootpackage/iptcpackage) { get; set; } | Hämtar eller ställer in IPTC-metadatapaketet. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MakerNotePackage](../../groupdocs.metadata.formats.image/jpegrootpackage/makernotepackage) { get; } | Hämtar eller ställer in metadatapaketet MakerNote. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [XmpPackage](../../groupdocs.metadata.formats.image/jpegrootpackage/xmppackage) { get; set; } | Hämtar eller ställer in XMP-metadatapaketet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Lägger till kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar även alla kapslade paket. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestämmer om paketet innehåller en metadataegenskap med det angivna namnet. |
| [DetectBarcodeTypes](../../groupdocs.metadata.formats.image/jpegrootpackage/detectbarcodetypes)() | Extraherar typerna av streckkoder som visas i bilden. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Hittar metadataegenskaperna som uppfyller det angivna predikatet. Sökningen är rekursiv så den påverkar också alla kapslade paket. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| [RemoveImageResourcePackage](../../groupdocs.metadata.formats.image/jpegrootpackage/removeimageresourcepackage)() | Tar bort Photoshop Image Resource metadatapaket. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Tar bort metadataegenskaper som uppfyller det angivna predikatet. |
| override [Sanitize](../../groupdocs.metadata.formats.image/jpegrootpackage/sanitize)() | Tar bort skrivbara metadataegenskaper från paketet. Operationen är rekursiv så den påverkar alla kapslade paket också. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Anmärkningar

**Läs mer**

* [Arbeta med metadata i JPEG-bilder](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG+images)
* [Arbeta med EXIF-metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)
* [Arbeta med XMP-metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)
* [Arbeta med IPTC IIM-metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Se även

* class [ImageRootPackage](../imagerootpackage)
* interface [IExif](../../groupdocs.metadata.standards.exif/iexif)
* interface [IIptc](../../groupdocs.metadata.standards.iptc/iiptc)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* namnutrymme [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->