---
title: VCardCommunicationRecordset
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un insieme di record vCard di comunicazione. Queste proprietà descrivono informazioni su come comunicare con loggetto rappresentato dalla vCard.
type: docs
weight: 660
url: /it/net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/
---
## VCardCommunicationRecordset class

Rappresenta un insieme di record vCard di comunicazione. Queste proprietà descrivono informazioni su come comunicare con l'oggetto rappresentato dalla vCard.

```csharp
public class VCardCommunicationRecordset : VCardRecordset
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [EmailRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/emailrecords) { get; } | Ottiene gli indirizzi di posta elettronica per la comunicazione con l'oggetto. |
| [Emails](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/emails) { get; } | Ottiene gli indirizzi di posta elettronica per la comunicazione con l'oggetto. |
| [ImppEntries](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/imppentries) { get; } | Ottiene gli URI per la messaggistica istantanea e le comunicazioni del protocollo di presenza con l'oggetto. |
| [ImppRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/impprecords) { get; } | Ottiene gli URI per la messaggistica istantanea e le comunicazioni del protocollo di presenza con l'oggetto. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [LanguageRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/languagerecords) { get; } | Ottiene le lingue che possono essere utilizzate per contattare l'oggetto. |
| [Languages](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/languages) { get; } | Ottiene le lingue che possono essere utilizzate per contattare l'oggetto. |
| [Mailer](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/mailer) { get; } | Ottiene il tipo di software di posta elettronica utilizzato dall'individuo associato alla vCard. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [TelephoneRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/telephonerecords) { get; } | Ottiene i numeri di telefono per la comunicazione telefonica con l'oggetto. |
| [Telephones](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/telephones) { get; } | Ottiene i numeri di telefono per la comunicazione telefonica con l'oggetto. |

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
