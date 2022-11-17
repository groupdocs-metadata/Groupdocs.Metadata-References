---
title: ID3V1Tag
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un tag ID3v1. Ulteriori informazioni sono disponibili allindirizzohttps//en.wikipedia.org/wiki/ID3ID3v1https//en.wikipedia.org/wiki/ID3ID3v1 .
type: docs
weight: 410
url: /it/net/groupdocs.metadata.formats.audio/id3v1tag/
---
## ID3V1Tag class

Rappresenta un tag ID3v1. Ulteriori informazioni sono disponibili all'indirizzo[https://en.wikipedia.org/wiki/ID3#ID3v1](https://en.wikipedia.org/wiki/ID3#ID3v1) .

```csharp
public sealed class ID3V1Tag : ID3Tag
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ID3V1Tag](id3v1tag)() | Inizializza una nuova istanza di[`ID3V1Tag`](../id3v1tag) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v1tag/album) { get; set; } | Ottiene o imposta l'album. La lunghezza massima è di 30 caratteri. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v1tag/artist) { get; set; } | Ottiene o imposta l'artista. La lunghezza massima è di 30 caratteri. |
| [Comment](../../groupdocs.metadata.formats.audio/id3v1tag/comment) { get; set; } | Ottiene o imposta il commento. La lunghezza massima è di 30 caratteri. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [GenreValue](../../groupdocs.metadata.formats.audio/id3v1tag/genrevalue) { get; } | Ottiene o imposta l'identificatore del genere. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [Title](../../groupdocs.metadata.formats.audio/id3v1tag/title) { get; set; } | Ottiene o imposta il titolo. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v1tag/tracknumber) { get; set; } | Ottiene o imposta il numero della traccia. Presentato solo in un tag ID3v1.1. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v1tag/version) { get; } | Ottiene la versione ID3. Può essere ID3 o ID3v1.1 |
| [Year](../../groupdocs.metadata.formats.audio/id3v1tag/year) { get; set; } | Ottiene o imposta l'anno. La lunghezza massima è di 4 caratteri. |

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

Il tag ID3(v1) è una piccola porzione di dati aggiuntivi alla fine di MP3. Ulteriori informazioni sono disponibili all'indirizzo[http://id3.org/ID3v1](http://id3.org/ID3v1) .

**Scopri di più**

* [Gestione del tag ID3v1](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v1+tag)

### Esempi

Questo esempio di codice mostra come leggere il tag ID3v1 in un file MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V1))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V1 != null)
    {
        Console.WriteLine(root.ID3V1.Album);
        Console.WriteLine(root.ID3V1.Artist);
        Console.WriteLine(root.ID3V1.Title);
        Console.WriteLine(root.ID3V1.Version);
        Console.WriteLine(root.ID3V1.Comment);

        //...
    }
}
```

### Guarda anche

* class [ID3Tag](../id3tag)
* spazio dei nomi [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
