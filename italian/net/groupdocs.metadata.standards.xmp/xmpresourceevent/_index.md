---
title: XmpResourceEvent
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un evento di alto livello verificatosi durante lelaborazione di una risorsa.
type: docs
weight: 3540
url: /it/net/groupdocs.metadata.standards.xmp/xmpresourceevent/
---
## XmpResourceEvent class

Rappresenta un evento di alto livello verificatosi durante l'elaborazione di una risorsa.

```csharp
public sealed class XmpResourceEvent : XmpComplexType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XmpResourceEvent](xmpresourceevent)() | Inizializza una nuova istanza di[`XmpResourceEvent`](../xmpresourceevent) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Action](../../groupdocs.metadata.standards.xmp/xmpresourceevent/action) { get; set; } | Ottiene o imposta l'azione che si è verificata. |
| [Changed](../../groupdocs.metadata.standards.xmp/xmpresourceevent/changed) { get; set; } | Ottiene o imposta un elenco delimitato da punto e virgola delle parti della risorsa che sono state modificate dalla precedente cronologia eventi. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [InstanceID](../../groupdocs.metadata.standards.xmp/xmpresourceevent/instanceid) { get; set; } | Ottiene o imposta il valore della proprietà xmpMM:InstanceID per la risorsa modificata (output). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Ottiene gli URI dello spazio dei nomi utilizzati in[`XmpComplexType`](../xmpcomplextype) istanza. |
| [Parameters](../../groupdocs.metadata.standards.xmp/xmpresourceevent/parameters) { get; set; } | Ottiene o imposta la descrizione aggiuntiva dell'azione. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Ottiene i prefissi dello spazio dei nomi utilizzati in[`XmpComplexType`](../xmpcomplextype) istanza. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [SoftwareAgent](../../groupdocs.metadata.standards.xmp/xmpresourceevent/softwareagent) { get; set; } | Ottiene o imposta l'agente software che ha eseguito l'azione. |
| [When](../../groupdocs.metadata.standards.xmp/xmpresourceevent/when) { get; set; } | Ottiene o imposta il timestamp di quando si è verificata l'azione. |

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
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) e[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | Restituisce aString che rappresenta questa istanza. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Guarda anche

* class [XmpComplexType](../xmpcomplextype)
* spazio dei nomi [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
