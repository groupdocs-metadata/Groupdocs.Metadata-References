---
title: CadPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente les métadonnées CAO conception assistée par ordinateur.
type: docs
weight: 840
url: /fr/net/groupdocs.metadata.formats.cad/cadpackage/
---
## CadPackage class

Représente les métadonnées CAO (conception assistée par ordinateur).

```csharp
public sealed class CadPackage : CustomPackage
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AcadVersion](../../groupdocs.metadata.formats.cad/cadpackage/acadversion) { get; } | Obtient le numéro de version de la base de données de dessins AutoCAD. |
| [Author](../../groupdocs.metadata.formats.cad/cadpackage/author) { get; } | Obtient l'auteur du dessin. |
| [Comments](../../groupdocs.metadata.formats.cad/cadpackage/comments) { get; } | Obtient les commentaires de l'utilisateur. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [CreatedDateTime](../../groupdocs.metadata.formats.cad/cadpackage/createddatetime) { get; } | Obtient la date et l'heure de création du dessin. |
| [CustomProperties](../../groupdocs.metadata.formats.cad/cadpackage/customproperties) { get; } | Obtient le package contenant les propriétés de métadonnées personnalisées. |
| [Height](../../groupdocs.metadata.formats.cad/cadpackage/height) { get; } | Obtient la hauteur du dessin. |
| [HyperlinkBase](../../groupdocs.metadata.formats.cad/cadpackage/hyperlinkbase) { get; } | Obtient la base du lien hypertexte. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [Keywords](../../groupdocs.metadata.formats.cad/cadpackage/keywords) { get; } | Obtient les mots-clés. |
| [LastSavedBy](../../groupdocs.metadata.formats.cad/cadpackage/lastsavedby) { get; } | Obtient le nom du dernier éditeur. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [ModifiedDateTime](../../groupdocs.metadata.formats.cad/cadpackage/modifieddatetime) { get; } | Obtient la date et l'heure auxquelles le dessin a été modifié. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [RevisionNumber](../../groupdocs.metadata.formats.cad/cadpackage/revisionnumber) { get; } | Obtient le numéro de révision. |
| [Subject](../../groupdocs.metadata.formats.cad/cadpackage/subject) { get; } | Obtient le sujet. |
| [Title](../../groupdocs.metadata.formats.cad/cadpackage/title) { get; } | Obtient le titre. |
| [Width](../../groupdocs.metadata.formats.cad/cadpackage/width) { get; } | Obtient la largeur du dessin. |

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

* [Utilisation des métadonnées CAO](https://docs.groupdocs.com/display/metadatanet/Working+with+CAD+metadata)

### Voir également

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espace de noms [GroupDocs.Metadata.Formats.Cad](../../groupdocs.metadata.formats.cad)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
