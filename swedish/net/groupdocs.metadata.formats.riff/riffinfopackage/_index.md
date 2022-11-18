---
title: RiffInfoPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar metadatapaketet som innehåller egenskaper som extraherats från RIFF INFObiten.
type: docs
weight: 2220
url: /sv/net/groupdocs.metadata.formats.riff/riffinfopackage/
---
## RiffInfoPackage class

Representerar metadatapaketet som innehåller egenskaper som extraherats från RIFF INFO-biten.

```csharp
public sealed class RiffInfoPackage : CustomPackage
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Artist](../../groupdocs.metadata.formats.riff/riffinfopackage/artist) { get; } | Hämtar artisten av det ursprungliga ämnet för filen. |
| [Comment](../../groupdocs.metadata.formats.riff/riffinfopackage/comment) { get; } | Hämtar kommentaren om filen eller ämnet för filen. |
| [Copyright](../../groupdocs.metadata.formats.riff/riffinfopackage/copyright) { get; } | Hämtar upphovsrättsinformationen för filen. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [CreationDate](../../groupdocs.metadata.formats.riff/riffinfopackage/creationdate) { get; } | Hämtar datumet då ämnet för filen skapades. |
| [Engineer](../../groupdocs.metadata.formats.riff/riffinfopackage/engineer) { get; } | Hämtar namnet på ingenjören som arbetade med filen. |
| [Genre](../../groupdocs.metadata.formats.riff/riffinfopackage/genre) { get; } | Hämtar genren för originalverket. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [Keywords](../../groupdocs.metadata.formats.riff/riffinfopackage/keywords) { get; } | Hämtar nyckelorden som refererar till filen eller ämnet för filen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [Name](../../groupdocs.metadata.formats.riff/riffinfopackage/name) { get; } | Hämtar titeln på filens ämne. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [Software](../../groupdocs.metadata.formats.riff/riffinfopackage/software) { get; } | Hämtar namnet på mjukvarupaketet som används för att skapa filen. |
| [Source](../../groupdocs.metadata.formats.riff/riffinfopackage/source) { get; } | Hämtar namnet på den person eller organisation som tillhandahöll det ursprungliga ämnet för filen. |
| [Subject](../../groupdocs.metadata.formats.riff/riffinfopackage/subject) { get; } | Får en beskrivning av filens innehåll, till exempel "Aerial view of Seattle." |
| [Technician](../../groupdocs.metadata.formats.riff/riffinfopackage/technician) { get; } | Får teknikern som digitaliserade ämnesfilen. |

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

### Se även

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namnutrymme [GroupDocs.Metadata.Formats.Riff](../../groupdocs.metadata.formats.riff)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
