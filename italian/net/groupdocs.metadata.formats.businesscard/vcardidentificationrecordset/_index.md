---
title: VCardIdentificationRecordset
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un insieme di record vCard di identificazione. Questi tipi vengono utilizzati per acquisire informazioni associate a lidentificazione e la denominazione dellentità associata alla vCard.
type: docs
weight: 740
url: /it/net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/
---
## VCardIdentificationRecordset class

Rappresenta un insieme di record vCard di identificazione. Questi tipi vengono utilizzati per acquisire informazioni associate a l'identificazione e la denominazione dell'entità associata alla vCard.

```csharp
public class VCardIdentificationRecordset : VCardRecordset
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AnniversaryDateTimeRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversarydatetimerecord) { get; } | Ottiene la data del matrimonio rappresentata come un unico valore di data e ora. |
| [AnniversaryRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversaryrecord) { get; } | Ottiene la data del matrimonio, o equivalente, dell'oggetto. |
| [AnniversaryTextRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversarytextrecord) { get; } | Ottiene la data del matrimonio rappresentata come un singolo valore di testo. |
| [BinaryPhotos](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/binaryphotos) { get; } | Ottiene un array contenente le informazioni sull'immagine o sulla fotografia rappresentate come dati binari che annotano alcuni aspetti dell'oggetto. |
| [BirthdateDateTimeRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdatedatetimerecord) { get; } | Ottiene la data di nascita dell'oggetto. |
| [BirthdateRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdaterecords) { get; } | Ottiene un array contenente la data di nascita dell'oggetto in diverse rappresentazioni. |
| [BirthdateTextRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdatetextrecords) { get; } | Ottiene un array contenente la data di nascita dell'oggetto in diverse rappresentazioni testuali. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [DateTimeAnniversary](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/datetimeanniversary) { get; } | Ottiene la data del matrimonio rappresentata come un unico valore di data e ora. |
| [DateTimeBirthdate](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/datetimebirthdate) { get; } | Ottiene la data di nascita dell'oggetto. |
| [FormattedNameRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/formattednamerecords) { get; } | Ottiene un array contenente il testo formattato corrispondente al nome dell'oggetto. |
| [FormattedNames](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/formattednames) { get; } | Ottiene un array contenente il testo formattato corrispondente al nome dell'oggetto. |
| [Gender](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/gender) { get; } | Ottiene i componenti del sesso e dell'identità di genere dell'oggetto. |
| [GenderRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/genderrecord) { get; } | Ottiene i componenti del sesso e dell'identità di genere dell'oggetto. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [Name](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/name) { get; } | Ottiene i componenti del nome dell'oggetto. |
| [NameRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/namerecord) { get; } | Ottiene i componenti del nome dell'oggetto. |
| [NicknameRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/nicknamerecords) { get; } | Ottiene un array contenente il testo corrispondente al nickname dell'oggetto. |
| [Nicknames](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/nicknames) { get; } | Ottiene un array contenente il testo corrispondente al nickname dell'oggetto. |
| [PhotoBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photobinaryrecords) { get; } | Ottiene un array contenente le informazioni sull'immagine o sulla fotografia rappresentate come dati binari che annotano alcuni aspetti dell'oggetto. |
| [PhotoRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photorecords) { get; } | Ottiene un array contenente le informazioni sull'immagine o sulla fotografia che annotano alcuni aspetti dell'oggetto. |
| [PhotoUriRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photourirecords) { get; } | Ottiene un array contenente le informazioni sull'immagine o sulla fotografia rappresentate da URI che annotano alcuni aspetti dell'oggetto. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [TextAnniversary](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/textanniversary) { get; } | Ottiene la data del matrimonio rappresentata come un singolo valore di testo. |
| [TextBirthdates](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/textbirthdates) { get; } | Ottiene un array contenente la data di nascita dell'oggetto in diverse rappresentazioni testuali. |
| [UriPhotos](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/uriphotos) { get; } | Ottiene un array contenente le informazioni sull'immagine o sulla fotografia rappresentate da URI che annotano alcuni aspetti dell'oggetto. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) E[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

**Saperne di più**

* [Utilizzo dei metadati vCard](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Guarda anche

* class [VCardRecordset](../vcardrecordset)
* spazio dei nomi [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
