---
title: ExifPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un pacchetto di metadati EXIF Exchangeable Image File Format.
type: docs
weight: 2790
url: /it/net/groupdocs.metadata.standards.exif/exifpackage/
---
## ExifPackage class

Rappresenta un pacchetto di metadati EXIF (Exchangeable Image File Format).

```csharp
public class ExifPackage : ExifDictionaryBasePackage
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ExifPackage](exifpackage)() | Inizializza una nuova istanza di[`ExifPackage`](../exifpackage) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Artist](../../groupdocs.metadata.standards.exif/exifpackage/artist) { get; set; } | Ottiene o imposta il nome del proprietario della fotocamera, del fotografo o del creatore dell'immagine. |
| [Copyright](../../groupdocs.metadata.standards.exif/exifpackage/copyright) { get; set; } | Ottiene o imposta l'avviso di copyright. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [DateTime](../../groupdocs.metadata.standards.exif/exifpackage/datetime) { get; set; } | Ottiene o imposta la data e l'ora di creazione dell'immagine. Nello standard EXIF, è la data e l'ora in cui il file è stato modificato. |
| [ExifIfdPackage](../../groupdocs.metadata.standards.exif/exifpackage/exififdpackage) { get; } | Ottiene i dati EXIF IFD. |
| [GpsPackage](../../groupdocs.metadata.standards.exif/exifpackage/gpspackage) { get; } | Ottiene i dati GPS. |
| [ImageDescription](../../groupdocs.metadata.standards.exif/exifpackage/imagedescription) { get; set; } | Ottiene o imposta una stringa di caratteri che dà il titolo dell'immagine. Può essere un commento come "1988 picnic aziendale" o simili. |
| [ImageLength](../../groupdocs.metadata.standards.exif/exifpackage/imagelength) { get; set; } | Ottiene o imposta il numero di righe di dati dell'immagine. |
| [ImageWidth](../../groupdocs.metadata.standards.exif/exifpackage/imagewidth) { get; set; } | Ottiene o imposta il numero di colonne di dati dell'immagine, pari al numero di pixel per riga. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Ottiene il tag TIFF con l'id specificato. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [Make](../../groupdocs.metadata.standards.exif/exifpackage/make) { get; set; } | Ottiene o imposta il produttore dell'apparecchiatura di registrazione. Questo è il produttore del DSC, scanner, digitalizzatore video o altra apparecchiatura che ha generato l'immagine. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [Model](../../groupdocs.metadata.standards.exif/exifpackage/model) { get; set; } | Ottiene o imposta il nome del modello o il numero del modello dell'apparecchiatura. Questo è il nome o il numero del modello del DSC, scanner, digitalizzatore video o altra apparecchiatura che ha generato l'immagine. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [Software](../../groupdocs.metadata.standards.exif/exifpackage/software) { get; set; } | Ottiene o imposta il nome e la versione del software o del firmware della fotocamera o del dispositivo di input dell'immagine utilizzato per generare l'immagine. |
| [Thumbnail](../../groupdocs.metadata.standards.exif/exifpackage/thumbnail) { get; } | Ottiene la miniatura dell'immagine rappresentata come un array di byte. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Rimuove tutti i tag TIFF memorizzati nel pacchetto. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Rimuove la proprietà con l'id specificato. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Aggiunge o sostituisce il tag specificato. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) E[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Crea un elenco dal pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

**Saperne di più**

* [Lavorare con i metadati EXIF](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Esempi

Questo esempio di codice mostra come aggiornare le proprietà EXIF comuni.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        // Imposta il pacchetto EXIF se manca
        if (root.ExifPackage == null)
        {
            root.ExifPackage = new ExifPackage();
        }

        root.ExifPackage.Copyright = "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.";
        root.ExifPackage.ImageDescription = "test image";
        root.ExifPackage.Software = "GroupDocs.Metadata";

        //...

        root.ExifPackage.ExifIfdPackage.BodySerialNumber = "test";
        root.ExifPackage.ExifIfdPackage.CameraOwnerName = "GroupDocs";
        root.ExifPackage.ExifIfdPackage.UserComment = "test comment";

        //...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Guarda anche

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* spazio dei nomi [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
