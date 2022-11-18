---
title: DiagramPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar ett inbyggt metadatapaket i ett diagramformat.
type: docs
weight: 890
url: /sv/net/groupdocs.metadata.formats.document/diagrampackage/
---
## DiagramPackage class

Representerar ett inbyggt metadatapaket i ett diagramformat.

```csharp
public class DiagramPackage : DocumentPackage
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AlternateNames](../../groupdocs.metadata.formats.document/diagrampackage/alternatenames) { get; set; } | Hämtar eller ställer in alternativa namn för dokumentet. Kan endast uppdateras i VDX- och VSX-format. |
| [BuildNumberCreated](../../groupdocs.metadata.formats.document/diagrampackage/buildnumbercreated) { get; } | Hämtar hela byggnumret för den instans som användes för att skapa dokumentet. |
| [BuildNumberEdited](../../groupdocs.metadata.formats.document/diagrampackage/buildnumberedited) { get; } | Hämtar byggnumret för den instans som senast användes för att redigera dokumentet. |
| [Category](../../groupdocs.metadata.formats.document/diagrampackage/category) { get; set; } | Hämtar eller ställer in den beskrivande texten för ritningstypen, såsom flödesschema eller kontorslayout. Denna text kan också skrivas in i Microsoft Visios användargränssnitt i rutan Kategori i dialogrutan Egenskaper. |
| [Company](../../groupdocs.metadata.formats.document/diagrampackage/company) { get; set; } | Hämtar eller ställer in användarinmatad information som identifierar företaget som skapar ritningen eller företaget som ritningen skapas för. Maximal längd är 63 tecken. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [Creator](../../groupdocs.metadata.formats.document/diagrampackage/creator) { get; set; } | Hämtar eller ställer in personen som skapade eller senast uppdaterade filen. Maximal längd är 63 tecken.. |
| [Description](../../groupdocs.metadata.formats.document/diagrampackage/description) { get; set; } | Hämtar eller ställer in en beskrivande textsträng för dokumentet. Använd det här elementet för att lagra viktig information om dokumentet, såsom dess syfte, senaste ändringar eller väntande ändringar. Maximalt är 191 tecken. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/diagrampackage/hyperlinkbase) { get; set; } | Hämtar eller ställer in sökvägen som ska användas för relativa hyperlänkar (hyperlänkar för vilka den länkade filplatsen beskrivs i relation till Microsoft Visio-diagrammet). Som standard är en hyperlänkssökväg relativ till det aktuella dokumentet om inte en annan sökväg anges i detta element. Maximal längd är 256 tecken. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [Keywords](../../groupdocs.metadata.formats.document/diagrampackage/keywords) { get; set; } | Hämtar eller ställer in en textsträng som identifierar ämnen eller annan viktig information om filen, såsom projektnamn, klientnamn eller versionsnummer. Den maximala stränglängden är 63 tecken. |
| [Language](../../groupdocs.metadata.formats.document/diagrampackage/language) { get; set; } | Hämtar eller ställer in språket för dokumentet. Kan endast uppdateras i VSD- och VSDX-format. |
| [Manager](../../groupdocs.metadata.formats.document/diagrampackage/manager) { get; set; } | Hämtar eller ställer in en användarinmatad textsträng som identifierar personen som är ansvarig för projektet eller avdelningen. Maximal längd är 63 tecken. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [PreviewPicture](../../groupdocs.metadata.formats.document/diagrampackage/previewpicture) { get; set; } | Hämtar eller ställer in förhandsgranskningsbilden. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [Subject](../../groupdocs.metadata.formats.document/diagrampackage/subject) { get; set; } | Hämtar eller ställer in en användardefinierad textsträng som beskriver innehållet i dokumentet. Maximal längd är 63 tecken. |
| [Template](../../groupdocs.metadata.formats.document/diagrampackage/template) { get; set; } | Hämtar eller ställer in ett strängvärde som anger filnamnet på mallen från vilken dokumentet skapades. |
| [TimeCreated](../../groupdocs.metadata.formats.document/diagrampackage/timecreated) { get; set; } | Hämtar eller ställer in ett datum- och tidsvärde som anger när dokumentet skapades. |
| [TimeEdited](../../groupdocs.metadata.formats.document/diagrampackage/timeedited) { get; } | Får ett datum- och tidsvärde som anger när dokumentet senast redigerades. |
| [TimePrinted](../../groupdocs.metadata.formats.document/diagrampackage/timeprinted) { get; } | Får ett datum- och tidsvärde som anger när dokumentet senast skrevs ut. |
| [TimeSaved](../../groupdocs.metadata.formats.document/diagrampackage/timesaved) { get; } | Får ett datum- och tidsvärde som anger när dokumentet senast sparades. |
| [Title](../../groupdocs.metadata.formats.document/diagrampackage/title) { get; set; } | Hämtar eller ställer in en användardefinierad textsträng som fungerar som en beskrivande titel för dokumentet. Maximal längd är 63 tecken. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Lägger till kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar även alla kapslade paket. |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | Tar bort alla skrivbara metadataegenskaper från paketet. |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | Tar bort alla inbyggda metadataegenskaper. |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | Tar bort alla anpassade metadataegenskaper. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestämmer om paketet innehåller en metadataegenskap med det angivna namnet. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Hittar metadataegenskaperna som uppfyller det angivna predikatet. Sökningen är rekursiv så den påverkar också alla kapslade paket. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | Tar bort en skrivbar metadataegenskap med det angivna namnet. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Tar bort metadataegenskaper som uppfyller det angivna predikatet. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Tar bort skrivbara metadataegenskaper från paketet. Operationen är rekursiv så den påverkar alla kapslade paket också. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set)(string, bool) | Lägger till eller ersätter metadataegenskapen med det angivna namnet. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_2)(string, DateTime) | Lägger till eller ersätter metadataegenskapen med det angivna namnet. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_1)(string, double) | Lägger till eller ersätter metadataegenskapen med det angivna namnet. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_3)(string, string) | Lägger till eller ersätter metadataegenskapen med det angivna namnet. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Anmärkningar

**Läs mer**

* [Arbeta med metadata i diagram](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### Exempel

Detta kodexempel visar hur man extraherar inbyggda metadataegenskaper från ett diagram.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVsdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    Console.WriteLine(root.DocumentProperties.Creator);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.Language);
    Console.WriteLine(root.DocumentProperties.TimeCreated);
    Console.WriteLine(root.DocumentProperties.Category);

    // ... 
}
```

### Se även

* class [DocumentPackage](../documentpackage)
* namnutrymme [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
