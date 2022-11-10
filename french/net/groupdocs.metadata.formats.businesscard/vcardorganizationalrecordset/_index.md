---
title: VCardOrganizationalRecordset
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente un ensemble denregistrements vCard organisationnels. Ces propriétés concernent les informations associées aux caractéristiques de lorganisation ou des unités organisationnelles de lobjet représenté par la vCard.
type: docs
weight: 750
url: /fr/net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/
---
## VCardOrganizationalRecordset class

Représente un ensemble d'enregistrements vCard organisationnels. Ces propriétés concernent les informations associées aux caractéristiques de l'organisation ou des unités organisationnelles de l'objet représenté par la vCard.

```csharp
public class VCardOrganizationalRecordset : VCardRecordset
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AgentObjectRecord](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agentobjectrecord) { get; } | Obtient les informations sur une autre personne qui agira au nom de l'objet vCard. |
| [AgentRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agentrecords) { get; } | Obtient les informations sur une autre personne qui agira au nom de l'objet vCard. |
| [AgentUriRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agenturirecords) { get; } | Obtient les informations sur une autre personne qui agira au nom de l'objet vCard. |
| [BinaryLogos](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/binarylogos) { get; } | Obtient les images graphiques du logo associé à l'objet. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [LogoBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logobinaryrecords) { get; } | Obtient les images graphiques du logo associé à l'objet. |
| [LogoRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logorecords) { get; } | Obtient les images graphiques du logo associé à l'objet. |
| [LogoUriRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logourirecords) { get; } | Obtient les URI des images graphiques du logo associé à l'objet. |
| [MemberRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/memberrecords) { get; } | Obtient les membres du groupe représenté par cette vCard. |
| [Members](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/members) { get; } | Obtient les membres du groupe représenté par cette vCard. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [ObjectAgent](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/objectagent) { get; } | Obtient les informations sur une autre personne qui agira au nom de l'objet vCard. |
| [OrganizationNameRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/organizationnamerecords) { get; } | Obtient les noms organisationnels et les unités associées à l'objet. |
| [OrganizationNames](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/organizationnames) { get; } | Obtient les noms organisationnels et les unités associées à l'objet. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [RelationshipRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/relationshiprecords) { get; } | Obtient les relations entre une autre entité et l'entité représentée par cette vCard. |
| [Relationships](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/relationships) { get; } | Obtient les relations entre une autre entité et l'entité représentée par cette vCard. |
| [RoleRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/rolerecords) { get; } | Obtient les fonctions ou les parties jouées dans une situation particulière par l'objet. |
| [Roles](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/roles) { get; } | Obtient les fonctions ou les parties jouées dans une situation particulière par l'objet. |
| [TitleRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/titlerecords) { get; } | Obtient les positions ou les emplois de l'objet. |
| [Titles](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/titles) { get; } | Obtient les positions ou les emplois de l'objet. |
| [UriAgents](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/uriagents) { get; } | Obtient les informations sur une autre personne qui agira au nom de l'objet vCard. |
| [UriLogos](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/urilogos) { get; } | Obtient les URI des images graphiques du logo associé à l'objet. |

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
