---
title: EmlRootPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta il pacchetto radice che consente di lavorare con i metadati in un messaggio di posta elettronica EML.
type: docs
weight: 1390
url: /it/net/groupdocs.metadata.formats.email/emlrootpackage/
---
## EmlRootPackage class

Rappresenta il pacchetto radice che consente di lavorare con i metadati in un messaggio di posta elettronica EML.

```csharp
public class EmlRootPackage : EmailRootPackage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [EmailPackage](../../groupdocs.metadata.formats.email/emlrootpackage/emailpackage) { get; } | Ottiene il pacchetto di metadati EML. (2 properties) |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Ottiene il pacchetto di metadati del tipo di file. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [ClearAttachments](../../groupdocs.metadata.formats.email/emailrootpackage/clearattachments)() | Rimuove tutti gli allegati dal messaggio e-mail. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) e[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

**Scopri di più**

* [Lavorare con le email salvate](https://docs.groupdocs.com/display/metadatanet/Working+with+saved+Emails)

### Esempi

Questo esempio di codice mostra come estrarre i metadati da un messaggio EML.

```csharp
using (Metadata metadata = new Metadata(Constants.InputEml))
{
    var root = metadata.GetRootPackage<EmlRootPackage>();

    Console.WriteLine(root.EmailPackage.Sender);
    Console.WriteLine(root.EmailPackage.Subject);
    foreach (string recipient in root.EmailPackage.Recipients)
    {
        Console.WriteLine(recipient);
    }

    foreach (var attachedFileName in root.EmailPackage.AttachedFileNames)
    {
        Console.WriteLine(attachedFileName);
    }

    foreach (var header in root.EmailPackage.Headers)
    {
        Console.WriteLine("{0} = {1}", header.Name, header.Value);
    }

    //...
}
```

### Guarda anche

* class [EmailRootPackage](../emailrootpackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Email](../../groupdocs.metadata.formats.email)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
