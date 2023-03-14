---
title: DicomPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta i metadati DICOM nativi.
type: docs
weight: 1670
url: /it/net/groupdocs.metadata.formats.image/dicompackage/
---
## DicomPackage class

Rappresenta i metadati DICOM nativi.

```csharp
public sealed class DicomPackage : CustomPackage
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DicomPackage](dicompackage)() | Inizializza una nuova istanza di[`Metadata`](../../groupdocs.metadata/metadata) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BitsAllocated](../../groupdocs.metadata.formats.image/dicompackage/bitsallocated) { get; } | Ottiene il valore allocato dei bit. |
| [Blues](../../groupdocs.metadata.formats.image/dicompackage/blues) { get; } | Ottiene i colori dell'array del blu. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [DicomInfo](../../groupdocs.metadata.formats.image/dicompackage/dicominfo) { get; } | Ottiene le informazioni di intestazione del file DICOM. |
| [Greens](../../groupdocs.metadata.formats.image/dicompackage/greens) { get; } | Ottiene i colori dell'array del verde. |
| [HeaderBytes](../../groupdocs.metadata.formats.image/dicompackage/headerbytes) { get; } | Ottiene le informazioni di intestazione per byte. |
| [HeaderOffset](../../groupdocs.metadata.formats.image/dicompackage/headeroffset) { get; } | Ottiene l'offset dell'intestazione. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [NumberOfFrames](../../groupdocs.metadata.formats.image/dicompackage/numberofframes) { get; } | Ottiene il numero di fotogrammi. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [Reds](../../groupdocs.metadata.formats.image/dicompackage/reds) { get; } | Ottiene i colori dell'array del rosso. |

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

* [Lavorare con i metadati DICOM](https://docs.groupdocs.com/display/metadatanet/Working+with+DICOM+metadata)

### Guarda anche

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
