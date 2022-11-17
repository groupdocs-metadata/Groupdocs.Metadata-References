---
title: DublinCorePackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un pacchetto di metadati Dublin Core.
type: docs
weight: 2730
url: /it/net/groupdocs.metadata.standards.dublincore/dublincorepackage/
---
## DublinCorePackage class

Rappresenta un pacchetto di metadati Dublin Core.

```csharp
public sealed class DublinCorePackage : CustomPackage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Contributor](../../groupdocs.metadata.standards.dublincore/dublincorepackage/contributor) { get; } | Ottiene l'elemento Dublin Core del contributore. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [Coverage](../../groupdocs.metadata.standards.dublincore/dublincorepackage/coverage) { get; } | Ottiene l'elemento Dublin Core di copertura. |
| [Creator](../../groupdocs.metadata.standards.dublincore/dublincorepackage/creator) { get; } | Ottiene l'elemento creatore Dublin Core. |
| [Date](../../groupdocs.metadata.standards.dublincore/dublincorepackage/date) { get; } | Ottiene la data dell'elemento Dublin Core. |
| [Description](../../groupdocs.metadata.standards.dublincore/dublincorepackage/description) { get; } | Ottiene la descrizione dell'elemento Dublin Core. |
| [Format](../../groupdocs.metadata.standards.dublincore/dublincorepackage/format) { get; } | Ottiene il formato dell'elemento Dublin Core. |
| [Identifier](../../groupdocs.metadata.standards.dublincore/dublincorepackage/identifier) { get; } | Ottiene l'identificatore dell'elemento Dublin Core. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [Language](../../groupdocs.metadata.standards.dublincore/dublincorepackage/language) { get; } | Ottiene l'elemento Dublin Core della lingua. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [Publisher](../../groupdocs.metadata.standards.dublincore/dublincorepackage/publisher) { get; } | Ottiene l'elemento Dublin Core dell'editore. |
| [Relation](../../groupdocs.metadata.standards.dublincore/dublincorepackage/relation) { get; } | Ottiene l'elemento Dublin Core della relazione. |
| [Rights](../../groupdocs.metadata.standards.dublincore/dublincorepackage/rights) { get; } | Ottiene i diritti dell'elemento Dublin Core. |
| [Source](../../groupdocs.metadata.standards.dublincore/dublincorepackage/source) { get; } | Ottiene l'elemento Dublin Core di origine. |
| [Subject](../../groupdocs.metadata.standards.dublincore/dublincorepackage/subject) { get; } | Ottiene l'elemento Dublin Core soggetto. |
| [Title](../../groupdocs.metadata.standards.dublincore/dublincorepackage/title) { get; } | Ottiene il titolo Dublin Core element. |
| [Type](../../groupdocs.metadata.standards.dublincore/dublincorepackage/type) { get; } | Ottiene l'elemento di tipo Dublin Core. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) e[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Guarda anche

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* spazio dei nomi [GroupDocs.Metadata.Standards.DublinCore](../../groupdocs.metadata.standards.dublincore)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
