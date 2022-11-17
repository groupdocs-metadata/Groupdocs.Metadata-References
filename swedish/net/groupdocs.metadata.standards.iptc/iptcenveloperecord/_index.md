---
title: IptcEnvelopeRecord
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar en IPTC Envelope Record.
type: docs
weight: 2910
url: /sv/net/groupdocs.metadata.standards.iptc/iptcenveloperecord/
---
## IptcEnvelopeRecord class

Representerar en IPTC Envelope Record.

```csharp
public sealed class IptcEnvelopeRecord : IptcRecord
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [IptcEnvelopeRecord](iptcenveloperecord)() | Initierar en ny instans av[`IptcEnvelopeRecord`](../iptcenveloperecord) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [DateSent](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/datesent) { get; set; } | Hämtar eller ställer in datumet då tjänsten skickade materialet. |
| [Destination](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/destination) { get; set; } | Hämtar eller ställer in destinationen. |
| [Destinations](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/destinations) { get; set; } | Hämtar eller ställer in en rad destinationer. |
| [FileFormat](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/fileformat) { get; set; } | Hämtar eller ställer in filformatet. |
| [FileFormatVersion](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/fileformatversion) { get; set; } | Hämtar eller ställer in filformatversionen. Ett nummer som representerar den specifika versionen av filformatet som anges i[`FileFormat`](./fileformat) . |
| [Item](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/item) { get; } | Får[`IptcDataSet`](../iptcdataset) med det angivna numret. (3 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [ModelVersion](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/modelversion) { get; set; } | Hämtar eller ställer in ett nummer som identifierar versionen av informationen. |
| [ProductID](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/productid) { get; set; } | Hämtar eller ställer in produktidentifieraren. |
| [ProductIds](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/productids) { get; set; } | Hämtar eller ställer in produktidentifierare. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [RecordNumber](../../groupdocs.metadata.standards.iptc/iptcrecord/recordnumber) { get; } | Får postnumret. |
| [ServiceIdentifier](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/serviceidentifier) { get; set; } | Hämtar eller ställer in tjänstens identifierare. |

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
| [ToList](../../groupdocs.metadata.standards.iptc/iptcrecord/tolist)() | Skapar en lista från paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Anmärkningar

**Läs mer**

* [Arbeta med IPTC IIM-metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Se även

* class [IptcRecord](../iptcrecord)
* namnutrymme [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
