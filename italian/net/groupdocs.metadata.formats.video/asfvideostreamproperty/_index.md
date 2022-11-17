---
title: AsfVideoStreamProperty
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta i metadati della proprietà del flusso video nel contenitore multimediale ASF.
type: docs
weight: 2370
url: /it/net/groupdocs.metadata.formats.video/asfvideostreamproperty/
---
## AsfVideoStreamProperty class

Rappresenta i metadati della proprietà del flusso video nel contenitore multimediale ASF.

```csharp
public class AsfVideoStreamProperty : AsfBaseStreamProperty
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternateBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/alternatebitrate) { get; } | Ottiene il tasso di perdita RAlt, in bit al secondo, di un leaky bucket che contiene la porzione di dati del flusso senza overflow, escludendo tutto l'overhead del pacchetto di dati ASF. |
| [AverageBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagebitrate) { get; } | Ottiene il bitrate medio. |
| [AverageTimePerFrame](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagetimeperframe) { get; } | Ottiene la durata media, misurata in unità di 100 nanosecondi, di ogni fotogramma. |
| [Bitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/bitrate) { get; } | Ottiene il tasso di perdita R, in bit al secondo, di un leaky bucket che contiene la porzione di dati del flusso senza overflow, escludendo tutto l'overhead del pacchetto di dati ASF. |
| [BitsPerPixels](../../groupdocs.metadata.formats.video/asfvideostreamproperty/bitsperpixels) { get; } | Ottiene i bit per pixel. |
| [Compression](../../groupdocs.metadata.formats.video/asfvideostreamproperty/compression) { get; } | Ottiene l'ID di compressione video. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [EndTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/endtime) { get; } | Ottiene l'ora di presentazione dell'ultimo oggetto più la durata della riproduzione, indicando dove finisce questo flusso multimediale digitale all'interno del contesto della sequenza temporale del file ASF nel suo complesso. |
| [Flags](../../groupdocs.metadata.formats.video/asfbasestreamproperty/flags) { get; } | Ottiene i flag. |
| [ImageHeight](../../groupdocs.metadata.formats.video/asfvideostreamproperty/imageheight) { get; } | Ottiene l'altezza dell'immagine codificata in pixel. |
| [ImageWidth](../../groupdocs.metadata.formats.video/asfvideostreamproperty/imagewidth) { get; } | Ottiene la larghezza dell'immagine codificata in pixel. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [Language](../../groupdocs.metadata.formats.video/asfbasestreamproperty/language) { get; } | Ottiene la lingua del flusso. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [StartTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/starttime) { get; } | Ottiene l'ora di presentazione del primo oggetto, indicando dove inizia questo flusso multimediale digitale all'interno del contesto della sequenza temporale del file ASF nel suo insieme. |
| [StreamNumber](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamnumber) { get; } | Ottiene il numero di questo flusso. |
| [StreamType](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamtype) { get; } | Ottiene il tipo di questo flusso. |

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

* [Lavorare con i metadati nei file ASF](https://docs.groupdocs.com/display/metadatanet/Working+with+Metadata+in+ASF+Files)

### Guarda anche

* class [AsfBaseStreamProperty](../asfbasestreamproperty)
* spazio dei nomi [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
