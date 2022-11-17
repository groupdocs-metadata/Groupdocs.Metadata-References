---
title: XmpPdfPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Specifica le proprietà utilizzate con i documenti Adobe PDF.
type: docs
weight: 3190
url: /it/net/groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/
---
## XmpPdfPackage class

Specifica le proprietà utilizzate con i documenti Adobe PDF.

```csharp
public sealed class XmpPdfPackage : XmpPackage
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XmpPdfPackage](xmppdfpackage)() | Inizializza una nuova istanza di[`XmpPdfPackage`](../xmppdfpackage) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [IsTrapped](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/istrapped) { get; set; } | Ottiene o imposta un valore che indica se il documento è stato intercettato. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [Keywords](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/keywords) { get; set; } | Recupera o imposta le parole chiave. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Ottiene l'URI dello spazio dei nomi. |
| [PdfVersion](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/pdfversion) { get; set; } | Ottiene o imposta la versione del file PDF. Ad esempio, 1.0, 1.3 e così via. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Ottiene il prefisso xmlns. |
| [Producer](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/producer) { get; set; } | Ottiene o imposta il nome dello strumento che ha creato il documento PDF. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Ottiene lo spazio dei nomi XML. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Rimuove tutte le proprietà XMP. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Converte il valore XMP nella rappresentazione XML. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Rimuove la proprietà con il nome specificato. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Imposta la proprietà booleana. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | InsiemiDateTime proprietà. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Imposta la proprietà double. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Imposta la proprietà numero intero. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/set#set_7)(string, string) | Imposta la proprietà della stringa. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Imposta il valore ereditato da[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Imposta il valore ereditato da[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Imposta il valore ereditato da[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) e[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Guarda anche

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* spazio dei nomi [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
