---
title: VCardSecurityRecordset
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar en uppsättning säkerhetsvCardposter. Dessa egenskaper handlar om säkerheten för kommunikationsvägar eller åtkomst till vCard.
type: docs
weight: 800
url: /sv/net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/
---
## VCardSecurityRecordset class

Representerar en uppsättning säkerhets-vCard-poster. Dessa egenskaper handlar om säkerheten för kommunikationsvägar eller åtkomst till vCard.

```csharp
public class VCardSecurityRecordset : VCardRecordset
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AccessClassification](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/accessclassification) { get; } | Hämtar känsligheten för informationen i vCard. |
| [BinaryPublicKeys](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/binarypublickeys) { get; } | Hämtar de publika nycklarna eller autentiseringscertifikaten som är kopplade till objektet. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [PublicKeyBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/publickeybinaryrecords) { get; } | Hämtar de publika nycklarna eller autentiseringscertifikaten som är kopplade till objektet. |
| [PublicKeyRecords](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/publickeyrecords) { get; } | Hämtar de publika nycklarna eller autentiseringscertifikaten som är kopplade till objektet. |
| [PublicKeyUriRecords](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/publickeyurirecords) { get; } | Hämtar de publika nycklarna eller autentiseringscertifikaten som är kopplade till objektet. |
| [UriPublicKeys](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/uripublickeys) { get; } | Hämtar de publika nycklarna eller autentiseringscertifikaten som är kopplade till objektet. |

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
