---
title: OpenTypeMacintoshNameRecord
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar namnposttabellens värde förMacintosh plattform.
type: docs
weight: 1510
url: /sv/net/groupdocs.metadata.formats.font/opentypemacintoshnamerecord/
---
## OpenTypeMacintoshNameRecord class

Representerar namnposttabellens värde förMacintosh plattform.

```csharp
public class OpenTypeMacintoshNameRecord : OpenTypeBaseNameRecord
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [Encoding](../../groupdocs.metadata.formats.font/opentypemacintoshnamerecord/encoding) { get; } | Hämtar kodningsidentifieraren. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [Language](../../groupdocs.metadata.formats.font/opentypemacintoshnamerecord/language) { get; } | Hämtar språkidentifieraren. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [NameID](../../groupdocs.metadata.formats.font/opentypebasenamerecord/nameid) { get; } | Hämtar namnidentifieraren. |
| [Platform](../../groupdocs.metadata.formats.font/opentypebasenamerecord/platform) { get; } | Hämtar plattformsidentifieraren. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [Value](../../groupdocs.metadata.formats.font/opentypebasenamerecord/value) { get; } | Hämtar strängvärdet för post. |

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

* [Arbeta med OpenType-teckensnitt](https://docs.groupdocs.com/display/metadatanet/Working+with+OpenType+fonts)

### Se även

* class [OpenTypeBaseNameRecord](../opentypebasenamerecord)
* namnutrymme [GroupDocs.Metadata.Formats.Font](../../groupdocs.metadata.formats.font)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->