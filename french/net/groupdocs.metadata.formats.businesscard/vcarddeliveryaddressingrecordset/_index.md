---
title: VCardDeliveryAddressingRecordset
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente un ensemble denregistrements vCard dadressage de livraison. Ces types concernent les informations relatives à ladressage de livraison ou létiquette de lobjet vCard.
type: docs
weight: 700
url: /fr/net/groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/
---
## VCardDeliveryAddressingRecordset class

Représente un ensemble d'enregistrements vCard d'adressage de livraison. Ces types concernent les informations relatives à l'adressage de livraison ou l'étiquette de l'objet vCard.

```csharp
public class VCardDeliveryAddressingRecordset : VCardRecordset
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Addresses](../../groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/addresses) { get; } | Obtient les composants de l'adresse de livraison de l'objet. |
| [AddressRecords](../../groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/addressrecords) { get; } | Obtient les composants de l'adresse de livraison de l'objet. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [LabelRecords](../../groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/labelrecords) { get; } | Obtient un tableau contenant le texte formaté correspondant à l'adresse de livraison de l'objet. |
| [Labels](../../groupdocs.metadata.formats.businesscard/vcarddeliveryaddressingrecordset/labels) { get; } | Obtient un tableau contenant le texte formaté correspondant à l'adresse de livraison de l'objet. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |

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
