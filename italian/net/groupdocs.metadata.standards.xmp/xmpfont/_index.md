---
title: XmpFont
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Una struttura contenente le caratteristiche di un font utilizzato in un documento.
type: docs
weight: 3400
url: /it/net/groupdocs.metadata.standards.xmp/xmpfont/
---
## XmpFont class

Una struttura contenente le caratteristiche di un font utilizzato in un documento.

```csharp
public sealed class XmpFont : XmpComplexType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XmpFont](xmpfont#constructor)() | Inizializza una nuova istanza di[`XmpFont`](../xmpfont) classe. |
| [XmpFont](xmpfont#constructor_1)(string) | Inizializza una nuova istanza di[`XmpFont`](../xmpfont) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ChildFontFiles](../../groupdocs.metadata.standards.xmp/xmpfont/childfontfiles) { get; set; } | Ottiene o imposta l'elenco dei nomi file per i caratteri che compongono un carattere composito. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [FontFace](../../groupdocs.metadata.standards.xmp/xmpfont/fontface) { get; set; } | Ottiene o imposta il nome del carattere. |
| [FontFamily](../../groupdocs.metadata.standards.xmp/xmpfont/fontfamily) { get; set; } | Ottiene o imposta il nome della famiglia di caratteri. |
| [FontFileName](../../groupdocs.metadata.standards.xmp/xmpfont/fontfilename) { get; set; } | Ottiene o imposta il nome file del carattere (non un percorso completo). |
| [FontName](../../groupdocs.metadata.standards.xmp/xmpfont/fontname) { get; set; } | Ottiene o imposta il nome PostScript del font. |
| [FontType](../../groupdocs.metadata.standards.xmp/xmpfont/fonttype) { get; set; } | Ottiene o imposta il tipo di carattere. |
| [IsComposite](../../groupdocs.metadata.standards.xmp/xmpfont/iscomposite) { get; set; } | Ottiene o imposta un valore che indica se il carattere è composito. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Ottiene gli URI dello spazio dei nomi utilizzati in[`XmpComplexType`](../xmpcomplextype) istanza. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Ottiene i prefissi dello spazio dei nomi utilizzati in[`XmpComplexType`](../xmpcomplextype) istanza. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [Version](../../groupdocs.metadata.standards.xmp/xmpfont/version) { get; set; } | Ottiene o imposta la versione del font. |

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
