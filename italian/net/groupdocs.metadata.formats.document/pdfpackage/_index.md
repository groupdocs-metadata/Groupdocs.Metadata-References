---
title: PdfPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta i metadati nativi in un documento PDF.
type: docs
weight: 1030
url: /it/net/groupdocs.metadata.formats.document/pdfpackage/
---
## PdfPackage class

Rappresenta i metadati nativi in un documento PDF.

```csharp
public class PdfPackage : DocumentPackage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/pdfpackage/author) { get; set; } | Ottiene o imposta l'autore del documento. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [CreatedDate](../../groupdocs.metadata.formats.document/pdfpackage/createddate) { get; set; } | Ottiene o imposta la data di creazione del documento. |
| [Creator](../../groupdocs.metadata.formats.document/pdfpackage/creator) { get; } | Ottiene il creatore del documento. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [Keywords](../../groupdocs.metadata.formats.document/pdfpackage/keywords) { get; set; } | Recupera o imposta le parole chiave. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [ModifiedDate](../../groupdocs.metadata.formats.document/pdfpackage/modifieddate) { get; set; } | Ottiene o imposta la data dell'ultima modifica. |
| [Producer](../../groupdocs.metadata.formats.document/pdfpackage/producer) { get; } | Ottiene il produttore del documento. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [Subject](../../groupdocs.metadata.formats.document/pdfpackage/subject) { get; set; } | Ottiene o imposta l'oggetto del documento. |
| [Title](../../groupdocs.metadata.formats.document/pdfpackage/title) { get; set; } | Ottiene o imposta il titolo del documento. |
| [TrappedFlag](../../groupdocs.metadata.formats.document/pdfpackage/trappedflag) { get; set; } | Ottiene o imposta il flag bloccato. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | Rimuove tutte le proprietà dei metadati scrivibili dal pacchetto. |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | Rimuove tutte le proprietà dei metadati incorporati. |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | Rimuove tutte le proprietà dei metadati personalizzati. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | Rimuove una proprietà di metadati scrivibili dal nome specificato. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| [Set](../../groupdocs.metadata.formats.document/pdfpackage/set)(string, string) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) E[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

**Saperne di più**

* [Lavorare con i metadati nei documenti PDF](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)

### Esempi

Questo frammento di codice mostra come aggiornare le proprietà dei metadati incorporati in un documento PDF.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedDate = DateTime.Now;
    root.DocumentProperties.Title = "test title";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    //... 

    metadata.Save(Constants.OutputPdf);
}
```

### Guarda anche

* class [DocumentPackage](../documentpackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
