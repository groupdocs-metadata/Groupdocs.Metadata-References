---
title: ZipPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar ZIParkivmetadata.
type: docs
weight: 360
url: /sv/net/groupdocs.metadata.formats.archive/zippackage/
---
## ZipPackage class

Representerar ZIP-arkivmetadata.

```csharp
public sealed class ZipPackage : CustomPackage
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Comment](../../groupdocs.metadata.formats.archive/zippackage/comment) { get; set; } | Hämtar eller ställer in ZIP-arkivkommentaren skapad av en användare. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [Files](../../groupdocs.metadata.formats.archive/zippackage/files) { get; } | Får en array av[`ZipFile`](../zipfile) poster i ZIP-arkivet. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [TotalEntries](../../groupdocs.metadata.formats.archive/zippackage/totalentries) { get; } | Hämtar det totala antalet poster i ZIP-arkivet. |

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

* [Arbeta med ZIP-arkiv](https://docs.groupdocs.com/display/metadatanet/Working+with+ZIP+archives)

### Exempel

Följande kodavsnitt visar hur man hämtar metadata från ett ZIP-arkiv.

```csharp
Encoding encoding = Encoding.GetEncoding(866);

using (Metadata metadata = new Metadata(Constants.InputZip))
{
    var root = metadata.GetRootPackage<ZipRootPackage>();

    Console.WriteLine(root.ZipPackage.Comment);
    Console.WriteLine(root.ZipPackage.TotalEntries);

    foreach (var file in root.ZipPackage.Files)
    {
        Console.WriteLine(file.Name);
        Console.WriteLine(file.CompressedSize);
        Console.WriteLine(file.CompressionMethod);
        Console.WriteLine(file.Flags);
        Console.WriteLine(file.ModificationDateTime);
        Console.WriteLine(file.UncompressedSize);

        // Använd en specifik kodning för filnamnen
        Console.WriteLine(encoding.GetString(file.RawName));
    }
}
```

### Se även

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namnutrymme [GroupDocs.Metadata.Formats.Archive](../../groupdocs.metadata.formats.archive)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
