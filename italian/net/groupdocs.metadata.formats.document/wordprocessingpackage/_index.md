---
title: WordProcessingPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un pacchetto di metadati nativi in un documento di elaborazione testi.
type: docs
weight: 1280
url: /it/net/groupdocs.metadata.formats.document/wordprocessingpackage/
---
## WordProcessingPackage class

Rappresenta un pacchetto di metadati nativi in un documento di elaborazione testi.

```csharp
public class WordProcessingPackage : DocumentPackage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/wordprocessingpackage/author) { get; set; } | Ottiene o imposta l'autore del documento. |
| [BytesInDocument](../../groupdocs.metadata.formats.document/wordprocessingpackage/bytesindocument) { get; } | Ottiene una stima del numero di byte nel documento. |
| [Category](../../groupdocs.metadata.formats.document/wordprocessingpackage/category) { get; set; } | Ottiene o imposta la categoria. |
| [Comments](../../groupdocs.metadata.formats.document/wordprocessingpackage/comments) { get; set; } | Ottiene o imposta i commenti. |
| [Company](../../groupdocs.metadata.formats.document/wordprocessingpackage/company) { get; set; } | Ottiene o imposta la società. |
| [ContentStatus](../../groupdocs.metadata.formats.document/wordprocessingpackage/contentstatus) { get; set; } | Ottiene o imposta lo stato del contenuto. |
| [ContentType](../../groupdocs.metadata.formats.document/wordprocessingpackage/contenttype) { get; set; } | Ottiene o imposta il tipo di contenuto del documento. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [CreatedTime](../../groupdocs.metadata.formats.document/wordprocessingpackage/createdtime) { get; set; } | Ottiene o imposta la data di creazione del documento. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/wordprocessingpackage/hyperlinkbase) { get; set; } | Ottiene o imposta la base del collegamento ipertestuale. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [Keywords](../../groupdocs.metadata.formats.document/wordprocessingpackage/keywords) { get; set; } | Recupera o imposta le parole chiave. |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/wordprocessingpackage/lastprinteddate) { get; set; } | Recupera o imposta l'ultima data stampata. |
| [LastSavedBy](../../groupdocs.metadata.formats.document/wordprocessingpackage/lastsavedby) { get; set; } | Ottiene o imposta il nome dell'ultimo autore. |
| [LastSavedTime](../../groupdocs.metadata.formats.document/wordprocessingpackage/lastsavedtime) { get; set; } | Ottiene o imposta l'ora dell'ultimo salvataggio. |
| [LinksUpToDate](../../groupdocs.metadata.formats.document/wordprocessingpackage/linksuptodate) { get; set; } | Ottiene o imposta un valore che indica se i collegamenti ipertestuali nel documento sono aggiornati. |
| [Manager](../../groupdocs.metadata.formats.document/wordprocessingpackage/manager) { get; set; } | Ottiene o imposta il gestore. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [NameOfApplication](../../groupdocs.metadata.formats.document/wordprocessingpackage/nameofapplication) { get; } | Ottiene il nome dell'applicazione. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [RevisionNumber](../../groupdocs.metadata.formats.document/wordprocessingpackage/revisionnumber) { get; set; } | Ottiene o imposta il numero di revisione. |
| [Subject](../../groupdocs.metadata.formats.document/wordprocessingpackage/subject) { get; set; } | Ottiene o imposta l'oggetto. |
| [Template](../../groupdocs.metadata.formats.document/wordprocessingpackage/template) { get; set; } | Ottiene o imposta il modello. |
| [Title](../../groupdocs.metadata.formats.document/wordprocessingpackage/title) { get; set; } | Ottiene o imposta il titolo del documento. |
| [TitlesOfParts](../../groupdocs.metadata.formats.document/wordprocessingpackage/titlesofparts) { get; } | Ottiene i titoli delle parti del documento. Sola lettura. |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/wordprocessingpackage/totaleditingtime) { get; set; } | Ottiene o imposta il tempo totale di modifica in minuti. |
| [Version](../../groupdocs.metadata.formats.document/wordprocessingpackage/version) { get; } | Ottiene il numero di versione dell'applicazione che ha creato il documento. |

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
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set)(string, bool) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_3)(string, DateTime) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_1)(string, double) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_2)(string, int) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_4)(string, string) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) e[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

**Scopri di più**

* [Lavorare con i metadati nei documenti di WordProcessing](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### Esempi

Questo esempio di codice mostra come aggiornare le proprietà dei metadati incorporati in un documento di elaborazione di testi.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDoc))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    //... 

    metadata.Save(Constants.OutputDoc);
}
```

### Guarda anche

* class [DocumentPackage](../documentpackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
