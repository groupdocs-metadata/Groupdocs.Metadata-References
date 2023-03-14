---
title: RiffInfoPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta il pacchetto di metadati contenente le proprietà estratte dal blocco RIFF INFO.
type: docs
weight: 2220
url: /it/net/groupdocs.metadata.formats.riff/riffinfopackage/
---
## RiffInfoPackage class

Rappresenta il pacchetto di metadati contenente le proprietà estratte dal blocco RIFF INFO.

```csharp
public sealed class RiffInfoPackage : CustomPackage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Artist](../../groupdocs.metadata.formats.riff/riffinfopackage/artist) { get; } | Ottiene l'artista dell'oggetto originale del file. |
| [Comment](../../groupdocs.metadata.formats.riff/riffinfopackage/comment) { get; } | Ottiene il commento sul file o sull'oggetto del file. |
| [Copyright](../../groupdocs.metadata.formats.riff/riffinfopackage/copyright) { get; } | Ottiene le informazioni sul copyright per il file. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [CreationDate](../../groupdocs.metadata.formats.riff/riffinfopackage/creationdate) { get; } | Ottiene la data di creazione dell'oggetto del file. |
| [Engineer](../../groupdocs.metadata.formats.riff/riffinfopackage/engineer) { get; } | Ottiene il nome dell'ingegnere che ha lavorato al file. |
| [Genre](../../groupdocs.metadata.formats.riff/riffinfopackage/genre) { get; } | Ottiene il genere dell'opera originale. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [Keywords](../../groupdocs.metadata.formats.riff/riffinfopackage/keywords) { get; } | Recupera le parole chiave che fanno riferimento al file o all'oggetto del file. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [Name](../../groupdocs.metadata.formats.riff/riffinfopackage/name) { get; } | Ottiene il titolo dell'oggetto del file. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [Software](../../groupdocs.metadata.formats.riff/riffinfopackage/software) { get; } | Ottiene il nome del pacchetto software utilizzato per creare il file. |
| [Source](../../groupdocs.metadata.formats.riff/riffinfopackage/source) { get; } | Ottiene il nome della persona o dell'organizzazione che ha fornito l'oggetto originale del file. |
| [Subject](../../groupdocs.metadata.formats.riff/riffinfopackage/subject) { get; } | Ottiene una descrizione del contenuto del file, ad esempio "Veduta aerea di Seattle". |
| [Technician](../../groupdocs.metadata.formats.riff/riffinfopackage/technician) { get; } | Recupera il tecnico che ha digitalizzato il file dell'oggetto. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) E[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Guarda anche

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Riff](../../groupdocs.metadata.formats.riff)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
