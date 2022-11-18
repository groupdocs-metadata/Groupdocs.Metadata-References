---
title: MsgRootPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar rotpaketet som tillåter arbete med metadata i ett MSGepostmeddelande.
type: docs
weight: 1410
url: /sv/net/groupdocs.metadata.formats.email/msgrootpackage/
---
## MsgRootPackage class

Representerar rotpaketet som tillåter arbete med metadata i ett MSG-e-postmeddelande.

```csharp
public class MsgRootPackage : EmailRootPackage
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [EmailPackage](../../groupdocs.metadata.formats.email/msgrootpackage/emailpackage) { get; } | Hämtar MSG-metadatapaketet. (2 properties) |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Hämtar filtypens metadatapaket. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Lägger till kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar även alla kapslade paket. |
| [ClearAttachments](../../groupdocs.metadata.formats.email/emailrootpackage/clearattachments)() | Tar bort alla bilagor från e-postmeddelandet. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestämmer om paketet innehåller en metadataegenskap med det angivna namnet. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Hittar metadataegenskaperna som uppfyller det angivna predikatet. Sökningen är rekursiv så den påverkar också alla kapslade paket. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Tar bort metadataegenskaper som uppfyller det angivna predikatet. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Tar bort skrivbara metadataegenskaper från paketet. Operationen är rekursiv så den påverkar alla kapslade paket också. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Anmärkningar

**Läs mer**

* [Arbeta med sparade e-postmeddelanden](https://docs.groupdocs.com/display/metadatanet/Working+with+saved+Emails)

### Exempel

Detta kodexempel visar hur man extraherar metadata från ett MSG-meddelande.

```csharp
using (Metadata metadata = new Metadata(Constants.InputMsg))
{
    var root = metadata.GetRootPackage<MsgRootPackage>();

    Console.WriteLine(root.EmailPackage.Sender);
    Console.WriteLine(root.EmailPackage.Subject);
    foreach (string recipient in root.EmailPackage.Recipients)
    {
        Console.WriteLine(recipient);
    }

    foreach (var attachedFileName in root.EmailPackage.AttachedFileNames)
    {
        Console.WriteLine(attachedFileName);
    }

    foreach (var header in root.EmailPackage.Headers)
    {
        Console.WriteLine("{0} = {1}", header.Name, header.Value);
    }

    Console.WriteLine(root.EmailPackage.Body);
    Console.WriteLine(root.EmailPackage.DeliveryTime);

    // ...
}
```

### Se även

* class [EmailRootPackage](../emailrootpackage)
* namnutrymme [GroupDocs.Metadata.Formats.Email](../../groupdocs.metadata.formats.email)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
