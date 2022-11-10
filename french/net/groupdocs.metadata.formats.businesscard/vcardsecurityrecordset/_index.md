---
title: VCardSecurityRecordset
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente un ensemble denregistrements vCard de sécurité. Ces propriétés concernent la sécurité des voies de communication ou laccès à la vCard.
type: docs
weight: 800
url: /fr/net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/
---
## VCardSecurityRecordset class

Représente un ensemble d'enregistrements vCard de sécurité. Ces propriétés concernent la sécurité des voies de communication ou l'accès à la vCard.

```csharp
public class VCardSecurityRecordset : VCardRecordset
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AccessClassification](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/accessclassification) { get; } | Obtient la sensibilité des informations dans la vCard. |
| [BinaryPublicKeys](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/binarypublickeys) { get; } | Obtient les clés publiques ou les certificats d'authentification associés à l'objet. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [PublicKeyBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/publickeybinaryrecords) { get; } | Obtient les clés publiques ou les certificats d'authentification associés à l'objet. |
| [PublicKeyRecords](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/publickeyrecords) { get; } | Obtient les clés publiques ou les certificats d'authentification associés à l'objet. |
| [PublicKeyUriRecords](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/publickeyurirecords) { get; } | Obtient les clés publiques ou les certificats d'authentification associés à l'objet. |
| [UriPublicKeys](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/uripublickeys) { get; } | Obtient les clés publiques ou les certificats d'authentification associés à l'objet. |

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

### Remarques

**Apprendre encore plus**

* [Travailler avec les métadonnées vCard](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Voir également

* class [VCardRecordset](../vcardrecordset)
* espace de noms [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
