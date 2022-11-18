---
title: ID3V2Tag
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un tag ID3v2. Ulteriori informazioni sono disponibili allindirizzohttps//en.wikipedia.org/wiki/ID3ID3v2https//en.wikipedia.org/wiki/ID3ID3v2 .
type: docs
weight: 490
url: /it/net/groupdocs.metadata.formats.audio/id3v2tag/
---
## ID3V2Tag class

Rappresenta un tag ID3v2. Ulteriori informazioni sono disponibili all'indirizzo[https://en.wikipedia.org/wiki/ID3#ID3v2](https://en.wikipedia.org/wiki/ID3#ID3v2) .

```csharp
public sealed class ID3V2Tag : ID3Tag
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ID3V2Tag](id3v2tag)() | Inizializza una nuova istanza di[`ID3V2Tag`](../id3v2tag) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v2tag/album) { get; set; } | Ottiene o imposta il titolo dell'album/film/programma. Questo valore è rappresentato dal frame TALB. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v2tag/artist) { get; set; } | Ottiene o imposta Lead artist(s)/Lead performer(s)/Soloist(s)/Performing group. Questo valore è rappresentato dal frame TPE1. |
| [AttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/attachedpictures) { get; set; } | Ottiene o imposta le immagini allegate direttamente correlate al file audio. Questo valore è rappresentato dal frame APIC. |
| [Band](../../groupdocs.metadata.formats.audio/id3v2tag/band) { get; set; } | Ottiene o imposta Banda/Orchestra/Accompagnamento. Questo valore è rappresentato dal frame TPE2. |
| [BitsPerMinute](../../groupdocs.metadata.formats.audio/id3v2tag/bitsperminute) { get; set; } | Ottiene o imposta il numero di battiti al minuto nella parte principale dell'audio. Questo valore è rappresentato dal frame TBPM. |
| [Comments](../../groupdocs.metadata.formats.audio/id3v2tag/comments) { get; set; } | Recupera o imposta i commenti dell'utente. Questo valore è rappresentato dal frame COMM. Il frame è destinato a qualsiasi tipo di informazione full text che non rientra in nessun altro frame. |
| [Composers](../../groupdocs.metadata.formats.audio/id3v2tag/composers) { get; set; } | Ottiene o imposta i compositori. I nomi sono separati dal carattere "/". Questo valore è rappresentato dal frame TCOM. |
| [ContentType](../../groupdocs.metadata.formats.audio/id3v2tag/contenttype) { get; set; } | Ottiene o imposta il tipo di contenuto. Questo valore è rappresentato dal frame TCON. |
| [Copyright](../../groupdocs.metadata.formats.audio/id3v2tag/copyright) { get; set; } | Ottiene o imposta il messaggio di copyright. Questo valore è rappresentato dal frame TCOP. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [Date](../../groupdocs.metadata.formats.audio/id3v2tag/date) { get; set; } | Ottiene o imposta una stringa numerica nel formato DDMM contenente la data della registrazione. Questo campo è sempre lungo quattro caratteri. Questo valore è rappresentato dal frame TDAT. |
| [EncodedBy](../../groupdocs.metadata.formats.audio/id3v2tag/encodedby) { get; set; } | Ottiene o imposta il nome della persona o dell'organizzazione che ha codificato il file audio. Questo valore è rappresentato dal frame TENC. |
| [Isrc](../../groupdocs.metadata.formats.audio/id3v2tag/isrc) { get; set; } | Ottiene o imposta l'ISRC (International Standard Recording Code) (12 caratteri). Questo valore è rappresentato dal frame TSRC. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [LengthInMilliseconds](../../groupdocs.metadata.formats.audio/id3v2tag/lengthinmilliseconds) { get; set; } | Ottiene o imposta la lunghezza del file audio in millisecondi, rappresentata come una stringa numerica. Questo valore è rappresentato dal frame TLEN. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [MusicalKey](../../groupdocs.metadata.formats.audio/id3v2tag/musicalkey) { get; set; } | Ottiene o imposta la chiave musicale in cui inizia il suono. Questo valore è rappresentato dal frame TKEY. |
| [OriginalAlbum](../../groupdocs.metadata.formats.audio/id3v2tag/originalalbum) { get; set; } | Recupera o imposta il titolo originale dell'album/film/programma. Questo valore è rappresentato dal frame TOAL. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [Publisher](../../groupdocs.metadata.formats.audio/id3v2tag/publisher) { get; set; } | Ottiene o imposta il nome dell'etichetta o dell'editore. Questo valore è rappresentato dal frame TPUB. |
| [SizeInBytes](../../groupdocs.metadata.formats.audio/id3v2tag/sizeinbytes) { get; set; } | Ottiene o imposta la dimensione del file audio in byte, escluso il tag ID3v2, rappresentato come una stringa numerica. Questo valore è rappresentato dal frame TSIZ. |
| [SoftwareHardware](../../groupdocs.metadata.formats.audio/id3v2tag/softwarehardware) { get; set; } | Ottiene o imposta il codificatore audio utilizzato e le sue impostazioni quando il file è stato codificato. Questo valore è rappresentato dal frame TSSE. |
| [Subtitle](../../groupdocs.metadata.formats.audio/id3v2tag/subtitle) { get; set; } | Ottiene o imposta il perfezionamento Sottotitolo/Descrizione. Questo valore è rappresentato dal frame TIT3. |
| [TagSize](../../groupdocs.metadata.formats.audio/id3v2tag/tagsize) { get; } | Ottiene la dimensione del tag. |
| [Time](../../groupdocs.metadata.formats.audio/id3v2tag/time) { get; set; } | Ottiene o imposta una stringa numerica nel formato HHMM contenente l'ora della registrazione. Questo campo è sempre lungo quattro caratteri. Questo valore è rappresentato dal frame TIME. |
| [Title](../../groupdocs.metadata.formats.audio/id3v2tag/title) { get; set; } | Ottiene o imposta Titolo/Nome brano/Descrizione contenuto. Questo valore è rappresentato dal frame TIT2. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v2tag/tracknumber) { get; set; } | Ottiene o imposta una stringa numerica contenente il numero d'ordine del file audio sulla sua registrazione originale. Questo valore è rappresentato dal frame TRCK. |
| [TrackPlayCounter](../../groupdocs.metadata.formats.audio/id3v2tag/trackplaycounter) { get; } | Ottiene il numero di volte in cui il file è stato riprodotto. Questo valore è rappresentato dal frame PCNT. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v2tag/version) { get; } | Ottiene la versione ID3. |
| [Year](../../groupdocs.metadata.formats.audio/id3v2tag/year) { get; set; } | Ottiene o imposta una stringa numerica con un anno della registrazione. Questo frame è sempre lungo quattro caratteri (fino all'anno 10000). Questo valore è rappresentato dal frame TYER. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../groupdocs.metadata.formats.audio/id3v2tag/add)(ID3V2TagFrame) | Aggiunge una cornice al tag. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [Clear](../../groupdocs.metadata.formats.audio/id3v2tag/clear)(string) | Rimuove tutti i frame con l'id specificato. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [Get](../../groupdocs.metadata.formats.audio/id3v2tag/get)(string) | Ottiene un array di frame con l'id specificato. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| [Remove](../../groupdocs.metadata.formats.audio/id3v2tag/remove)(ID3V2TagFrame) | Rimuove il fotogramma specificato dal tag. |
| [RemoveAttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/removeattachedpictures)() | Rimuove tutte le immagini allegate memorizzate nei frame APIC. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| [Set](../../groupdocs.metadata.formats.audio/id3v2tag/set)(ID3V2TagFrame) | Rimuove tutti i frame con lo stesso id di quello specificato e aggiunge il nuovo frame al tag. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) e[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [ToList](../../groupdocs.metadata.formats.audio/id3v2tag/tolist)() | Crea un elenco dal pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

**Scopri di più**

* [Gestione del tag ID3v2](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Esempi

Questo esempio mostra come leggere il tag ID3v2 in un file MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V2 != null)
    {
        Console.WriteLine(root.ID3V2.Album);
        Console.WriteLine(root.ID3V2.Artist);
        Console.WriteLine(root.ID3V2.Band);
        Console.WriteLine(root.ID3V2.Title);
        Console.WriteLine(root.ID3V2.Composers);
        Console.WriteLine(root.ID3V2.Copyright);
        Console.WriteLine(root.ID3V2.Publisher);
        Console.WriteLine(root.ID3V2.OriginalAlbum);
        Console.WriteLine(root.ID3V2.MusicalKey);

        if (root.ID3V2.AttachedPictures != null)
        {
            foreach (var attachedPicture in root.ID3V2.AttachedPictures)
            {
                Console.WriteLine(attachedPicture.AttachedPictureType);
                Console.WriteLine(attachedPicture.MimeType);
                Console.WriteLine(attachedPicture.Description);

                //...
            }
        }

        //...
    }
}
```

### Guarda anche

* class [ID3Tag](../id3tag)
* spazio dei nomi [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
