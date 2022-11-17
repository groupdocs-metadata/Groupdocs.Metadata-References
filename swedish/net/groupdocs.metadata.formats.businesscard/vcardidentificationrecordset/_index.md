---
title: VCardIdentificationRecordset
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar en uppsättning vCardposter för identifiering. Dessa typer används för att fånga information associerad med identifieringen och namngivningen av den enhet som är associerad med vCard.
type: docs
weight: 740
url: /sv/net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/
---
## VCardIdentificationRecordset class

Representerar en uppsättning vCard-poster för identifiering. Dessa typer används för att fånga information associerad med identifieringen och namngivningen av den enhet som är associerad med vCard.

```csharp
public class VCardIdentificationRecordset : VCardRecordset
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AnniversaryDateTimeRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversarydatetimerecord) { get; } | Får datumet för äktenskapet representerat som ett enda datum-och-eller-tidsvärde. |
| [AnniversaryRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversaryrecord) { get; } | Hämtar datumet för äktenskapet, eller motsvarande, för objektet. |
| [AnniversaryTextRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversarytextrecord) { get; } | Får vigseldatumet representerat som ett enda textvärde. |
| [BinaryPhotos](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/binaryphotos) { get; } | Hämtar en array som innehåller bild- eller fotografiinformationen representerad som binär data som kommenterar vissa aspekter av objektet. |
| [BirthdateDateTimeRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdatedatetimerecord) { get; } | Hämtar objektets födelsedatum. |
| [BirthdateRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdaterecords) { get; } | Hämtar en array som innehåller objektets födelsedatum i olika representationer. |
| [BirthdateTextRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdatetextrecords) { get; } | Hämtar en array som innehåller objektets födelsedatum i olika textrepresentationer. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [DateTimeAnniversary](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/datetimeanniversary) { get; } | Får datumet för äktenskapet representerat som ett enda datum-och-eller-tidsvärde. |
| [DateTimeBirthdate](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/datetimebirthdate) { get; } | Hämtar objektets födelsedatum. |
| [FormattedNameRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/formattednamerecords) { get; } | Hämtar en array som innehåller den formaterade texten som motsvarar namnet på objektet. |
| [FormattedNames](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/formattednames) { get; } | Hämtar en array som innehåller den formaterade texten som motsvarar namnet på objektet. |
| [Gender](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/gender) { get; } | Hämtar komponenterna av objektets kön och könsidentitet. |
| [GenderRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/genderrecord) { get; } | Hämtar komponenterna av objektets kön och könsidentitet. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [Name](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/name) { get; } | Hämtar komponenterna i namnet på objektet. |
| [NameRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/namerecord) { get; } | Hämtar komponenterna i namnet på objektet. |
| [NicknameRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/nicknamerecords) { get; } | Hämtar en array som innehåller texten som motsvarar objektets smeknamn. |
| [Nicknames](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/nicknames) { get; } | Hämtar en array som innehåller texten som motsvarar objektets smeknamn. |
| [PhotoBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photobinaryrecords) { get; } | Hämtar en array som innehåller bild- eller fotografiinformationen representerad som binär data som kommenterar vissa aspekter av objektet. |
| [PhotoRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photorecords) { get; } | Hämtar en array som innehåller bilden eller fotografiinformationen som kommenterar vissa aspekter av objektet. |
| [PhotoUriRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photourirecords) { get; } | Hämtar en array som innehåller bild- eller fotografiinformationen representerad av URI:er som kommenterar vissa aspekter av objektet. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [TextAnniversary](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/textanniversary) { get; } | Får vigseldatumet representerat som ett enda textvärde. |
| [TextBirthdates](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/textbirthdates) { get; } | Hämtar en array som innehåller objektets födelsedatum i olika textrepresentationer. |
| [UriPhotos](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/uriphotos) { get; } | Hämtar en array som innehåller bild- eller fotografiinformationen representerad av URI:er som kommenterar vissa aspekter av objektet. |

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
