---
title: SpreadsheetInspectionPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Innehåller information om kalkylbladsdelar som i vissa fall kan betraktas som metadata.
type: docs
weight: 1190
url: /sv/net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/
---
## SpreadsheetInspectionPackage class

Innehåller information om kalkylbladsdelar som i vissa fall kan betraktas som metadata.

```csharp
public sealed class SpreadsheetInspectionPackage : CustomPackage
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Comments](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/comments) { get; } | Får en mängd användarkommentarer. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/digitalsignatures) { get; } | Får en rad digitala signaturer som presenteras i dokumentet. |
| [HiddenSheets](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/hiddensheets) { get; } | Får en uppsättning av de dolda arken. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Lägger till kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar även alla kapslade paket. |
| [ClearComments](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/clearcomments)() | Tar bort alla upptäckta användarkommentarer från kalkylarket. |
| [ClearDigitalSignatures](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/cleardigitalsignatures)() | Tar bort alla upptäckta digitala signaturer från kalkylarket. |
| [ClearHiddenSheets](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/clearhiddensheets)() | Tar bort alla upptäckta dolda ark från kalkylarket. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestämmer om paketet innehåller en metadataegenskap med det angivna namnet. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Hittar metadataegenskaperna som uppfyller det angivna predikatet. Sökningen är rekursiv så den påverkar också alla kapslade paket. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Tar bort metadataegenskaper som uppfyller det angivna predikatet. |
| override [Sanitize](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/sanitize)() | Tar bort skrivbara metadataegenskaper från paketet. Operationen är rekursiv så den påverkar alla kapslade paket också. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Anmärkningar

**Läs mer**

* [Arbeta med metadata i kalkylblad](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Spreadsheets)

### Exempel

Det här kodexemplet visar egenskaper för att ta bort inspektioner från ett kalkylblad.

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    var root = metadata.GetRootPackage<SpreadsheetRootPackage>();

    root.InspectionPackage.ClearComments();
    root.InspectionPackage.ClearDigitalSignatures();
    root.InspectionPackage.ClearHiddenSheets();

    metadata.Save(Constants.OutputXlsx);
}
```

### Se även

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namnutrymme [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
