---
title: Cms
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt een digitaal teken gemaakt met Cryptographic Message Syntax CMS  IETFs standaard voor cryptografisch beveiligde berichten. CMS is gebaseerd op de syntaxis van PKCS 7 gespecificeerd in RFC 5652. Ziehttps//tools.ietf.org/html/rfc5652https//tools.ietf.org/html/rfc5652 voor meer informatie.
type: docs
weight: 2960
url: /nl/net/groupdocs.metadata.standards.pkcs/cms/
---
## Cms class

Vertegenwoordigt een digitaal teken gemaakt met Cryptographic Message Syntax (CMS) - IETF's standaard voor cryptografisch beveiligde berichten. CMS is gebaseerd op de syntaxis van PKCS #7, gespecificeerd in RFC 5652. Zie[https://tools.ietf.org/html/rfc5652](https://tools.ietf.org/html/rfc5652) voor meer informatie.

```csharp
public class Cms : DigitalSignature
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CertificateRawData](../../groupdocs.metadata.standards.signing/digitalsignature/certificaterawdata) { get; } | Haalt de ruwe gegevens van het certificaat op. |
| [Certificates](../../groupdocs.metadata.standards.pkcs/cms/certificates) { get; } | Haalt de verzameling certificaten op. |
| [CertificateSubject](../../groupdocs.metadata.standards.signing/digitalsignature/certificatesubject) { get; } | Haalt de DN-naam van het onderwerp op uit een certificaat. |
| [Comments](../../groupdocs.metadata.standards.signing/digitalsignature/comments) { get; } | Krijgt de opmerking over het doel van de ondertekening. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [DigestAlgorithms](../../groupdocs.metadata.standards.pkcs/cms/digestalgorithms) { get; } | Haalt de array van algoritme-ID's voor berichtsamenvatting op. Er kan een willekeurig aantal elementen in de collectie zijn, inclusief nul. |
| [EncapsulatedContent](../../groupdocs.metadata.standards.pkcs/cms/encapsulatedcontent) { get; } | Haalt de ondertekende inhoud op, bestaande uit een inhoudstype-ID en de inhoud zelf. |
| virtual [IsValid](../../groupdocs.metadata.standards.signing/digitalsignature/isvalid) { get; } | Krijgt een waarde die aangeeft of de handtekening geldig is. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [Signers](../../groupdocs.metadata.standards.pkcs/cms/signers) { get; } | Haalt de verzameling informatiepakketten per ondertekenaar op. |
| override [SignTime](../../groupdocs.metadata.standards.pkcs/cms/signtime) { get; } | Krijgt het tijdstip waarop de ondertekenaar (naar verluidt) het ondertekeningsproces heeft uitgevoerd. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Voegt bekende metadata-eigenschappen toe die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bepaalt of het pakket een metadata-eigenschap bevat met de opgegeven naam. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Zoekt de metadata-eigenschappen die voldoen aan het opgegeven predikaat. De zoekopdracht is recursief, dus het heeft ook invloed op alle geneste pakketten. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Retourneert een enumerator die de verzameling herhaalt. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Verwijdert beschrijfbare metadata-eigenschappen uit het pakket. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Zie ook

* class [DigitalSignature](../../groupdocs.metadata.standards.signing/digitalsignature)
* naamruimte [GroupDocs.Metadata.Standards.Pkcs](../../groupdocs.metadata.standards.pkcs)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
