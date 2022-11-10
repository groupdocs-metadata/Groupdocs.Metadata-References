---
title: MatroskaTag
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente les métadonnées décrivant les pistes les éditions les chapitres les pièces jointes ou le segment dans son ensemble dans une vidéo Matroska.
type: docs
weight: 2530
url: /fr/net/groupdocs.metadata.formats.video/matroskatag/
---
## MatroskaTag class

Représente les métadonnées décrivant les pistes, les éditions, les chapitres, les pièces jointes ou le segment dans son ensemble dans une vidéo Matroska.

```csharp
public class MatroskaTag : MatroskaBasePackage
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [SimpleTags](../../groupdocs.metadata.formats.video/matroskatag/simpletags) { get; } | Obtient les informations générales sur la cible. |
| [TagTrackUid](../../groupdocs.metadata.formats.video/matroskatag/tagtrackuid) { get; } | Obtient un identifiant unique pour identifier la ou les pistes auxquelles appartiennent les balises. Si la valeur est 0 à ce niveau, les balises s'appliquent à toutes les pistes du segment. |
| [TargetType](../../groupdocs.metadata.formats.video/matroskatag/targettype) { get; } | Obtient une chaîne d'information qui peut être utilisée pour afficher le niveau logique de la cible. Comme "ALBUM", "TRACK", "MOVIE", "CHAPTER", etc. |
| [TargetTypeValue](../../groupdocs.metadata.formats.video/matroskatag/targettypevalue) { get; } | Obtient le nombre indiquant le niveau logique de la cible. |

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

* [Utilisation des métadonnées dans les fichiers Matroska (MKV)](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### Voir également

* class [MatroskaBasePackage](../matroskabasepackage)
* espace de noms [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
