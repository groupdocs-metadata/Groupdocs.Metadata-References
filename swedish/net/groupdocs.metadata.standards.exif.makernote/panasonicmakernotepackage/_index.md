---
title: PanasonicMakerNotePackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar PANASONIC MakerNotemetadata.
type: docs
weight: 2850
url: /sv/net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/
---
## PanasonicMakerNotePackage class

Representerar PANASONIC MakerNote-metadata.

```csharp
public class PanasonicMakerNotePackage : MakerNotePackage
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AccessorySerialNumber](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/accessoryserialnumber) { get; } | Får tillbehörets serienummer. |
| [AccessoryType](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/accessorytype) { get; } | Hämtar typen av tillbehör. |
| [AFMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/afmode) { get; } | Hämtar AF-läget. |
| [Audio](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/audio) { get; } | Hämtar ljudläget. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [FirmwareVersion](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/firmwareversion) { get; } | Hämtar firmwareversionen. |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/focusmode) { get; } | Får fokusläget. |
| [ImageQuality](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/imagequality) { get; } | Får bildkvaliteten. |
| [ImageStabilization](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/imagestabilization) { get; } | Får bildstabiliseringsläget. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Hämtar TIFF-taggen med angivet id. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [LensSerialNumber](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/lensserialnumber) { get; } | Hämtar linsens serienummer. |
| [LensType](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/lenstype) { get; } | Hämtar typen av lins. |
| [MacroMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/macromode) { get; } | Hämtar makroläget. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [ShootingMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/shootingmode) { get; } | Hämtar fotograferingsläget. |
| [WhiteBalance](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/whitebalance) { get; } | Får vitbalansen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Lägger till kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar även alla kapslade paket. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Tar bort alla TIFF-taggar som är lagrade i paketet. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestämmer om paketet innehåller en metadataegenskap med det angivna namnet. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Hittar metadataegenskaperna som uppfyller det angivna predikatet. Sökningen är rekursiv så den påverkar också alla kapslade paket. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Tar bort egenskapen med angivet id. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Tar bort metadataegenskaper som uppfyller det angivna predikatet. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Tar bort skrivbara metadataegenskaper från paketet. Operationen är rekursiv så den påverkar alla kapslade paket också. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Lägger till eller ersätter den angivna taggen. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Skapar en lista från paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Se även

* class [MakerNotePackage](../makernotepackage)
* namnutrymme [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
