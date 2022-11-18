---
title: NoteRootPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar rotpaketet avsett att arbeta med metadata i en elektronisk anteckningsfil.
type: docs
weight: 970
url: /sv/net/groupdocs.metadata.formats.document/noterootpackage/
---
## NoteRootPackage class

Representerar rotpaketet avsett att arbeta med metadata i en elektronisk anteckningsfil.

```csharp
public class NoteRootPackage : RootMetadataPackage
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [DocumentStatistics](../../groupdocs.metadata.formats.document/noterootpackage/documentstatistics) { get; } | Hämtar dokumentstatistikpaketet. |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Hämtar filtypens metadatapaket. |
| [InspectionPackage](../../groupdocs.metadata.formats.document/noterootpackage/inspectionpackage) { get; } | Hämtar ett metadatapaket som innehåller inspektionsresultat för dokumentet. Paketet innehåller information om dokumentdelar som kan betraktas som metadata i vissa fall. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Lägger till kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar även alla kapslade paket. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestämmer om paketet innehåller en metadataegenskap med det angivna namnet. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Hittar metadataegenskaperna som uppfyller det angivna predikatet. Sökningen är rekursiv så den påverkar också alla kapslade paket. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Tar bort metadataegenskaper som uppfyller det angivna predikatet. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Tar bort skrivbara metadataegenskaper från paketet. Operationen är rekursiv så den påverkar alla kapslade paket också. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Anmärkningar

**Läs mer**

* [Arbeta med metadata i Note-format](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Note+formats)

### Exempel

Detta kodexempel visar hur man inspekterar ett anteckningsdokument.

```csharp
using (Metadata metadata = new Metadata(Constants.InputOne))
{
    var root = metadata.GetRootPackage<NoteRootPackage>();

    if (root.InspectionPackage.Pages != null)
    {
        foreach (var page in root.InspectionPackage.Pages)
        {
            Console.WriteLine(page.Title);
            Console.WriteLine(page.Author);
            Console.WriteLine(page.CreationTime);
            Console.WriteLine(page.LastModificationTime);
        }
    }
}
```

### Se även

* class [RootMetadataPackage](../../groupdocs.metadata.common/rootmetadatapackage)
* namnutrymme [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
