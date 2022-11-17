---
title: MatroskaSubtitleTrack
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar undertextmetadata i en Matroskavideo.
type: docs
weight: 2520
url: /sv/net/groupdocs.metadata.formats.video/matroskasubtitletrack/
---
## MatroskaSubtitleTrack class

Representerar undertextmetadata i en Matroska-video.

```csharp
public class MatroskaSubtitleTrack : MatroskaTrack
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CodecID](../../groupdocs.metadata.formats.video/matroskatrack/codecid) { get; } | Får ett ID som motsvarar codec. |
| [CodecName](../../groupdocs.metadata.formats.video/matroskatrack/codecname) { get; } | Får en läsbar sträng som anger codec. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [DefaultDuration](../../groupdocs.metadata.formats.video/matroskatrack/defaultduration) { get; } | Hämtar antalet nanosekunder (skalas inte via[`TimecodeScale`](../matroskasegment/timecodescale) ) per bildruta. |
| [FlagEnabled](../../groupdocs.metadata.formats.video/matroskatrack/flagenabled) { get; } | Hämtar den aktiverade flaggan, sant om spåret är användbart. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [Language](../../groupdocs.metadata.formats.video/matroskatrack/language) { get; } | Hämtar språket för spåret i formuläret Matroska-språk. Detta element MÅSTE ignoreras om[`LanguageIetf`](../matroskatrack/languageietf) Element används i samma TrackEntry. |
| [LanguageIetf](../../groupdocs.metadata.formats.video/matroskatrack/languageietf) { get; } | Hämtar språket för spåret enligt BCP 47 och med hjälp av IANA Language Subtag Registry. Om detta element används, då någon[`Language`](../matroskatrack/language) Element som används i samma TrackEntry MÅSTE ignoreras. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [Name](../../groupdocs.metadata.formats.video/matroskatrack/name) { get; } | Får det mänskliga läsbara spårnamnet. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [Subtitles](../../groupdocs.metadata.formats.video/matroskasubtitletrack/subtitles) { get; } | Hämtar undertexterna. |
| [TrackNumber](../../groupdocs.metadata.formats.video/matroskatrack/tracknumber) { get; } | Hämtar spårnumret som används i Block Header. Användning av fler än 127 spår uppmuntras inte, även om designen tillåter ett obegränsat antal. |
| [TrackType](../../groupdocs.metadata.formats.video/matroskatrack/tracktype) { get; } | Hämtar typen av spår. |
| [TrackUid](../../groupdocs.metadata.formats.video/matroskatrack/trackuid) { get; } | Får det unika ID:t för att identifiera spåret. Detta BÖR behållas när man gör en direktströmkopia av spåret till en annan fil. |

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

* class [MatroskaTrack](../matroskatrack)
* namnutrymme [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
