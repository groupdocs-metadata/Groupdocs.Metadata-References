---
title: MatroskaVideoTrack
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta i metadati video in un video Matroska.
type: docs
weight: 2610
url: /it/net/groupdocs.metadata.formats.video/matroskavideotrack/
---
## MatroskaVideoTrack class

Rappresenta i metadati video in un video Matroska.

```csharp
public class MatroskaVideoTrack : MatroskaTrack
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlphaMode](../../groupdocs.metadata.formats.video/matroskavideotrack/alphamode) { get; } | Ottiene la modalità video alfa. La presenza di questo elemento indica che l'elemento BlockAdditional potrebbe contenere dati Alpha. |
| [CodecID](../../groupdocs.metadata.formats.video/matroskatrack/codecid) { get; } | Ottiene un ID corrispondente al codec. |
| [CodecName](../../groupdocs.metadata.formats.video/matroskatrack/codecname) { get; } | Ottiene una stringa leggibile specificando il codec. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [DefaultDuration](../../groupdocs.metadata.formats.video/matroskatrack/defaultduration) { get; } | Ottiene il numero di nanosecondi (non ridimensionato tramite[`TimecodeScale`](../matroskasegment/timecodescale) ) per fotogramma. |
| [DisplayHeight](../../groupdocs.metadata.formats.video/matroskavideotrack/displayheight) { get; } | Ottiene l'altezza dei fotogrammi video da visualizzare. Si applica al fotogramma video dopo il ritaglio (PixelCrop* Elements). |
| [DisplayUnit](../../groupdocs.metadata.formats.video/matroskavideotrack/displayunit) { get; } | Ottiene il come[`DisplayWidth`](./displaywidth) E[`DisplayHeight`](./displayheight) sono interpretati. |
| [DisplayWidth](../../groupdocs.metadata.formats.video/matroskavideotrack/displaywidth) { get; } | Ottiene la larghezza dei fotogrammi video da visualizzare. Si applica al fotogramma video dopo il ritaglio (PixelCrop* Elements). |
| [FieldOrder](../../groupdocs.metadata.formats.video/matroskavideotrack/fieldorder) { get; } | Ottiene la dichiarazione dell'ordinamento dei campi del video. Se FlagInterlaced non è impostato su 1, questo elemento DEVE essere ignorato. |
| [FlagEnabled](../../groupdocs.metadata.formats.video/matroskatrack/flagenabled) { get; } | Ottiene il flag abilitato, vero se la traccia è utilizzabile. |
| [FlagInterlaced](../../groupdocs.metadata.formats.video/matroskavideotrack/flaginterlaced) { get; } | Ottiene un flag per dichiarare se il video è noto per essere progressivo o interlacciato e, se applicabile, per dichiarare i dettagli sull'interlacciamento. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [Language](../../groupdocs.metadata.formats.video/matroskatrack/language) { get; } | Ottiene la lingua della traccia nella forma delle lingue Matroska. Questo elemento DEVE essere ignorato se il[`LanguageIetf`](../matroskatrack/languageietf) L'elemento è utilizzato nella stessa TrackEntry. |
| [LanguageIetf](../../groupdocs.metadata.formats.video/matroskatrack/languageietf) { get; } | Ottiene la lingua della traccia in base a BCP 47 e utilizzando il registro dei sottotag della lingua IANA. Se viene utilizzato questo elemento, qualsiasi[`Language`](../matroskatrack/language) Gli elementi utilizzati nella stessa TrackEntry DEVONO essere ignorati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [Name](../../groupdocs.metadata.formats.video/matroskatrack/name) { get; } | Ottiene il nome della traccia leggibile dall'uomo. |
| [PixelCropBottom](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropbottom) { get; } | Ottiene il numero di pixel video da rimuovere nella parte inferiore dell'immagine. |
| [PixelCropLeft](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropleft) { get; } | Ottiene il numero di pixel video da rimuovere a sinistra dell'immagine. |
| [PixelCropRight](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropright) { get; } | Ottiene il numero di pixel video da rimuovere a destra dell'immagine. |
| [PixelCropTop](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcroptop) { get; } | Ottiene il numero di pixel video da rimuovere nella parte superiore dell'immagine. |
| [PixelHeight](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelheight) { get; } | Ottiene l'altezza dei fotogrammi video codificati in pixel. |
| [PixelWidth](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelwidth) { get; } | Ottiene la larghezza dei fotogrammi video codificati in pixel. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [StereoMode](../../groupdocs.metadata.formats.video/matroskavideotrack/stereomode) { get; } | Ottiene la modalità video stereo-3D. |
| [TrackNumber](../../groupdocs.metadata.formats.video/matroskatrack/tracknumber) { get; } | Ottiene il numero di traccia utilizzato nell'intestazione del blocco. L'utilizzo di più di 127 tracce non è consigliato, sebbene il design ne consenta un numero illimitato. |
| [TrackType](../../groupdocs.metadata.formats.video/matroskatrack/tracktype) { get; } | Ottiene il tipo di traccia. |
| [TrackUid](../../groupdocs.metadata.formats.video/matroskatrack/trackuid) { get; } | Ottiene l'ID univoco per identificare la traccia. Questo DOVREBBE essere mantenuto lo stesso quando si esegue una copia diretta della traccia in un altro file. |

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

* [Lavorare con i metadati nei file Matroska (MKV).](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### Guarda anche

* class [MatroskaTrack](../matroskatrack)
* spazio dei nomi [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
