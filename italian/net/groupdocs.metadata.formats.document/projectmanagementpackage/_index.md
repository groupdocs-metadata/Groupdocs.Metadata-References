---
title: ProjectManagementPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un pacchetto di metadati nativi in un file di gestione del progetto.
type: docs
weight: 1130
url: /it/net/groupdocs.metadata.formats.document/projectmanagementpackage/
---
## ProjectManagementPackage class

Rappresenta un pacchetto di metadati nativi in un file di gestione del progetto.

```csharp
public sealed class ProjectManagementPackage : DocumentPackage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/projectmanagementpackage/author) { get; set; } | Ottiene o imposta l'autore del progetto. |
| [Category](../../groupdocs.metadata.formats.document/projectmanagementpackage/category) { get; set; } | Ottiene o imposta la categoria. |
| [Comments](../../groupdocs.metadata.formats.document/projectmanagementpackage/comments) { get; set; } | Ottiene o imposta i commenti dell'utente. |
| [Company](../../groupdocs.metadata.formats.document/projectmanagementpackage/company) { get; set; } | Ottiene o imposta la società. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [CreationDate](../../groupdocs.metadata.formats.document/projectmanagementpackage/creationdate) { get; set; } | Ottiene o imposta la data di creazione. |
| [Guid](../../groupdocs.metadata.formats.document/projectmanagementpackage/guid) { get; set; } | Ottiene o imposta l'id del progetto. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/projectmanagementpackage/hyperlinkbase) { get; set; } | Ottiene o imposta la base del collegamento ipertestuale. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [Keywords](../../groupdocs.metadata.formats.document/projectmanagementpackage/keywords) { get; set; } | Recupera o imposta le parole chiave. |
| [LastAuthor](../../groupdocs.metadata.formats.document/projectmanagementpackage/lastauthor) { get; set; } | Ottiene o imposta l'ultimo autore. |
| [LastPrinted](../../groupdocs.metadata.formats.document/projectmanagementpackage/lastprinted) { get; set; } | Ottiene o imposta l'ora dell'ultima stampa del progetto. |
| [LastSaved](../../groupdocs.metadata.formats.document/projectmanagementpackage/lastsaved) { get; set; } | Ottiene o imposta la data in cui il progetto è stato salvato l'ultima volta. |
| [Manager](../../groupdocs.metadata.formats.document/projectmanagementpackage/manager) { get; set; } | Ottiene o imposta il project manager. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [Revision](../../groupdocs.metadata.formats.document/projectmanagementpackage/revision) { get; set; } | Ottiene o imposta il numero di revisione. |
| [SaveVersion](../../groupdocs.metadata.formats.document/projectmanagementpackage/saveversion) { get; } | Ottiene la versione di Microsoft Office Project da cui è stato salvato un file di progetto. |
| [Subject](../../groupdocs.metadata.formats.document/projectmanagementpackage/subject) { get; set; } | Ottiene o imposta l'oggetto. |
| [Template](../../groupdocs.metadata.formats.document/projectmanagementpackage/template) { get; set; } | Ottiene o imposta il modello. |
| [Title](../../groupdocs.metadata.formats.document/projectmanagementpackage/title) { get; set; } | Ottiene o imposta il titolo. |

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
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set)(string, bool) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_3)(string, DateTime) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_1)(string, double) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_2)(string, int) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_4)(string, string) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) E[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

**Saperne di più**

* [Utilizzo dei metadati nei formati ProjectManagement](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+ProjectManagement+formats)

### Esempi

Questo esempio di codice mostra come aggiornare le proprietà integrate in un documento ProjectManagement.

```csharp
using (Metadata metadata = new Metadata(Constants.InputMpp))
{
    var root = metadata.GetRootPackage<ProjectManagementRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreationDate = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Comments = "test comment";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    //... 

    metadata.Save(Constants.OutputMpp);
}
```

### Guarda anche

* class [DocumentPackage](../documentpackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
