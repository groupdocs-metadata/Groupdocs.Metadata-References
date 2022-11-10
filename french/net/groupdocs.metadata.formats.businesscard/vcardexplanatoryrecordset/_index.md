---
title: VCardExplanatoryRecordset
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente un ensemble denregistrements vCard explicatifs. Ces propriétés concernent des explications supplémentaires telles que celles liées aux notes dinformation ou aux révisions spécifiques à la vCard.
type: docs
weight: 710
url: /fr/net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/
---
## VCardExplanatoryRecordset class

Représente un ensemble d'enregistrements vCard explicatifs. Ces propriétés concernent des explications supplémentaires, telles que celles liées aux notes d'information ou aux révisions spécifiques à la vCard.

```csharp
public class VCardExplanatoryRecordset : VCardRecordset
```

## Propriétés

| Nom | La description |
| --- | --- |
| [BinarySounds](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/binarysounds) { get; } | Obtient les informations de contenu audio numérique qui annotent certains aspects de la vCard. |
| [Categories](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/categories) { get; } | Obtient les informations de catégorie d'application sur la vCard, également appelées "tags". |
| [CategoryRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/categoryrecords) { get; } | Obtient les informations de catégorie d'application sur la vCard, également appelées "tags". |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [NoteRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/noterecords) { get; } | Obtient les informations supplémentaires ou les commentaires associés à la vCard. |
| [Notes](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/notes) { get; } | Obtient les informations supplémentaires ou les commentaires associés à la vCard. |
| [PidIdentifierRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/pididentifierrecords) { get; } | Obtient la signification globale de l'identifiant de source PID local. |
| [PidIdentifiers](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/pididentifiers) { get; } | Obtient la signification globale de l'identifiant de source PID local. |
| [ProductIdentifier](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/productidentifier) { get; } | Obtient l'identifiant du produit qui a créé l'objet vCard. |
| [ProductIdentifierRecord](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/productidentifierrecord) { get; } | Obtient l'identifiant du produit qui a créé l'objet vCard. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [Revision](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/revision) { get; } | Obtient les informations de révision sur la vCard actuelle. |
| [SortString](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/sortstring) { get; } | Obtient le nom de famille ou le texte du prénom à utiliser pour le tri spécifique à la langue nationale du[`FormattedNames`](../vcardidentificationrecordset/formattednames) et[`Name`](../vcardidentificationrecordset/name) types. |
| [SoundBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/soundbinaryrecords) { get; } | Obtient les informations de contenu audio numérique qui annotent certains aspects de la vCard. |
| [SoundRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/soundrecords) { get; } | Obtient les informations de contenu audio numérique qui annotent certains aspects de la vCard. |
| [SoundUriRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/soundurirecords) { get; } | Obtient les informations de contenu audio numérique qui annotent certains aspects de la vCard. |
| [Uid](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/uid) { get; } | Obtient la valeur qui représente un identifiant global unique correspondant à la personne ou à la ressource associée à la vCard. |
| [UidRecord](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/uidrecord) { get; } | Obtient la valeur qui représente un identifiant global unique correspondant à la personne ou à la ressource associée à la vCard. |
| [UriSounds](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/urisounds) { get; } | Obtient les informations de contenu audio numérique qui annotent certains aspects de la vCard. |
| [UrlRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/urlrecords) { get; } | Obtient un tableau d'URL pointant vers des sites Web qui représentent la personne d'une manière ou d'une autre. |
| [Urls](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/urls) { get; } | Obtient un tableau d'URL pointant vers des sites Web qui représentent la personne d'une manière ou d'une autre. |
| [Version](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/version) { get; } | Obtient la version de la spécification vCard. |

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
