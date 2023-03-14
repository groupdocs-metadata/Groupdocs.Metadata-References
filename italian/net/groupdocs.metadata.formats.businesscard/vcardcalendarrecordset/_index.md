---
title: VCardCalendarRecordset
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un set di record vCard del calendario.
type: docs
weight: 640
url: /it/net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/
---
## VCardCalendarRecordset class

Rappresenta un set di record vCard del calendario.

```csharp
public class VCardCalendarRecordset : VCardRecordset
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BusyTimeEntries](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/busytimeentries) { get; } | Ottiene gli URI per il tempo occupato associato all'oggetto. |
| [BusyTimeRecords](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/busytimerecords) { get; } | Ottiene gli URI per il tempo occupato associato all'oggetto. |
| [CalendarAddresses](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendaraddresses) { get; } | Ottiene gli indirizzi utente del calendario a cui inviare una richiesta di pianificazione per l'oggetto rappresentato dalla vCard. |
| [CalendarAddressRecords](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendaraddressrecords) { get; } | Ottiene gli indirizzi utente del calendario a cui inviare una richiesta di pianificazione per l'oggetto rappresentato dalla vCard. |
| [CalendarUriRecords](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendarurirecords) { get; } | Ottiene gli URI per il calendario associato all'oggetto rappresentato dalla vCard. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [UriCalendarEntries](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/uricalendarentries) { get; } | Ottiene gli URI per il calendario associato all'oggetto rappresentato dalla vCard. |

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
