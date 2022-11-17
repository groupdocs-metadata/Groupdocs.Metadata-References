---
title: VCardDeliveryAddressingRecordset
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un insieme di record vCard dellindirizzo di consegna. Questi tipi riguardano le informazioni relative a lindirizzo di consegna o letichetta per loggetto vCard.
type: docs
weight: 700
url: /it/net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/
---
## VCardDeliveryAddressingRecordset class

Rappresenta un insieme di record vCard dell'indirizzo di consegna. Questi tipi riguardano le informazioni relative a l'indirizzo di consegna o l'etichetta per l'oggetto vCard.

```csharp
public class VCardDeliveryAddressingRecordset : VCardRecordset
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Addresses](../../groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/addresses) { get; } | Ottiene i componenti dell'indirizzo di consegna dell'oggetto. |
| [AddressRecords](../../groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/addressrecords) { get; } | Ottiene i componenti dell'indirizzo di consegna dell'oggetto. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [LabelRecords](../../groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/labelrecords) { get; } | Ottiene un array contenente il testo formattato corrispondente all'indirizzo di consegna dell'oggetto. |
| [Labels](../../groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/labels) { get; } | Ottiene un array contenente il testo formattato corrispondente all'indirizzo di consegna dell'oggetto. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) e[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

**Scopri di più**

* [Utilizzo dei metadati vCard](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Guarda anche

* class [VCardRecordset](../vcardrecordset)
* spazio dei nomi [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
