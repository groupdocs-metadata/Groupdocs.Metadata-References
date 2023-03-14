---
title: EmlPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta i metadati del messaggio EML.
type: docs
weight: 1380
url: /it/net/groupdocs.metadata.formats.email/emlpackage/
---
## EmlPackage class

Rappresenta i metadati del messaggio EML.

```csharp
public class EmlPackage : EmailPackage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AttachedFileNames](../../groupdocs.metadata.formats.email/emailpackage/attachedfilenames) { get; } | Ottiene un array dei nomi dei file allegati. |
| [BlindCarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/blindcarboncopyrecipients) { get; set; } | Ottiene o imposta l'array di destinatari BCC (copia nascosta) del messaggio di posta elettronica. |
| [CarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/carboncopyrecipients) { get; set; } | Ottiene o imposta l'array di destinatari CC (copia carbone) del messaggio di posta elettronica. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [Headers](../../groupdocs.metadata.formats.email/emailpackage/headers) { get; } | Ottiene un pacchetto di metadati contenente le intestazioni di posta elettronica. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [Recipients](../../groupdocs.metadata.formats.email/emailpackage/recipients) { get; set; } | Ottiene o imposta l'array dei destinatari dell'e-mail. |
| [Sender](../../groupdocs.metadata.formats.email/emailpackage/sender) { get; } | Ottiene l'indirizzo email del mittente. |
| [Subject](../../groupdocs.metadata.formats.email/emailpackage/subject) { get; set; } | Ottiene o imposta l'oggetto dell'email. |

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

* [Lavorare con le email salvate](https://docs.groupdocs.com/display/metadatanet/Working+with+saved+Emails)

### Guarda anche

* class [EmailPackage](../emailpackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Email](../../groupdocs.metadata.formats.email)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
