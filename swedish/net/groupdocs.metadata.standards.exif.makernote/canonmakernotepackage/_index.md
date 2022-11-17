---
title: CanonMakerNotePackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar CANON MakerNotemetadata.
type: docs
weight: 2820
url: /sv/net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/
---
## CanonMakerNotePackage class

Representerar CANON MakerNote-metadata.

```csharp
public sealed class CanonMakerNotePackage : MakerNotePackage
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CameraSettings](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/camerasettings) { get; } | Hämtar kamerainställningarna. |
| [CanonFileLength](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/canonfilelength) { get; } | Hämtar längden på kanonfilen. |
| [CanonFirmwareVersion](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/canonfirmwareversion) { get; } | Hämtar canon firmwareversion. |
| [CanonImageType](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/canonimagetype) { get; } | Får bildtypen Canon. |
| [CanonModelID](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/canonmodelid) { get; } | Hämtar kanonmodellens identifierare. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [FileNumber](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/filenumber) { get; } | Hämtar filnumret. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Hämtar TIFF-taggen med angivet id. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [OwnerName](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/ownername) { get; } | Hämtar namnet på ägaren. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [SerialNumber](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/serialnumber) { get; } | Hämtar serienumret. |

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
