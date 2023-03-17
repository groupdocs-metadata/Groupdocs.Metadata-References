---
title: LyricsTag
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta i metadati di Lyrics3 v2.00. Ulteriori informazioni sono disponibili allindirizzohttp//id3.org/Lyrics3v2 .
type: docs
weight: 570
url: /it/net/groupdocs.metadata.formats.audio/lyricstag/
---
## LyricsTag class

Rappresenta i metadati di Lyrics3 v2.00. Ulteriori informazioni sono disponibili all'indirizzohttp://id3.org/Lyrics3v2 .

```csharp
public sealed class LyricsTag : CustomPackage
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LyricsTag](lyricstag)() | Inizializza una nuova istanza di[`LyricsTag`](../lyricstag) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AdditionalInfo](../../groupdocs.metadata.formats.audio/lyricstag/additionalinfo) { get; set; } | Ottiene o imposta le informazioni aggiuntive. Questo valore è rappresentato dal campo INF. |
| [Album](../../groupdocs.metadata.formats.audio/lyricstag/album) { get; set; } | Ottiene o imposta il nome dell'album. Questo valore è rappresentato dal campo EAL. |
| [Artist](../../groupdocs.metadata.formats.audio/lyricstag/artist) { get; set; } | Ottiene o imposta il nome dell'artista. Questo valore è rappresentato dal campo EAR. |
| [Author](../../groupdocs.metadata.formats.audio/lyricstag/author) { get; set; } | Ottiene o imposta l'autore. Questo valore è rappresentato dal campo AUT. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [Lyrics](../../groupdocs.metadata.formats.audio/lyricstag/lyrics) { get; set; } | Recupera o imposta i testi. Questo valore è rappresentato dal campo LYR. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [Track](../../groupdocs.metadata.formats.audio/lyricstag/track) { get; set; } | Ottiene o imposta il titolo della traccia. Questo valore è rappresentato dal campo ETT. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [Get](../../groupdocs.metadata.formats.audio/lyricstag/get)(string) | Ottiene il valore del campo con l'id specificato. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| [Remove](../../groupdocs.metadata.formats.audio/lyricstag/remove)(string) | Rimuove il campo con l'id specificato. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| [Set](../../groupdocs.metadata.formats.audio/lyricstag/set)(LyricsField) | Aggiunge o sostituisce il campo Lyrics3 specificato. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) E[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [ToList](../../groupdocs.metadata.formats.audio/lyricstag/tolist)() | Crea un elenco dal pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

Lyrics3 v2.00 utilizza i campi per rappresentare le informazioni. I dati in un campo possono essere costituiti da caratteri ASCII nell'intervallo da 01 a 254 secondo lo standard. Poiché la mappa dei caratteri ASCII è definita solo da 00 a 128 ISO-8859- 1 si potrebbe presumere. I campi numerici sono lunghi 5 o 6 caratteri, a seconda della posizione, e sono riempiti con zeri.

**Saperne di più**

* [Gestione del tag Lyrics](https://docs.groupdocs.com/display/metadatanet/Handling+the+Lyrics+tag)

### Esempi

Questo esempio di codice mostra come leggere il tag Lyrics da un file MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithLyrics))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.Lyrics3V2 != null)
    {
        Console.WriteLine(root.Lyrics3V2.Lyrics);
        Console.WriteLine(root.Lyrics3V2.Album);
        Console.WriteLine(root.Lyrics3V2.Artist);
        Console.WriteLine(root.Lyrics3V2.Track);

        //...

        // In alternativa, puoi scorrere un elenco completo di campi tag
        foreach (var field in root.Lyrics3V2.ToList())
        {
            Console.WriteLine("{0} = {1}", field.ID, field.Data);
        }
    }
}
```

### Guarda anche

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
