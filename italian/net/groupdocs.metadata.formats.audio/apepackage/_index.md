---
title: ApePackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un pacchetto di metadati APE v2. Ulteriori informazioni sono disponibili allindirizzohttp//wiki.hydrogenaud.io/index.phptitleAPE_keyhttp//wiki.hydrogenaud.io/index.phptitleAPE_key .
type: docs
weight: 380
url: /it/net/groupdocs.metadata.formats.audio/apepackage/
---
## ApePackage class

Rappresenta un pacchetto di metadati APE v2. Ulteriori informazioni sono disponibili all'indirizzo[http://wiki.hydrogenaud.io/index.php?title=APE_key](http://wiki.hydrogenaud.io/index.php?title=APE_key) .

```csharp
public sealed class ApePackage : CustomPackage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Abstract](../../groupdocs.metadata.formats.audio/apepackage/abstract) { get; } | Ottiene il collegamento astratto. |
| [Album](../../groupdocs.metadata.formats.audio/apepackage/album) { get; } | Ottiene l'album. |
| [Artist](../../groupdocs.metadata.formats.audio/apepackage/artist) { get; } | Ottiene l'artista. |
| [Bibliography](../../groupdocs.metadata.formats.audio/apepackage/bibliography) { get; } | Ottiene la bibliografia. |
| [Comment](../../groupdocs.metadata.formats.audio/apepackage/comment) { get; } | Ottiene il commento. |
| [Composer](../../groupdocs.metadata.formats.audio/apepackage/composer) { get; } | Ottiene il compositore. |
| [Conductor](../../groupdocs.metadata.formats.audio/apepackage/conductor) { get; } | Ottiene il conduttore. |
| [Copyright](../../groupdocs.metadata.formats.audio/apepackage/copyright) { get; } | Ottiene il copyright. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [DebutAlbum](../../groupdocs.metadata.formats.audio/apepackage/debutalbum) { get; } | Ottiene l'album di debutto. |
| [File](../../groupdocs.metadata.formats.audio/apepackage/file) { get; } | Ottiene il file. |
| [Genre](../../groupdocs.metadata.formats.audio/apepackage/genre) { get; } | Ottiene il genere. |
| [Isbn](../../groupdocs.metadata.formats.audio/apepackage/isbn) { get; } | Ottiene il numero ISBN con cifra di controllo. Per saperne di più: https://en.wikipedia.org/wiki/International_Standard_Book_Number. |
| [Isrc](../../groupdocs.metadata.formats.audio/apepackage/isrc) { get; } | Ottiene il numero di registrazione standard internazionale. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [Language](../../groupdocs.metadata.formats.audio/apepackage/language) { get; } | Ottiene la lingua. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [PublicationRight](../../groupdocs.metadata.formats.audio/apepackage/publicationright) { get; } | Ottiene la pubblicazione corretta. |
| [Publisher](../../groupdocs.metadata.formats.audio/apepackage/publisher) { get; } | Ottiene l'editore. |
| [RecordLocation](../../groupdocs.metadata.formats.audio/apepackage/recordlocation) { get; } | Ottiene la posizione del record. |
| [Subtitle](../../groupdocs.metadata.formats.audio/apepackage/subtitle) { get; } | Ottiene il sottotitolo. |
| [Title](../../groupdocs.metadata.formats.audio/apepackage/title) { get; } | Ottiene il titolo. |
| [Track](../../groupdocs.metadata.formats.audio/apepackage/track) { get; } | Ottiene il numero della traccia. |

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

* [Gestione del tag APEv2](https://docs.groupdocs.com/display/metadatanet/Handling+the+APEv2+tag)

### Esempi

Questo esempio mostra come leggere il tag APEv2 in un file MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithApe))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ApeV2 != null)
    {
        Console.WriteLine(root.ApeV2.Album);
        Console.WriteLine(root.ApeV2.Title);
        Console.WriteLine(root.ApeV2.Artist);
        Console.WriteLine(root.ApeV2.Composer);
        Console.WriteLine(root.ApeV2.Copyright);
        Console.WriteLine(root.ApeV2.Genre);
        Console.WriteLine(root.ApeV2.Language);

        //...
    }
}
```

### Guarda anche

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
