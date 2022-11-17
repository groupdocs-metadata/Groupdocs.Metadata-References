---
title: PsdLayer
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar ett lager i en PSDfil.
type: docs
weight: 1900
url: /sv/net/groupdocs.metadata.formats.image/psdlayer/
---
## PsdLayer class

Representerar ett lager i en PSD-fil.

```csharp
public sealed class PsdLayer : CustomPackage
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BitsPerPixel](../../groupdocs.metadata.formats.image/psdlayer/bitsperpixel) { get; } | Hämtar värdet för bitar per pixel. |
| [Bottom](../../groupdocs.metadata.formats.image/psdlayer/bottom) { get; } | Får bottenlagerpositionen. |
| [ChannelCount](../../groupdocs.metadata.formats.image/psdlayer/channelcount) { get; } | Hämtar antalet kanaler. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [Flags](../../groupdocs.metadata.formats.image/psdlayer/flags) { get; } | Hämtar lagerflaggorna. |
| [Height](../../groupdocs.metadata.formats.image/psdlayer/height) { get; } | Får höjden. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [Left](../../groupdocs.metadata.formats.image/psdlayer/left) { get; } | Får vänster lagerposition. |
| [Length](../../groupdocs.metadata.formats.image/psdlayer/length) { get; } | Får den totala lagerlängden i byte. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [Name](../../groupdocs.metadata.formats.image/psdlayer/name) { get; } | Hämtar lagrets namn. |
| [Opacity](../../groupdocs.metadata.formats.image/psdlayer/opacity) { get; } | Får lagrets opacitet. 0 = transparent, 255 = ogenomskinlig. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [Right](../../groupdocs.metadata.formats.image/psdlayer/right) { get; } | Får rätt lagerposition. |
| [Top](../../groupdocs.metadata.formats.image/psdlayer/top) { get; } | Får det översta lagrets position. |
| [Width](../../groupdocs.metadata.formats.image/psdlayer/width) { get; } | Hämtar bredden. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Lägger till kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar även alla kapslade paket. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestämmer om paketet innehåller en metadataegenskap med det angivna namnet. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Hittar metadataegenskaperna som uppfyller det angivna predikatet. Sökningen är rekursiv så den påverkar också alla kapslade paket. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Tar bort metadataegenskaper som uppfyller det angivna predikatet. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Tar bort skrivbara metadataegenskaper från paketet. Operationen är rekursiv så den påverkar alla kapslade paket också. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Anmärkningar

**Läs mer**

* [Arbeta med metadata i PSD-bilder](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PSD+images)

### Se även

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namnutrymme [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
