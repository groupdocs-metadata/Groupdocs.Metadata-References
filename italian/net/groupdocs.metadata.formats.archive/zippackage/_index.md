---
title: ZipPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta i metadati dellarchivio ZIP.
type: docs
weight: 360
url: /it/net/groupdocs.metadata.formats.archive/zippackage/
---
## ZipPackage class

Rappresenta i metadati dell'archivio ZIP.

```csharp
public sealed class ZipPackage : CustomPackage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Comment](../../groupdocs.metadata.formats.archive/zippackage/comment) { get; set; } | Ottiene o imposta il commento dell'archivio ZIP creato da un utente. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [Files](../../groupdocs.metadata.formats.archive/zippackage/files) { get; } | Ottiene un array di[`ZipFile`](../zipfile) voci all'interno dell'archivio ZIP. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [TotalEntries](../../groupdocs.metadata.formats.archive/zippackage/totalentries) { get; } | Ottiene il numero totale di voci all'interno dell'archivio ZIP. |

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

* [Lavorare con archivi ZIP](https://docs.groupdocs.com/display/metadatanet/Working+with+ZIP+archives)

### Esempi

Il seguente frammento di codice mostra come ottenere i metadati da un archivio ZIP.

```csharp
Encoding encoding = Encoding.GetEncoding(866);

using (Metadata metadata = new Metadata(Constants.InputZip))
{
    var root = metadata.GetRootPackage<ZipRootPackage>();

    Console.WriteLine(root.ZipPackage.Comment);
    Console.WriteLine(root.ZipPackage.TotalEntries);

    foreach (var file in root.ZipPackage.Files)
    {
        Console.WriteLine(file.Name);
        Console.WriteLine(file.CompressedSize);
        Console.WriteLine(file.CompressionMethod);
        Console.WriteLine(file.Flags);
        Console.WriteLine(file.ModificationDateTime);
        Console.WriteLine(file.UncompressedSize);

        // Usa una codifica specifica per i nomi dei file
        Console.WriteLine(encoding.GetString(file.RawName));
    }
}
```

### Guarda anche

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Archive](../../groupdocs.metadata.formats.archive)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
