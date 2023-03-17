---
title: PresentationPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un pacchetto di metadati nativi in una presentazione.
type: docs
weight: 1090
url: /it/net/groupdocs.metadata.formats.document/presentationpackage/
---
## PresentationPackage class

Rappresenta un pacchetto di metadati nativi in una presentazione.

```csharp
public class PresentationPackage : DocumentPackage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ApplicationTemplate](../../groupdocs.metadata.formats.document/presentationpackage/applicationtemplate) { get; set; } | Ottiene o imposta il modello dell'applicazione. |
| [Author](../../groupdocs.metadata.formats.document/presentationpackage/author) { get; set; } | Ottiene o imposta l'autore del documento. |
| [Category](../../groupdocs.metadata.formats.document/presentationpackage/category) { get; set; } | Ottiene o imposta la categoria. |
| [Comments](../../groupdocs.metadata.formats.document/presentationpackage/comments) { get; set; } | Ottiene o imposta i commenti. |
| [Company](../../groupdocs.metadata.formats.document/presentationpackage/company) { get; set; } | Ottiene o imposta la società. |
| [ContentStatus](../../groupdocs.metadata.formats.document/presentationpackage/contentstatus) { get; set; } | Ottiene o imposta lo stato del contenuto. Può essere aggiornato solo in un documento PPTX. |
| [ContentType](../../groupdocs.metadata.formats.document/presentationpackage/contenttype) { get; set; } | Ottiene o imposta il tipo di contenuto. Può essere aggiornato solo in un documento PPTX. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [CreatedTime](../../groupdocs.metadata.formats.document/presentationpackage/createdtime) { get; set; } | Ottiene o imposta la data di creazione del documento. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/presentationpackage/hyperlinkbase) { get; set; } | Ottiene o imposta la base del collegamento ipertestuale. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [Keywords](../../groupdocs.metadata.formats.document/presentationpackage/keywords) { get; set; } | Recupera o imposta le parole chiave. |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/presentationpackage/lastprinteddate) { get; set; } | Recupera o imposta l'ultima data stampata. |
| [LastSavedBy](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedby) { get; set; } | Ottiene o imposta il nome dell'ultimo autore. |
| [LastSavedTime](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedtime) { get; } | Ottiene la data e l'ora in cui la presentazione è stata modificata l'ultima volta. |
| [Manager](../../groupdocs.metadata.formats.document/presentationpackage/manager) { get; set; } | Ottiene o imposta il gestore. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [NameOfApplication](../../groupdocs.metadata.formats.document/presentationpackage/nameofapplication) { get; } | Ottiene il nome dell'applicazione che ha creato il documento. |
| [PresentationFormat](../../groupdocs.metadata.formats.document/presentationpackage/presentationformat) { get; } | Ottiene il formato della presentazione. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [RevisionNumber](../../groupdocs.metadata.formats.document/presentationpackage/revisionnumber) { get; set; } | Ottiene o imposta il numero di revisione. |
| [SharedDoc](../../groupdocs.metadata.formats.document/presentationpackage/shareddoc) { get; set; } | Ottiene o imposta un valore che indica se la presentazione è condivisa tra più persone. Può essere aggiornato solo in un documento PPTX. |
| [Subject](../../groupdocs.metadata.formats.document/presentationpackage/subject) { get; set; } | Ottiene o imposta l'oggetto. |
| [Title](../../groupdocs.metadata.formats.document/presentationpackage/title) { get; set; } | Ottiene o imposta il titolo del documento. |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/presentationpackage/totaleditingtime) { get; set; } | Ottiene o imposta il tempo totale di modifica del documento. |
| [Version](../../groupdocs.metadata.formats.document/presentationpackage/version) { get; } | Ottiene la versione dell'applicazione. |

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
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set)(string, bool) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_3)(string, DateTime) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_1)(string, double) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_2)(string, int) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_4)(string, string) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) E[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

**Saperne di più**

* [Lavorare con i metadati in Presentazioni](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Presentations)

### Esempi

Questo esempio mostra come aggiornare le proprietà dei metadati incorporati in una presentazione.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPptx))
{
    var root = metadata.GetRootPackage<PresentationRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    //... 

    metadata.Save(Constants.OutputPptx);
}
```

### Guarda anche

* class [DocumentPackage](../documentpackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
