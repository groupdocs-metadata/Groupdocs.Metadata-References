---
title: XmpMeta
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta xmpmeta. Facoltativo. Lo scopo di questo elemento è identificare i metadati XMP allinterno del testo XML generale che potrebbe contenere altri usi non XMP di RDF.
type: docs
weight: 3460
url: /it/net/groupdocs.metadata.standards.xmp/xmpmeta/
---
## XmpMeta class

Rappresenta xmpmeta. Facoltativo. Lo scopo di questo elemento è identificare i metadati XMP all'interno del testo XML generale che potrebbe contenere altri usi non XMP di RDF.

```csharp
public sealed class XmpMeta : XmpElementBase, IXmpType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XmpMeta](xmpmeta)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AdobeXmpToolkit](../../groupdocs.metadata.standards.xmp/xmpmeta/adobexmptoolkit) { get; } | Ottiene la versione del toolkit Adobe XMP. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [ClearAttributes](../../groupdocs.metadata.standards.xmp/xmpelementbase/clearattributes)() | Rimuove tutti gli attributi. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| [ContainsAttribute](../../groupdocs.metadata.standards.xmp/xmpelementbase/containsattribute)(string) | Determina se l'elemento contiene un attributo specifico. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [GetAttribute](../../groupdocs.metadata.standards.xmp/xmpelementbase/getattribute)(string) | Ottiene l'attributo. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpmeta/getxmprepresentation)() | Converte il valore XMP nella rappresentazione xml. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| override [SetAttribute](../../groupdocs.metadata.standards.xmp/xmpmeta/setattribute)(string, string) | Aggiunge un attributo. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) E[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Guarda anche

* class [XmpElementBase](../xmpelementbase)
* interface [IXmpType](../ixmptype)
* spazio dei nomi [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
