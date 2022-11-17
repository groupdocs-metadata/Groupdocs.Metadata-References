---
title: VCardCalendarRecordset
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar en uppsättning vCardposter i Kalender.
type: docs
weight: 640
url: /sv/net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/
---
## VCardCalendarRecordset class

Representerar en uppsättning vCard-poster i Kalender.

```csharp
public class VCardCalendarRecordset : VCardRecordset
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BusyTimeEntries](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/busytimeentries) { get; } | Hämtar URI:erna för den upptagna tiden som är associerad med objektet. |
| [BusyTimeRecords](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/busytimerecords) { get; } | Hämtar URI:erna för den upptagna tiden som är associerad med objektet. |
| [CalendarAddresses](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendaraddresses) { get; } | Hämtar kalenderanvändaradresserna som en schemaläggningsbegäran ska skickas till för objektet som representeras av vCard. |
| [CalendarAddressRecords](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendaraddressrecords) { get; } | Hämtar kalenderanvändaradresserna som en schemaläggningsbegäran ska skickas till för objektet som representeras av vCard. |
| [CalendarUriRecords](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendarurirecords) { get; } | Hämtar URI:erna för kalendern som är associerad med objektet som representeras av vCard. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [UriCalendarEntries](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/uricalendarentries) { get; } | Hämtar URI:erna för kalendern som är associerad med objektet som representeras av vCard. |

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

* [Arbeta med vCard-metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Se även

* class [VCardRecordset](../vcardrecordset)
* namnutrymme [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
