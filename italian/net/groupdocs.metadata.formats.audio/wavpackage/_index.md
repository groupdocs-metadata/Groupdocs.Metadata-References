---
title: WavPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un pacchetto di metadati nativi in un file audio WAV.
type: docs
weight: 590
url: /it/net/groupdocs.metadata.formats.audio/wavpackage/
---
## WavPackage class

Rappresenta un pacchetto di metadati nativi in un file audio WAV.

```csharp
public sealed class WavPackage : CustomPackage
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WavPackage](wavpackage)() | Inizializza una nuova istanza di[`WavPackage`](../wavpackage) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AudioFormat](../../groupdocs.metadata.formats.audio/wavpackage/audioformat) { get; } | Ottiene il formato audio. PCM = 1 (ovvero quantizzazione lineare). Valori diversi da 1 indicano una qualche forma di compressione. |
| [BitsPerSample](../../groupdocs.metadata.formats.audio/wavpackage/bitspersample) { get; } | Ottiene i bit per valore campione. |
| [BlockAlign](../../groupdocs.metadata.formats.audio/wavpackage/blockalign) { get; } | Ottiene l'allineamento del blocco. |
| [ByteRate](../../groupdocs.metadata.formats.audio/wavpackage/byterate) { get; } | Ottiene la velocità in byte. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [NumberOfChannels](../../groupdocs.metadata.formats.audio/wavpackage/numberofchannels) { get; } | Ottiene il numero di canali. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [SampleRate](../../groupdocs.metadata.formats.audio/wavpackage/samplerate) { get; } | Ottiene la frequenza di campionamento. |

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

* [Gestione dei metadati nei file WAV](https://docs.groupdocs.com/display/metadatanet/Handling+metadata+in+WAV+files)

### Esempi

Questo esempio di codice mostra come estrarre informazioni audio tecniche da un file WAV.

```csharp
using (Metadata metadata = new Metadata(Constants.InputWav))
{
    var root = metadata.GetRootPackage<WavRootPackage>();
    if (root.WavPackage != null)
    {
        Console.WriteLine(root.WavPackage.AudioFormat);
        Console.WriteLine(root.WavPackage.BitsPerSample);
        Console.WriteLine(root.WavPackage.BlockAlign);
        Console.WriteLine(root.WavPackage.ByteRate);
        Console.WriteLine(root.WavPackage.NumberOfChannels);
        Console.WriteLine(root.WavPackage.SampleRate);
    }
}
```

### Guarda anche

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
