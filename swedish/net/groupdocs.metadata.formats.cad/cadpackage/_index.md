---
title: CadPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar CAD Computeraided design metadata.
type: docs
weight: 840
url: /sv/net/groupdocs.metadata.formats.cad/cadpackage/
---
## CadPackage class

Representerar CAD (Computer-aided design) metadata.

```csharp
public sealed class CadPackage : CustomPackage
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AcadVersion](../../groupdocs.metadata.formats.cad/cadpackage/acadversion) { get; } | Hämtar AutoCAD ritdatabasens versionsnummer. |
| [Author](../../groupdocs.metadata.formats.cad/cadpackage/author) { get; } | Får ritningsförfattaren. |
| [Comments](../../groupdocs.metadata.formats.cad/cadpackage/comments) { get; } | Får användarens kommentarer. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [CreatedDateTime](../../groupdocs.metadata.formats.cad/cadpackage/createddatetime) { get; } | Hämtar datum och tid när ritningen skapades. |
| [CustomProperties](../../groupdocs.metadata.formats.cad/cadpackage/customproperties) { get; } | Hämtar paketet som innehåller anpassade metadataegenskaper. |
| [Height](../../groupdocs.metadata.formats.cad/cadpackage/height) { get; } | Får rithöjden. |
| [HyperlinkBase](../../groupdocs.metadata.formats.cad/cadpackage/hyperlinkbase) { get; } | Hämtar hyperlänksbasen. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [Keywords](../../groupdocs.metadata.formats.cad/cadpackage/keywords) { get; } | Hämtar sökorden. |
| [LastSavedBy](../../groupdocs.metadata.formats.cad/cadpackage/lastsavedby) { get; } | Hämtar namnet på den senaste redigeraren. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [ModifiedDateTime](../../groupdocs.metadata.formats.cad/cadpackage/modifieddatetime) { get; } | Hämtar datum och tid när ritningen ändrades. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [RevisionNumber](../../groupdocs.metadata.formats.cad/cadpackage/revisionnumber) { get; } | Får versionsnumret. |
| [Subject](../../groupdocs.metadata.formats.cad/cadpackage/subject) { get; } | Får ämnet. |
| [Title](../../groupdocs.metadata.formats.cad/cadpackage/title) { get; } | Får titeln. |
| [Width](../../groupdocs.metadata.formats.cad/cadpackage/width) { get; } | Får ritningsbredden. |

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

* [Arbeta med CAD-metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+CAD+metadata)

### Se även

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namnutrymme [GroupDocs.Metadata.Formats.Cad](../../groupdocs.metadata.formats.cad)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
