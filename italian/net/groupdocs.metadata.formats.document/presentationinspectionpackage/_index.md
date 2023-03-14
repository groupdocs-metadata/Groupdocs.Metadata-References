---
title: PresentationInspectionPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Contiene informazioni su parti della presentazione che in alcuni casi possono essere considerate come metadati.
type: docs
weight: 1080
url: /it/net/groupdocs.metadata.formats.document/presentationinspectionpackage/
---
## PresentationInspectionPackage class

Contiene informazioni su parti della presentazione che in alcuni casi possono essere considerate come metadati.

```csharp
public sealed class PresentationInspectionPackage : CustomPackage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Comments](../../groupdocs.metadata.formats.document/presentationinspectionpackage/comments) { get; } | Ottiene un array dei commenti. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [HiddenSlides](../../groupdocs.metadata.formats.document/presentationinspectionpackage/hiddenslides) { get; } | Ottiene un array delle diapositive nascoste. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [ClearComments](../../groupdocs.metadata.formats.document/presentationinspectionpackage/clearcomments)() | Rimuove dalla presentazione tutti i commenti degli utenti rilevati. |
| [ClearHiddenSlides](../../groupdocs.metadata.formats.document/presentationinspectionpackage/clearhiddenslides)() | Rimuove tutte le diapositive nascoste rilevate dalla presentazione. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/presentationinspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| override [Sanitize](../../groupdocs.metadata.formats.document/presentationinspectionpackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) E[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

**Saperne di più**

* [Lavorare con i metadati in Presentazioni](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Presentations)

### Esempi

Questo esempio di codice mostra come pulire le proprietà di ispezione in una presentazione.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPpt))
{
    var root = metadata.GetRootPackage<PresentationRootPackage>();

    root.InspectionPackage.ClearComments();
    root.InspectionPackage.ClearHiddenSlides();

    metadata.Save(Constants.OutputPpt);
}
```

### Guarda anche

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
