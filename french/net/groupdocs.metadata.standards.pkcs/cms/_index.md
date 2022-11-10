---
title: Cms
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente un signe numérique créé avec la syntaxe de message cryptographique CMS  la norme de lIETF pour les messages protégés par chiffrement. CMS est basé sur la syntaxe de PKCS 7 spécifiée dans la RFC 5652. Veuillez consulterhttps//tools.ietf.org/html/rfc5652https//tools.ietf.org/html/rfc5652 pour plus dinformations.
type: docs
weight: 2960
url: /fr/net/groupdocs.metadata.standards.pkcs/cms/
---
## Cms class

Représente un signe numérique créé avec la syntaxe de message cryptographique (CMS) - la norme de l'IETF pour les messages protégés par chiffrement. CMS est basé sur la syntaxe de PKCS #7, spécifiée dans la RFC 5652. Veuillez consulter[https://tools.ietf.org/html/rfc5652](https://tools.ietf.org/html/rfc5652) pour plus d'informations.

```csharp
public class Cms : DigitalSignature
```

## Propriétés

| Nom | La description |
| --- | --- |
| [CertificateRawData](../../groupdocs.metadata.standards.signing/digitalsignature/certificaterawdata) { get; } | Obtient les données brutes du certificat. |
| [Certificates](../../groupdocs.metadata.standards.pkcs/cms/certificates) { get; } | Obtient la collection de certificats. |
| [CertificateSubject](../../groupdocs.metadata.standards.signing/digitalsignature/certificatesubject) { get; } | Obtient le nom distinctif du sujet à partir d'un certificat. |
| [Comments](../../groupdocs.metadata.standards.signing/digitalsignature/comments) { get; } | Obtient le commentaire sur l'objet de la signature. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [DigestAlgorithms](../../groupdocs.metadata.standards.pkcs/cms/digestalgorithms) { get; } | Obtient le tableau d'identificateurs d'algorithme de résumé de message. Il peut y avoir n'importe quel nombre d'éléments dans la collection, y compris zéro. |
| [EncapsulatedContent](../../groupdocs.metadata.standards.pkcs/cms/encapsulatedcontent) { get; } | Obtient le contenu signé, composé d'un identifiant de type de contenu et du contenu lui-même. |
| virtual [IsValid](../../groupdocs.metadata.standards.signing/digitalsignature/isvalid) { get; } | Obtient une valeur indiquant si la signature est valide. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [Signers](../../groupdocs.metadata.standards.pkcs/cms/signers) { get; } | Obtient la collection de packages d'informations par signataire. |
| override [SignTime](../../groupdocs.metadata.standards.pkcs/cms/signtime) { get; } | Obtient l'heure à laquelle le signataire (prétendument) a effectué le processus de signature. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ajoute des propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Détermine si le package contient une propriété de métadonnées avec le nom spécifié. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trouve les propriétés de métadonnées satisfaisant le prédicat spécifié. La recherche est récursive, elle affecte donc également tous les packages imbriqués. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Supprime les propriétés de métadonnées satisfaisant le prédicat spécifié. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Supprime les propriétés de métadonnées inscriptibles du package. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Définit les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. Cette méthode est une combinaison de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) et[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si une propriété existante satisfait le prédicat, sa valeur est mise à jour. S'il manque une propriété connue dans le package qui satisfait le prédicat, elle est ajoutée au package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Voir également

* class [DigitalSignature](../../groupdocs.metadata.standards.signing/digitalsignature)
* espace de noms [GroupDocs.Metadata.Standards.Pkcs](../../groupdocs.metadata.standards.pkcs)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
