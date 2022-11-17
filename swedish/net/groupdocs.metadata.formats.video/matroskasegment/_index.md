---
title: MatroskaSegment
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar ett SEGMENTINFOelement som innehåller allmän information om SEGMENTET i en Matroskavideo.
type: docs
weight: 2490
url: /sv/net/groupdocs.metadata.formats.video/matroskasegment/
---
## MatroskaSegment class

Representerar ett SEGMENTINFO-element som innehåller allmän information om SEGMENTET i en Matroska-video.

```csharp
public class MatroskaSegment : MatroskaBasePackage
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [DateUtc](../../groupdocs.metadata.formats.video/matroskasegment/dateutc) { get; } | Hämtar datum och tid då segmentet skapades av muxing-applikationen eller biblioteket. |
| [Duration](../../groupdocs.metadata.formats.video/matroskasegment/duration) { get; } | Hämtar varaktigheten för SEGMENTET. Se[`TimecodeScale`](./timecodescale) för mer information. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [MuxingApp](../../groupdocs.metadata.formats.video/matroskasegment/muxingapp) { get; } | Får hela namnet på applikationen eller biblioteket följt av versionsnumret. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [ScaledDuration](../../groupdocs.metadata.formats.video/matroskasegment/scaledduration) { get; } | Hämtar den skalade varaktigheten för SEGMENTET. |
| [SegmentFilename](../../groupdocs.metadata.formats.video/matroskasegment/segmentfilename) { get; } | Hämtar filnamnet som motsvarar detta segment. |
| [SegmentUid](../../groupdocs.metadata.formats.video/matroskasegment/segmentuid) { get; } | Får det unika 128-bitarsnumret som identifierar ett SEGMENT. Uppenbarligen kan en fil endast refereras till av en annan fil om ett SEGMENTUID finns, men uppspelning är möjlig utan det UID. |
| [TimecodeScale](../../groupdocs.metadata.formats.video/matroskasegment/timecodescale) { get; } | Hämtar tidskodens skalvärde. Varje skalad tidskod i en MATROSKA-fil multipliceras med TIMECODESCALE för att erhålla tidskoden i nanosekunder. Observera att inte alla tidskoder skalas! |
| [Title](../../groupdocs.metadata.formats.video/matroskasegment/title) { get; } | Hämtar det allmänna namnet på segmentet. |
| [WritingApp](../../groupdocs.metadata.formats.video/matroskasegment/writingapp) { get; } | Får programmets fullständiga namn följt av versionsnumret. |

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

* [Arbeta med metadata i Matroska (MKV) filer](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### Se även

* class [MatroskaBasePackage](../matroskabasepackage)
* namnutrymme [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
