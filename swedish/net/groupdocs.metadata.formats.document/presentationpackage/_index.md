---
title: PresentationPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar ett inbyggt metadatapaket i en presentation.
type: docs
weight: 1090
url: /sv/net/groupdocs.metadata.formats.document/presentationpackage/
---
## PresentationPackage class

Representerar ett inbyggt metadatapaket i en presentation.

```csharp
public class PresentationPackage : DocumentPackage
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ApplicationTemplate](../../groupdocs.metadata.formats.document/presentationpackage/applicationtemplate) { get; set; } | Hämtar eller ställer in ansökningsmallen. |
| [Author](../../groupdocs.metadata.formats.document/presentationpackage/author) { get; set; } | Hämtar eller ställer in dokumentets författare. |
| [Category](../../groupdocs.metadata.formats.document/presentationpackage/category) { get; set; } | Hämtar eller ställer in kategorin. |
| [Comments](../../groupdocs.metadata.formats.document/presentationpackage/comments) { get; set; } | Hämtar eller ställer in kommentarerna. |
| [Company](../../groupdocs.metadata.formats.document/presentationpackage/company) { get; set; } | Får eller sätter företaget. |
| [ContentStatus](../../groupdocs.metadata.formats.document/presentationpackage/contentstatus) { get; set; } | Hämtar eller ställer in innehållsstatus. Kan endast uppdateras i ett PPTX-dokument. |
| [ContentType](../../groupdocs.metadata.formats.document/presentationpackage/contenttype) { get; set; } | Hämtar eller ställer in innehållstypen. Kan endast uppdateras i ett PPTX-dokument. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [CreatedTime](../../groupdocs.metadata.formats.document/presentationpackage/createdtime) { get; set; } | Hämtar eller ställer in dokumentets skapade datum. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/presentationpackage/hyperlinkbase) { get; set; } | Hämtar eller ställer in hyperlänksbasen. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [Keywords](../../groupdocs.metadata.formats.document/presentationpackage/keywords) { get; set; } | Hämtar eller ställer in sökorden. |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/presentationpackage/lastprinteddate) { get; set; } | Hämtar eller ställer in det senast utskrivna datumet. |
| [LastSavedBy](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedby) { get; set; } | Hämtar eller ställer in namnet på den senaste författaren. |
| [LastSavedTime](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedtime) { get; } | Hämtar datum och tid när presentationen ändrades förra gången. |
| [Manager](../../groupdocs.metadata.formats.document/presentationpackage/manager) { get; set; } | Hämtar eller ställer in managern. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [NameOfApplication](../../groupdocs.metadata.formats.document/presentationpackage/nameofapplication) { get; } | Hämtar namnet på programmet som skapade dokumentet. |
| [PresentationFormat](../../groupdocs.metadata.formats.document/presentationpackage/presentationformat) { get; } | Hämtar presentationsformatet. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [RevisionNumber](../../groupdocs.metadata.formats.document/presentationpackage/revisionnumber) { get; set; } | Hämtar eller ställer in revisionsnumret. |
| [SharedDoc](../../groupdocs.metadata.formats.document/presentationpackage/shareddoc) { get; set; } | Hämtar eller ställer in ett värde som anger om presentationen delas mellan flera personer. Kan endast uppdateras i ett PPTX-dokument. |
| [Subject](../../groupdocs.metadata.formats.document/presentationpackage/subject) { get; set; } | Får eller ställer in ämnet. |
| [Title](../../groupdocs.metadata.formats.document/presentationpackage/title) { get; set; } | Hämtar eller ställer in titeln på dokumentet. |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/presentationpackage/totaleditingtime) { get; set; } | Hämtar eller ställer in den totala redigeringstiden för dokumentet. |
| [Version](../../groupdocs.metadata.formats.document/presentationpackage/version) { get; } | Hämtar applikationsversionen. |

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
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set)(string, bool) | Lägger till eller ersätter metadataegenskapen med det angivna namnet. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_3)(string, DateTime) | Lägger till eller ersätter metadataegenskapen med det angivna namnet. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_1)(string, double) | Lägger till eller ersätter metadataegenskapen med det angivna namnet. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_2)(string, int) | Lägger till eller ersätter metadataegenskapen med det angivna namnet. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_4)(string, string) | Lägger till eller ersätter metadataegenskapen med det angivna namnet. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Anmärkningar

**Läs mer**

* [Arbeta med metadata i presentationer](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Presentations)

### Exempel

Det här exemplet visar hur man uppdaterar inbyggda metadataegenskaper i en presentation.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPptx))
{
    var root = metadata.GetRootPackage<PresentationRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputPptx);
}
```

### Se även

* class [DocumentPackage](../documentpackage)
* namnutrymme [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
