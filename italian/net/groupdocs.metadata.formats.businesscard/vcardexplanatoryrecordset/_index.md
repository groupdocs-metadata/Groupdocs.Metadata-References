---
title: VCardExplanatoryRecordset
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un insieme di record vCard esplicativi. Queste proprietà riguardano spiegazioni aggiuntive come quelle relative a note informative o revisioni specifiche della vCard.
type: docs
weight: 710
url: /it/net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/
---
## VCardExplanatoryRecordset class

Rappresenta un insieme di record vCard esplicativi. Queste proprietà riguardano spiegazioni aggiuntive, come quelle relative a note informative o revisioni specifiche della vCard.

```csharp
public class VCardExplanatoryRecordset : VCardRecordset
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BinarySounds](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/binarysounds) { get; } | Ottiene le informazioni sul contenuto audio digitale che annotano alcuni aspetti della vCard. |
| [Categories](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/categories) { get; } | Ottiene le informazioni sulla categoria dell'applicazione relative alla vCard, note anche come "tag". |
| [CategoryRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/categoryrecords) { get; } | Ottiene le informazioni sulla categoria dell'applicazione relative alla vCard, note anche come "tag". |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [NoteRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/noterecords) { get; } | Ottiene le informazioni o i commenti supplementari associati alla vCard. |
| [Notes](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/notes) { get; } | Ottiene le informazioni o i commenti supplementari associati alla vCard. |
| [PidIdentifierRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/pididentifierrecords) { get; } | Ottiene il significato globale dell'identificatore della sorgente PID locale. |
| [PidIdentifiers](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/pididentifiers) { get; } | Ottiene il significato globale dell'identificatore della sorgente PID locale. |
| [ProductIdentifier](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/productidentifier) { get; } | Ottiene l'identificatore del prodotto che ha creato l'oggetto vCard. |
| [ProductIdentifierRecord](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/productidentifierrecord) { get; } | Ottiene l'identificatore del prodotto che ha creato l'oggetto vCard. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [Revision](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/revision) { get; } | Ottiene le informazioni sulla revisione della vCard corrente. |
| [SortString](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/sortstring) { get; } | Ottiene il testo del cognome o del nome da utilizzare per l'ordinamento specifico della lingua nazionale del[`FormattedNames`](../vcardidentificationrecordset/formattednames) E[`Name`](../vcardidentificationrecordset/name) tipi. |
| [SoundBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/soundbinaryrecords) { get; } | Ottiene le informazioni sul contenuto audio digitale che annotano alcuni aspetti della vCard. |
| [SoundRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/soundrecords) { get; } | Ottiene le informazioni sul contenuto audio digitale che annotano alcuni aspetti della vCard. |
| [SoundUriRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/soundurirecords) { get; } | Ottiene le informazioni sul contenuto audio digitale che annotano alcuni aspetti della vCard. |
| [Uid](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/uid) { get; } | Ottiene il valore che rappresenta un identificatore univoco globale corrispondente all'individuo o alla risorsa associata alla vCard. |
| [UidRecord](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/uidrecord) { get; } | Ottiene il valore che rappresenta un identificatore univoco globale corrispondente all'individuo o alla risorsa associata alla vCard. |
| [UriSounds](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/urisounds) { get; } | Ottiene le informazioni sul contenuto audio digitale che annotano alcuni aspetti della vCard. |
| [UrlRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/urlrecords) { get; } | Recupera un array di URL che puntano a siti Web che rappresentano in qualche modo la persona. |
| [Urls](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/urls) { get; } | Recupera un array di URL che puntano a siti Web che rappresentano in qualche modo la persona. |
| [Version](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/version) { get; } | Ottiene la versione della specifica vCard. |

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

### Osservazioni

**Saperne di più**

* [Utilizzo dei metadati vCard](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Guarda anche

* class [VCardRecordset](../vcardrecordset)
* spazio dei nomi [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
