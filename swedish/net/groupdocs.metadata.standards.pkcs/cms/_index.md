---
title: Cms
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar en digital skylt skapad med Cryptographic Message Syntax CMS  IETFs standard för kryptografiskt skyddade meddelanden. CMS är baserat på syntaxen för PKCS 7 specificerad i RFC 5652. Sehttps//tools.ietf.org/html/rfc5652https//tools.ietf.org/html/rfc5652 för mer information.
type: docs
weight: 2960
url: /sv/net/groupdocs.metadata.standards.pkcs/cms/
---
## Cms class

Representerar en digital skylt skapad med Cryptographic Message Syntax (CMS) - IETF:s standard för kryptografiskt skyddade meddelanden. CMS är baserat på syntaxen för PKCS #7, specificerad i RFC 5652. Se[https://tools.ietf.org/html/rfc5652](https://tools.ietf.org/html/rfc5652) för mer information.

```csharp
public class Cms : DigitalSignature
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CertificateRawData](../../groupdocs.metadata.standards.signing/digitalsignature/certificaterawdata) { get; } | Hämtar certifikatets rådata. |
| [Certificates](../../groupdocs.metadata.standards.pkcs/cms/certificates) { get; } | Får samlingen av certifikat. |
| [CertificateSubject](../../groupdocs.metadata.standards.signing/digitalsignature/certificatesubject) { get; } | Får ämnets särskiljande namn från ett certifikat. |
| [Comments](../../groupdocs.metadata.standards.signing/digitalsignature/comments) { get; } | Får kommentaren för signeringssyfte. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [DigestAlgorithms](../../groupdocs.metadata.standards.pkcs/cms/digestalgorithms) { get; } | Hämtar arrayen av algoritmidentifierare för meddelandesammandrag. Det kan finnas hur många element som helst i samlingen, inklusive noll. |
| [EncapsulatedContent](../../groupdocs.metadata.standards.pkcs/cms/encapsulatedcontent) { get; } | Hämtar det signerade innehållet, bestående av en innehållstypsidentifierare och själva innehållet. |
| virtual [IsValid](../../groupdocs.metadata.standards.signing/digitalsignature/isvalid) { get; } | Får ett värde som indikerar om signaturen är giltig. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [Signers](../../groupdocs.metadata.standards.pkcs/cms/signers) { get; } | Får samlingen av informationspaket för per-signer. |
| override [SignTime](../../groupdocs.metadata.standards.pkcs/cms/signtime) { get; } | Får tidpunkten då undertecknaren (påstås) utförde signeringsprocessen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Lägger till kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar även alla kapslade paket. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestämmer om paketet innehåller en metadataegenskap med det angivna namnet. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Hittar metadataegenskaperna som uppfyller det angivna predikatet. Sökningen är rekursiv så den påverkar också alla kapslade paket. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Tar bort metadataegenskaper som uppfyller det angivna predikatet. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Tar bort skrivbara metadataegenskaper från paketet. Operationen är rekursiv så den påverkar alla kapslade paket också. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Se även

* class [DigitalSignature](../../groupdocs.metadata.standards.signing/digitalsignature)
* namnutrymme [GroupDocs.Metadata.Standards.Pkcs](../../groupdocs.metadata.standards.pkcs)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
