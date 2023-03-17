---
title: CmsSigner
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt CMS per ondertekenaarinformatie.
type: docs
weight: 3010
url: /nl/net/groupdocs.metadata.standards.pkcs/cmssigner/
---
## CmsSigner class

Vertegenwoordigt CMS per ondertekenaar-informatie.

```csharp
public class CmsSigner : CustomPackage
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [DigestAlgorithm](../../groupdocs.metadata.standards.pkcs/cmssigner/digestalgorithm) { get; } | Haalt het berichtsamenvattingsalgoritme en alle bijbehorende parameters op die door de ondertekenaar worden gebruikt. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [SignatureAlgorithm](../../groupdocs.metadata.standards.pkcs/cmssigner/signaturealgorithm) { get; } | Haalt het handtekeningalgoritme en alle bijbehorende parameters op die door de ondertekenaar zijn gebruikt om de digitale handtekening te genereren. |
| [SignatureValue](../../groupdocs.metadata.standards.pkcs/cmssigner/signaturevalue) { get; } | Haalt het resultaat op van het genereren van digitale handtekeningen, met behulp van de berichtsamenvatting en de persoonlijke sleutel van de ondertekenaar. |
| [SignedAttributes](../../groupdocs.metadata.standards.pkcs/cmssigner/signedattributes) { get; } | Haalt de verzameling attributen op die zijn ondertekend. |
| [SignerIdentifier](../../groupdocs.metadata.standards.pkcs/cmssigner/signeridentifier) { get; } | Haalt het certificaat van de ondertekenaar op (en daarmee de openbare sleutel van de ondertekenaar) onbewerkte gegevens. |
| [SigningTime](../../groupdocs.metadata.standards.pkcs/cmssigner/signingtime) { get; } | Krijgt het tijdstip waarop de ondertekenaar (naar verluidt) het ondertekeningsproces heeft uitgevoerd. |
| [UnsignedAttributes](../../groupdocs.metadata.standards.pkcs/cmssigner/unsignedattributes) { get; } | Haalt de verzameling attributen op die niet zijn ondertekend. |

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

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* naamruimte [GroupDocs.Metadata.Standards.Pkcs](../../groupdocs.metadata.standards.pkcs)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
