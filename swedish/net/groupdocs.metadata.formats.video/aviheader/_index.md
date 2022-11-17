---
title: AviHeader
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar AVIMAINHEADERstrukturen i en AVIvideo.
type: docs
weight: 2380
url: /sv/net/groupdocs.metadata.formats.video/aviheader/
---
## AviHeader class

Representerar AVIMAINHEADER-strukturen i en AVI-video.

```csharp
public sealed class AviHeader : CustomPackage
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [AviHeader](aviheader)() | Initierar en ny instans av[`AviHeader`](../aviheader) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AviHeaderFlags](../../groupdocs.metadata.formats.video/aviheader/aviheaderflags) { get; } | Får en bitvis kombination av noll eller fler av AVI-flaggorna. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [Height](../../groupdocs.metadata.formats.video/aviheader/height) { get; } | Hämtar höjden på AVI-filen i pixlar. |
| [InitialFrames](../../groupdocs.metadata.formats.video/aviheader/initialframes) { get; } | Hämtar den initiala ramen för interfolierade filer.  Icke-interfolierade filer bör ange noll. Om du skapar interfolierade filer, ange antalet ramar i filen före den initiala ramen för AVI-sekvensen i den här medlemmen. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MaxBytesPerSec](../../groupdocs.metadata.formats.video/aviheader/maxbytespersec) { get; } | Får den ungefärliga maximala datahastigheten för filen.  Det här värdet indikerar antalet byte per sekund som systemet måste hantera för att presentera en AVI-sekvens som specificerad av de andra parametrarna som finns i huvudhuvudet och strömhuvudet. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [MicroSecPerFrame](../../groupdocs.metadata.formats.video/aviheader/microsecperframe) { get; } | Hämtar antalet mikrosekunder mellan bildrutor. Detta värde indikerar den övergripande timingen för filen. |
| [PaddingGranularity](../../groupdocs.metadata.formats.video/aviheader/paddinggranularity) { get; } | Hämtar justeringen för data, i byte. Fyll på data till multiplar av detta värde. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [Streams](../../groupdocs.metadata.formats.video/aviheader/streams) { get; } | Hämtar antalet strömmar i filen. Till exempel har en fil med ljud och video två strömmar. |
| [SuggestedBufferSize](../../groupdocs.metadata.formats.video/aviheader/suggestedbuffersize) { get; } | Hämtar den föreslagna buffertstorleken för att läsa filen.  I allmänhet bör denna storlek vara tillräckligt stor för att innehålla den största biten i filen. Om den är inställd på noll, eller om den är för liten, måste uppspelningsmjukvaran omfördela minne under uppspelning, vilket kommer att minska prestandan. För en interfolierad fil, bör buffertstorleken vara tillräckligt stor för att läsa en hel post, och inte bara en bit. |
| [TotalFrames](../../groupdocs.metadata.formats.video/aviheader/totalframes) { get; } | Hämtar det totala antalet ramar med data i filen. |
| [Width](../../groupdocs.metadata.formats.video/aviheader/width) { get; } | Hämtar AVI-filens bredd i pixlar. |

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

* [Arbeta med metadata i AVI-filer](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+AVI+files)

### Se även

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namnutrymme [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
