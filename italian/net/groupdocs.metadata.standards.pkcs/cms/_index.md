---
title: Cms
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta un segno digitale creato con la sintassi dei messaggi crittografici CMS lo standard IETF per i messaggi protetti crittograficamente. CMS si basa sulla sintassi di PKCS 7 specificata in RFC 5652. Consultarehttps//tools.ietf.org/html/rfc5652https//tools.ietf.org/html/rfc5652 per ulteriori informazioni.
type: docs
weight: 2960
url: /it/net/groupdocs.metadata.standards.pkcs/cms/
---
## Cms class

Rappresenta un segno digitale creato con la sintassi dei messaggi crittografici (CMS), lo standard IETF per i messaggi protetti crittograficamente. CMS si basa sulla sintassi di PKCS #7, specificata in RFC 5652. Consultare[https://tools.ietf.org/html/rfc5652](https://tools.ietf.org/html/rfc5652) per ulteriori informazioni.

```csharp
public class Cms : DigitalSignature
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CertificateRawData](../../groupdocs.metadata.standards.signing/digitalsignature/certificaterawdata) { get; } | Ottiene i dati grezzi del certificato. |
| [Certificates](../../groupdocs.metadata.standards.pkcs/cms/certificates) { get; } | Ottiene la raccolta di certificati. |
| [CertificateSubject](../../groupdocs.metadata.standards.signing/digitalsignature/certificatesubject) { get; } | Ottiene il nome distinto del soggetto da un certificato. |
| [Comments](../../groupdocs.metadata.standards.signing/digitalsignature/comments) { get; } | Ottiene il commento sullo scopo della firma. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [DigestAlgorithms](../../groupdocs.metadata.standards.pkcs/cms/digestalgorithms) { get; } | Ottiene l'array di identificatori dell'algoritmo message-digest. Potrebbe esserci un numero qualsiasi di elementi nella raccolta, incluso zero. |
| [EncapsulatedContent](../../groupdocs.metadata.standards.pkcs/cms/encapsulatedcontent) { get; } | Ottiene il contenuto firmato, costituito da un identificatore del tipo di contenuto e dal contenuto stesso. |
| virtual [IsValid](../../groupdocs.metadata.standards.signing/digitalsignature/isvalid) { get; } | Ottiene un valore che indica se la firma è valida. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [Signers](../../groupdocs.metadata.standards.pkcs/cms/signers) { get; } | Ottiene la raccolta di pacchetti di informazioni per firmatario. |
| override [SignTime](../../groupdocs.metadata.standards.pkcs/cms/signtime) { get; } | Ottiene l'ora in cui il firmatario (presumibilmente) ha eseguito il processo di firma. |

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

* class [DigitalSignature](../../groupdocs.metadata.standards.signing/digitalsignature)
* spazio dei nomi [GroupDocs.Metadata.Standards.Pkcs](../../groupdocs.metadata.standards.pkcs)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
