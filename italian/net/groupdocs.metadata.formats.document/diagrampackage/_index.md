---
title: DiagramPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un pacchetto di metadati nativi in un formato di diagramma.
type: docs
weight: 890
url: /it/net/groupdocs.metadata.formats.document/diagrampackage/
---
## DiagramPackage class

Rappresenta un pacchetto di metadati nativi in un formato di diagramma.

```csharp
public class DiagramPackage : DocumentPackage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternateNames](../../groupdocs.metadata.formats.document/diagrampackage/alternatenames) { get; set; } | Ottiene o imposta i nomi alternativi per il documento. Può essere aggiornato solo nei formati VDX e VSX. |
| [BuildNumberCreated](../../groupdocs.metadata.formats.document/diagrampackage/buildnumbercreated) { get; } | Ottiene il numero di build completo dell'istanza utilizzata per creare il documento. |
| [BuildNumberEdited](../../groupdocs.metadata.formats.document/diagrampackage/buildnumberedited) { get; } | Ottiene il numero di build dell'ultima istanza utilizzata per modificare il documento. |
| [Category](../../groupdocs.metadata.formats.document/diagrampackage/category) { get; set; } | Ottiene o imposta il testo descrittivo per il tipo di disegno, ad esempio diagramma di flusso o layout ufficio. Questo testo può essere immesso anche nell'interfaccia utente di Microsoft Visio nella casella Categoria nella finestra di dialogo Proprietà. |
| [Company](../../groupdocs.metadata.formats.document/diagrampackage/company) { get; set; } | Ottiene o imposta le informazioni immesse dall'utente che identificano l'azienda che crea il disegno o l'azienda per cui viene creato il disegno. La lunghezza massima è di 63 caratteri. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [Creator](../../groupdocs.metadata.formats.document/diagrampackage/creator) { get; set; } | Recupera o imposta la persona che ha creato o aggiornato per ultimo il file. La lunghezza massima è di 63 caratteri.. |
| [Description](../../groupdocs.metadata.formats.document/diagrampackage/description) { get; set; } | Ottiene o imposta una stringa di testo descrittiva per il documento. Utilizza questo elemento per archiviare informazioni importanti sul documento, ad esempio il suo scopo, le modifiche recenti o in sospeso. Il massimo è di 191 caratteri. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/diagrampackage/hyperlinkbase) { get; set; } | Ottiene o imposta il percorso da utilizzare per i collegamenti ipertestuali relativi (collegamenti ipertestuali per i quali è descritta la posizione del file collegato in relazione al diagramma di Microsoft Visio). Per impostazione predefinita, un percorso di collegamento ipertestuale è relativo al documento corrente a meno che non sia specificato un percorso diverso in questo elemento. La lunghezza massima è di 256 caratteri. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [Keywords](../../groupdocs.metadata.formats.document/diagrampackage/keywords) { get; set; } | Ottiene o imposta una stringa di testo che identifica gli argomenti o altre informazioni importanti sul file, ad esempio il nome del progetto, il nome del client o il numero di versione. La lunghezza massima della stringa è di 63 caratteri. |
| [Language](../../groupdocs.metadata.formats.document/diagrampackage/language) { get; set; } | Ottiene o imposta la lingua del documento. Può essere aggiornato solo nei formati VSD e VSDX. |
| [Manager](../../groupdocs.metadata.formats.document/diagrampackage/manager) { get; set; } | Ottiene o imposta una stringa di testo immessa dall'utente che identifica la persona responsabile del progetto o del dipartimento. La lunghezza massima è di 63 caratteri. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PreviewPicture](../../groupdocs.metadata.formats.document/diagrampackage/previewpicture) { get; set; } | Ottiene o imposta l'immagine di anteprima. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [Subject](../../groupdocs.metadata.formats.document/diagrampackage/subject) { get; set; } | Ottiene o imposta una stringa di testo definita dall'utente che descrive il contenuto del documento. La lunghezza massima è di 63 caratteri. |
| [Template](../../groupdocs.metadata.formats.document/diagrampackage/template) { get; set; } | Ottiene o imposta un valore stringa che specifica il nome file del modello da cui è stato creato il documento. |
| [TimeCreated](../../groupdocs.metadata.formats.document/diagrampackage/timecreated) { get; set; } | Ottiene o imposta un valore di data e ora che indica quando è stato creato il documento. |
| [TimeEdited](../../groupdocs.metadata.formats.document/diagrampackage/timeedited) { get; } | Ottiene un valore di data e ora che indica quando il documento è stato modificato l'ultima volta. |
| [TimePrinted](../../groupdocs.metadata.formats.document/diagrampackage/timeprinted) { get; } | Ottiene un valore di data e ora che indica quando il documento è stato stampato l'ultima volta. |
| [TimeSaved](../../groupdocs.metadata.formats.document/diagrampackage/timesaved) { get; } | Ottiene un valore di data e ora che indica quando il documento è stato salvato l'ultima volta. |
| [Title](../../groupdocs.metadata.formats.document/diagrampackage/title) { get; set; } | Ottiene o imposta una stringa di testo definita dall'utente che funge da titolo descrittivo per il documento. La lunghezza massima è di 63 caratteri. |

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
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set)(string, bool) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_2)(string, DateTime) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_1)(string, double) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_3)(string, string) | Aggiunge o sostituisce la proprietà dei metadati con il nome specificato. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) E[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

**Saperne di più**

* [Lavorare con i metadati in Diagrams](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### Esempi

Questo esempio di codice mostra come estrarre le proprietà dei metadati incorporati da un diagramma.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVsdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    Console.WriteLine(root.DocumentProperties.Creator);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.Language);
    Console.WriteLine(root.DocumentProperties.TimeCreated);
    Console.WriteLine(root.DocumentProperties.Category);

    //... 
}
```

### Guarda anche

* class [DocumentPackage](../documentpackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
