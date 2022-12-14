---
title: ID3V2TextFrame
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar en textram i enID3V2Tag./id3v2tag . Nästan alla bildrutor som börjar med Ttecknet faller inom denna kategori. Det finns bara ett undantag vilket är TXXXramen som representeras avID3V2UserDefinedFrame./id3v2userdefinedframe class.
type: docs
weight: 520
url: /sv/net/groupdocs.metadata.formats.audio/id3v2textframe/
---
## ID3V2TextFrame class

Representerar en textram i en[`ID3V2Tag`](../id3v2tag) . Nästan alla bildrutor som börjar med T-tecknet faller inom denna kategori. Det finns bara ett undantag, vilket är TXXX-ramen som representeras av[`ID3V2UserDefinedFrame`](../id3v2userdefinedframe) class.

```csharp
public class ID3V2TextFrame : ID3V2TagFrame
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ID3V2TextFrame](id3v2textframe)(string, ID3V2EncodingType, string) | Initierar en ny instans av[`ID3V2TextFrame`](../id3v2textframe) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [Data](../../groupdocs.metadata.formats.audio/id3v2tagframe/data) { get; } | Hämtar ramdata. |
| [Flags](../../groupdocs.metadata.formats.audio/id3v2tagframe/flags) { get; } | Hämtar ramflaggorna. |
| [Id](../../groupdocs.metadata.formats.audio/id3v2tagframe/id) { get; } | Hämtar id för ramen (fyra tecken som matchar mönstret [A-Z0-9]). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [Text](../../groupdocs.metadata.formats.audio/id3v2textframe/text) { get; } | Hämtar textvärdet. |
| [TextEncoding](../../groupdocs.metadata.formats.audio/id3v2textframe/textencoding) { get; } | Hämtar textkodningen. |

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

* [Hantera ID3v2-taggen](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Se även

* class [ID3V2TagFrame](../id3v2tagframe)
* namnutrymme [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
