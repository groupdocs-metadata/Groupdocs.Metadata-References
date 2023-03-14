---
title: XmpResourceRef
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un riferimento in più parti a una risorsa. Utilizzato per indicare versioni precedenti originali di interpretazioni originali per documenti derivati e così via.
type: docs
weight: 3550
url: /it/net/groupdocs.metadata.standards.xmp/xmpresourceref/
---
## XmpResourceRef class

Rappresenta un riferimento in più parti a una risorsa. Utilizzato per indicare versioni precedenti, originali di interpretazioni, originali per documenti derivati e così via.

```csharp
public sealed class XmpResourceRef : XmpComplexType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XmpResourceRef](xmpresourceref)() | Inizializza una nuova istanza di[`XmpResourceRef`](../xmpresourceref) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternatePaths](../../groupdocs.metadata.standards.xmp/xmpresourceref/alternatepaths) { get; set; } | Ottiene o imposta i percorsi o gli URL dei file di fallback della risorsa di riferimento. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [DocumentID](../../groupdocs.metadata.standards.xmp/xmpresourceref/documentid) { get; set; } | Ottiene o imposta il valore della proprietà xmpMM:DocumentID dalla risorsa di riferimento. |
| [FilePath](../../groupdocs.metadata.standards.xmp/xmpresourceref/filepath) { get; set; } | Ottiene o imposta il percorso del file o l'URL della risorsa di riferimento. |
| [InstanceID](../../groupdocs.metadata.standards.xmp/xmpresourceref/instanceid) { get; set; } | Ottiene o imposta il valore della proprietà xmpMM:InstanceID dalla risorsa di riferimento. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [LastModifyDate](../../groupdocs.metadata.standards.xmp/xmpresourceref/lastmodifydate) { get; set; } | Ottiene o imposta il valore di stEvt:quando per l'ultima volta è stato scritto il file. |
| [Manager](../../groupdocs.metadata.standards.xmp/xmpresourceref/manager) { get; set; } | Ottiene o imposta xmpMM:Manager della risorsa di riferimento. |
| [ManagerVariant](../../groupdocs.metadata.standards.xmp/xmpresourceref/managervariant) { get; set; } | Ottiene o imposta xmpMM:Manager della risorsa di riferimento. |
| [ManageTo](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageto) { get; set; } | Ottiene o imposta xmpMM:ManageTo della risorsa di riferimento. |
| [ManageUI](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageui) { get; set; } | Ottiene o imposta xmpMM:ManageUI. della risorsa di riferimento |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Ottiene gli URI dello spazio dei nomi utilizzati in[`XmpComplexType`](../xmpcomplextype) istanza. |
| [PartMapping](../../groupdocs.metadata.standards.xmp/xmpresourceref/partmapping) { get; set; } | Ottiene o imposta il nome o l'URI di una funzione di mappatura utilizzata per mappare fromPart a toPart. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Ottiene i prefissi dello spazio dei nomi utilizzati in[`XmpComplexType`](../xmpcomplextype) istanza. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [RenditionClass](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionclass) { get; set; } | Ottiene o imposta il valore della proprietà xmpMM:RenditionClass dalla risorsa di riferimento. |
| [RenditionParams](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionparams) { get; set; } | Ottiene o imposta il valore della proprietà xmpMM:RenditionParams dalla risorsa di riferimento. |
| [VersionID](../../groupdocs.metadata.standards.xmp/xmpresourceref/versionid) { get; set; } | Ottiene o imposta il valore della proprietà xmpMM:RenditionParams dalla risorsa di riferimento. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | Ottiene l'URI dello spazio dei nomi associato al prefisso specificato. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | Restituisce il valore contenuto nella stringa in formato XMP. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) E[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | Restituisce aString che rappresenta questa istanza. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Guarda anche

* class [XmpComplexType](../xmpcomplextype)
* spazio dei nomi [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
