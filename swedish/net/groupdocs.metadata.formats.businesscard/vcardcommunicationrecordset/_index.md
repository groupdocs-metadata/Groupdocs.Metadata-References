---
title: VCardCommunicationRecordset
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar en uppsättning kommunikation vCardposter. Dessa egenskaper beskriver information om hur man kommunicerar med objektet vCard representerar.
type: docs
weight: 660
url: /sv/net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/
---
## VCardCommunicationRecordset class

Representerar en uppsättning kommunikation vCard-poster. Dessa egenskaper beskriver information om hur man kommunicerar med objektet vCard representerar.

```csharp
public class VCardCommunicationRecordset : VCardRecordset
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [EmailRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/emailrecords) { get; } | Hämtar e-postadresserna för kommunikation med objektet. |
| [Emails](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/emails) { get; } | Hämtar e-postadresserna för kommunikation med objektet. |
| [ImppEntries](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/imppentries) { get; } | Hämtar URI:erna för snabbmeddelanden och kommunikation med närvaroprotokoll med objektet. |
| [ImppRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/impprecords) { get; } | Hämtar URI:erna för snabbmeddelanden och kommunikation med närvaroprotokoll med objektet. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [LanguageRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/languagerecords) { get; } | Hämtar språken som kan användas för att kontakta objektet. |
| [Languages](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/languages) { get; } | Hämtar språken som kan användas för att kontakta objektet. |
| [Mailer](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/mailer) { get; } | Hämtar typen av e-postprogramvara som används av individen som är associerad med vCard. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [TelephoneRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/telephonerecords) { get; } | Hämtar telefonnummer för telefonikommunikation med objektet. |
| [Telephones](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/telephones) { get; } | Hämtar telefonnummer för telefonikommunikation med objektet. |

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
