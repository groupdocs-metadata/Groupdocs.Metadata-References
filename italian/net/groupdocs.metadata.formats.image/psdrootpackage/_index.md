---
title: PsdRootPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta il pacchetto radice che consente di lavorare con i metadati in un documento Photoshop.
type: docs
weight: 1930
url: /it/net/groupdocs.metadata.formats.image/psdrootpackage/
---
## PsdRootPackage class

Rappresenta il pacchetto radice che consente di lavorare con i metadati in un documento Photoshop.

```csharp
public class PsdRootPackage : ImageRootPackage, IExif, IIptc, IXmp
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [ExifPackage](../../groupdocs.metadata.formats.image/psdrootpackage/exifpackage) { get; set; } | Ottiene o imposta il pacchetto di metadati EXIF. |
| [FileType](../../groupdocs.metadata.formats.image/imagerootpackage/filetype) { get; } | Ottiene il pacchetto di metadati del tipo di file. (2 properties) |
| [ImageResourcePackage](../../groupdocs.metadata.formats.image/psdrootpackage/imageresourcepackage) { get; } | Ottiene il pacchetto di metadati di Photoshop Image Resource. I blocchi di risorse immagine sono l'unità di base del formato di file nativo di Photoshop. |
| [IptcPackage](../../groupdocs.metadata.formats.image/psdrootpackage/iptcpackage) { get; set; } | Ottiene o imposta il pacchetto di metadati IPTC. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [PsdPackage](../../groupdocs.metadata.formats.image/psdrootpackage/psdpackage) { get; } | Ottiene il pacchetto di metadati contenente informazioni sul file PSD. |
| [XmpPackage](../../groupdocs.metadata.formats.image/psdrootpackage/xmppackage) { get; set; } | Ottiene o imposta il pacchetto di metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) E[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

**Saperne di più**

* [Lavorare con i metadati nelle immagini PSD](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PSD+images)
* [Lavorare con i metadati EXIF](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)
* [Lavorare con i metadati XMP](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)
* [Utilizzo dei metadati IPTC IIM](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Guarda anche

* class [ImageRootPackage](../imagerootpackage)
* interface [IExif](../../groupdocs.metadata.standards.exif/iexif)
* interface [IIptc](../../groupdocs.metadata.standards.iptc/iiptc)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* spazio dei nomi [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
