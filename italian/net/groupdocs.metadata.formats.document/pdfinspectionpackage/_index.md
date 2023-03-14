---
title: PdfInspectionPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Contiene informazioni su parti di documenti PDF che in alcuni casi possono essere considerate metadati.
type: docs
weight: 1020
url: /it/net/groupdocs.metadata.formats.document/pdfinspectionpackage/
---
## PdfInspectionPackage class

Contiene informazioni su parti di documenti PDF che in alcuni casi possono essere considerate metadati.

```csharp
public sealed class PdfInspectionPackage : CustomPackage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Annotations](../../groupdocs.metadata.formats.document/pdfinspectionpackage/annotations) { get; } | Ottiene un array delle annotazioni. |
| [Attachments](../../groupdocs.metadata.formats.document/pdfinspectionpackage/attachments) { get; } | Ottiene un array degli allegati. |
| [Bookmarks](../../groupdocs.metadata.formats.document/pdfinspectionpackage/bookmarks) { get; } | Ottiene un array dei segnalibri. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/pdfinspectionpackage/digitalsignatures) { get; } | Ottiene un array delle firme digitali. |
| [Fields](../../groupdocs.metadata.formats.document/pdfinspectionpackage/fields) { get; } | Ottiene un array dei campi del modulo. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [ClearAnnotations](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearannotations)() | Rimuove tutte le annotazioni rilevate dal documento. |
| [ClearAttachments](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearattachments)() | Rimuove tutti gli allegati rilevati dal documento. |
| [ClearBookmarks](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearbookmarks)() | Rimuove tutti i segnalibri rilevati dal documento. |
| [ClearDigitalSignatures](../../groupdocs.metadata.formats.document/pdfinspectionpackage/cleardigitalsignatures)() | Rimuove tutte le firme digitali rilevate dal documento. |
| [ClearFields](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearfields)() | Rimuove tutti i campi modulo rilevati dal documento. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/pdfinspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| override [Sanitize](../../groupdocs.metadata.formats.document/pdfinspectionpackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) E[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

**Saperne di più**

* [Lavorare con i metadati nei documenti PDF](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)

### Esempi

Questo esempio di codice mostra come rimuovere le proprietà di ispezione in un documento PDF.

```csharp
using (Metadata metadata = new Metadata(Constants.SignedPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    root.InspectionPackage.ClearAnnotations();
    root.InspectionPackage.ClearAttachments();
    root.InspectionPackage.ClearFields();
    root.InspectionPackage.ClearBookmarks();
    root.InspectionPackage.ClearDigitalSignatures();

    metadata.Save(Constants.OutputPdf);
}
```

### Guarda anche

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
