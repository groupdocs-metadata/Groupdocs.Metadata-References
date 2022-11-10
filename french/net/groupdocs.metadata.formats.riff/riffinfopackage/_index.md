---
title: RiffInfoPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente le package de métadonnées contenant les propriétés extraites du bloc RIFF INFO.
type: docs
weight: 2220
url: /fr/net/groupdocs.metadata.formats.riff/riffinfopackage/
---
## RiffInfoPackage class

Représente le package de métadonnées contenant les propriétés extraites du bloc RIFF INFO.

```csharp
public sealed class RiffInfoPackage : CustomPackage
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Artist](../../groupdocs.metadata.formats.riff/riffinfopackage/artist) { get; } | Obtient l'artiste du sujet original du fichier. |
| [Comment](../../groupdocs.metadata.formats.riff/riffinfopackage/comment) { get; } | Obtient le commentaire sur le fichier ou le sujet du fichier. |
| [Copyright](../../groupdocs.metadata.formats.riff/riffinfopackage/copyright) { get; } | Obtient les informations de copyright pour le fichier. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [CreationDate](../../groupdocs.metadata.formats.riff/riffinfopackage/creationdate) { get; } | Obtient la date à laquelle le sujet du fichier a été créé. |
| [Engineer](../../groupdocs.metadata.formats.riff/riffinfopackage/engineer) { get; } | Obtient le nom de l'ingénieur qui a travaillé sur le fichier. |
| [Genre](../../groupdocs.metadata.formats.riff/riffinfopackage/genre) { get; } | Obtient le genre de l'œuvre originale. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [Keywords](../../groupdocs.metadata.formats.riff/riffinfopackage/keywords) { get; } | Obtient les mots-clés qui font référence au fichier ou au sujet du fichier. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [Name](../../groupdocs.metadata.formats.riff/riffinfopackage/name) { get; } | Obtient le titre du sujet du fichier. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [Software](../../groupdocs.metadata.formats.riff/riffinfopackage/software) { get; } | Obtient le nom du package logiciel utilisé pour créer le fichier. |
| [Source](../../groupdocs.metadata.formats.riff/riffinfopackage/source) { get; } | Obtient le nom de la personne ou de l'organisation qui a fourni le sujet d'origine du fichier. |
| [Subject](../../groupdocs.metadata.formats.riff/riffinfopackage/subject) { get; } | Obtient une description du contenu du fichier, telle que "Vue aérienne de Seattle". |
| [Technician](../../groupdocs.metadata.formats.riff/riffinfopackage/technician) { get; } | Obtient le technicien qui a numérisé le fichier sujet. |

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

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espace de noms [GroupDocs.Metadata.Formats.Riff](../../groupdocs.metadata.formats.riff)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
