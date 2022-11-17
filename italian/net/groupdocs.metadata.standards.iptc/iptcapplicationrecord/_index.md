---
title: IptcApplicationRecord
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un record dellapplicazione IPTC.
type: docs
weight: 2880
url: /it/net/groupdocs.metadata.standards.iptc/iptcapplicationrecord/
---
## IptcApplicationRecord class

Rappresenta un record dell'applicazione IPTC.

```csharp
public sealed class IptcApplicationRecord : IptcRecord
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [IptcApplicationRecord](iptcapplicationrecord)() | Inizializza una nuova istanza di[`IptcApplicationRecord`](../iptcapplicationrecord) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllKeywords](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/allkeywords) { get; set; } | Recupera o imposta le parole chiave. |
| [ByLine](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/byline) { get; set; } | Ottiene o imposta il nome del creatore dell'oggetto, ad esempio scrittore, fotografo o artista grafico. |
| [ByLines](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylines) { get; set; } | Recupera o imposta i nomi dei creatori dell'oggetto, ad esempio scrittore, fotografo o artista grafico. |
| [ByLineTitle](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylinetitle) { get; set; } | Ottiene o imposta il titolo del creatore o dei creatori dell'oggetto. |
| [ByLineTitles](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylinetitles) { get; set; } | Ottiene o imposta i titoli del creatore o dei creatori dell'oggetto. |
| [CaptionAbstract](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/captionabstract) { get; set; } | Ottiene o imposta una descrizione testuale dell'oggetto, utilizzata in particolare quando l'oggetto non è testo. |
| [City](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/city) { get; set; } | Ottiene o imposta la città. |
| [Contact](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contact) { get; set; } | Ottiene o imposta informazioni sulla persona o sull'organizzazione che possono fornire ulteriori informazioni di background sull'oggetto. |
| [Contacts](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contacts) { get; set; } | Ottiene o imposta informazioni sulla persona o sull'organizzazione che possono fornire ulteriori informazioni di background sull'oggetto. |
| [ContentLocationCode](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationcode) { get; set; } | Ottiene o imposta il codice della posizione del contenuto. |
| [ContentLocationCodes](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationcodes) { get; set; } | Ottiene o imposta i codici di posizione del contenuto. |
| [ContentLocationName](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationname) { get; set; } | Ottiene o imposta il nome della posizione del contenuto. |
| [ContentLocationNames](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationnames) { get; set; } | Ottiene o imposta i nomi delle posizioni dei contenuti. |
| [CopyrightNotice](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/copyrightnotice) { get; set; } | Ottiene o imposta l'avviso di copyright. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [Credit](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/credit) { get; set; } | Ottiene o imposta informazioni sul fornitore dell'oggetto, non necessariamente il proprietario/creatore. |
| [DateCreated](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/datecreated) { get; set; } | Ottiene o imposta la data di creazione del contenuto intellettuale dell'oggetto. |
| [Headline](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/headline) { get; set; } | Ottiene o imposta una voce pubblicabile che fornisce una sintesi del contenuto dell'oggetto. |
| [Item](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/item) { get; } | Ottiene il[`IptcDataSet`](../iptcdataset) con il numero specificato. (3 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [Keywords](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/keywords) { get; set; } | Recupera o imposta le parole chiave. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [ProgramVersion](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/programversion) { get; set; } | Ottiene o imposta la versione del programma. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [RecordNumber](../../groupdocs.metadata.standards.iptc/iptcrecord/recordnumber) { get; } | Ottiene il numero del record. |
| [ReferenceDate](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/referencedate) { get; set; } | Ottiene o imposta la data di una busta precedente a cui fa riferimento l'oggetto corrente. |
| [ReferenceDates](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/referencedates) { get; } | Recupera le date di una busta precedente a cui fa riferimento l'oggetto corrente. |
| [ReleaseDate](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/releasedate) { get; set; } | Ottiene o imposta la data di rilascio. |

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
| [ToList](../../groupdocs.metadata.standards.iptc/iptcrecord/tolist)() | Crea un elenco dal pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

**Scopri di più**

* [Utilizzo dei metadati IPTC IIM](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Guarda anche

* class [IptcRecord](../iptcrecord)
* spazio dei nomi [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
