---
title: TorrentRootPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta il pacchetto root destinato a funzionare con i metadati di un file TORRENT.
type: docs
weight: 2200
url: /it/net/groupdocs.metadata.formats.peer2peer/torrentrootpackage/
---
## TorrentRootPackage class

Rappresenta il pacchetto root destinato a funzionare con i metadati di un file TORRENT.

```csharp
public class TorrentRootPackage : RootMetadataPackage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Ottiene il pacchetto di metadati del tipo di file. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [TorrentPackage](../../groupdocs.metadata.formats.peer2peer/torrentrootpackage/torrentpackage) { get; } | Ottiene il pacchetto di metadati del file TORRENT. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) E[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

**Saperne di più**

* [Lavorare con i file TORRENT](https://docs.groupdocs.com/display/metadatanet/Working+with+TORRENT+files)

### Esempi

Questo esempio di codice mostra come leggere i metadati di un file TORRENT.

```csharp
using (Metadata metadata = new Metadata(Constants.InputTorrent))
{
    var root = metadata.GetRootPackage<TorrentRootPackage>();

    Console.WriteLine(root.TorrentPackage.Announce);
    Console.WriteLine(root.TorrentPackage.Comment);
    Console.WriteLine(root.TorrentPackage.CreatedBy);
    Console.WriteLine(root.TorrentPackage.CreationDate);
    foreach (var file in root.TorrentPackage.SharedFiles)
    {
        Console.WriteLine(file.Name);
        Console.WriteLine(file.Length);
    }

    //...
}
```

### Guarda anche

* class [RootMetadataPackage](../../groupdocs.metadata.common/rootmetadatapackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Peer2Peer](../../groupdocs.metadata.formats.peer2peer)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
