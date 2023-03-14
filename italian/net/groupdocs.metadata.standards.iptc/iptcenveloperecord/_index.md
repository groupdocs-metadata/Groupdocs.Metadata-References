---
title: IptcEnvelopeRecord
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un record busta IPTC.
type: docs
weight: 2910
url: /it/net/groupdocs.metadata.standards.iptc/iptcenveloperecord/
---
## IptcEnvelopeRecord class

Rappresenta un record busta IPTC.

```csharp
public sealed class IptcEnvelopeRecord : IptcRecord
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [IptcEnvelopeRecord](iptcenveloperecord)() | Inizializza una nuova istanza di[`IptcEnvelopeRecord`](../iptcenveloperecord) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [DateSent](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/datesent) { get; set; } | Ottiene o imposta la data in cui il servizio ha inviato il materiale. |
| [Destination](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/destination) { get; set; } | Ottiene o imposta la destinazione. |
| [Destinations](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/destinations) { get; set; } | Ottiene o imposta un array di destinazioni. |
| [FileFormat](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/fileformat) { get; set; } | Ottiene o imposta il formato del file. |
| [FileFormatVersion](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/fileformatversion) { get; set; } | Ottiene o imposta la versione del formato file. Un numero che rappresenta la versione particolare del formato file specificato in[`FileFormat`](./fileformat) . |
| [Item](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/item) { get; } | Ottiene il[`IptcDataSet`](../iptcdataset) con il numero specificato. (3 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [ModelVersion](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/modelversion) { get; set; } | Ottiene o imposta un numero che identifica la versione delle informazioni. |
| [ProductID](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/productid) { get; set; } | Ottiene o imposta l'identificativo del prodotto. |
| [ProductIds](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/productids) { get; set; } | Ottiene o imposta gli identificatori del prodotto. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [RecordNumber](../../groupdocs.metadata.standards.iptc/iptcrecord/recordnumber) { get; } | Ottiene il numero del record. |
| [ServiceIdentifier](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/serviceidentifier) { get; set; } | Ottiene o imposta l'identificatore del servizio. |

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
| [ToList](../../groupdocs.metadata.standards.iptc/iptcrecord/tolist)() | Crea un elenco dal pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

**Saperne di più**

* [Utilizzo dei metadati IPTC IIM](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Guarda anche

* class [IptcRecord](../iptcrecord)
* spazio dei nomi [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
