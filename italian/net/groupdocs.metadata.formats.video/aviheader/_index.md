---
title: AviHeader
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta la struttura AVIMAINHEADER in un video AVI.
type: docs
weight: 2380
url: /it/net/groupdocs.metadata.formats.video/aviheader/
---
## AviHeader class

Rappresenta la struttura AVIMAINHEADER in un video AVI.

```csharp
public sealed class AviHeader : CustomPackage
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [AviHeader](aviheader)() | Inizializza una nuova istanza di[`AviHeader`](../aviheader) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AviHeaderFlags](../../groupdocs.metadata.formats.video/aviheader/aviheaderflags) { get; } | Ottiene una combinazione bit per bit di zero o più flag AVI. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [Height](../../groupdocs.metadata.formats.video/aviheader/height) { get; } | Ottiene l'altezza del file AVI in pixel. |
| [InitialFrames](../../groupdocs.metadata.formats.video/aviheader/initialframes) { get; } | Ottiene il frame iniziale per i file interleaved.  I file non interleaved devono specificare zero. Se stai creando file interleaved, specifica il numero di fotogrammi nel file prima del fotogramma iniziale della sequenza AVI in questo membro. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MaxBytesPerSec](../../groupdocs.metadata.formats.video/aviheader/maxbytespersec) { get; } | Ottiene la velocità dati massima approssimativa del file.  Questo valore indica il numero di byte al secondo che il sistema deve gestire per presentare una sequenza AVI come specificato dagli altri parametri contenuti nei blocchi dell'intestazione principale e dell'intestazione del flusso. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [MicroSecPerFrame](../../groupdocs.metadata.formats.video/aviheader/microsecperframe) { get; } | Ottiene il numero di microsecondi tra i frame. Questo valore indica i tempi complessivi per il file. |
| [PaddingGranularity](../../groupdocs.metadata.formats.video/aviheader/paddinggranularity) { get; } | Ottiene l'allineamento per i dati, in byte. Completa i dati con multipli di questo valore. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [Streams](../../groupdocs.metadata.formats.video/aviheader/streams) { get; } | Ottiene il numero di flussi nel file. Ad esempio, un file con audio e video ha due flussi. |
| [SuggestedBufferSize](../../groupdocs.metadata.formats.video/aviheader/suggestedbuffersize) { get; } | Ottiene la dimensione del buffer suggerita per la lettura del file.  Generalmente, questa dimensione dovrebbe essere abbastanza grande da contenere il blocco più grande del file. Se impostato su zero, o se è troppo piccolo, il software di riproduzione dovrà riallocare la memoria durante la riproduzione, il che ridurrà le prestazioni. Per un file interleaved, la dimensione del buffer dovrebbe essere abbastanza grande da leggere un intero record e non solo un blocco. |
| [TotalFrames](../../groupdocs.metadata.formats.video/aviheader/totalframes) { get; } | Ottiene il numero totale di frame di dati nel file. |
| [Width](../../groupdocs.metadata.formats.video/aviheader/width) { get; } | Ottiene la larghezza del file AVI in pixel. |

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

* [Lavorare con i metadati nei file AVI](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+AVI+files)

### Guarda anche

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
