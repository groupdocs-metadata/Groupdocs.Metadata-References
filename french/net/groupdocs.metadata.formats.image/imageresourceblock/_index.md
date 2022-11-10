---
title: ImageResourceBlock
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente un bloc de ressource dimage Photoshop.  Les blocs de ressources dimage sont lunité de construction de base de plusieurs formats de fichiers y compris le format de fichier natif de Photoshop JPEG et TIFF. Les ressources dimage sont utilisées pour stocker des données non pixelisées associées à des images telles que des chemins doutils de stylet.
type: docs
weight: 1740
url: /fr/net/groupdocs.metadata.formats.image/imageresourceblock/
---
## ImageResourceBlock class

Représente un bloc de ressource d'image Photoshop.  Les blocs de ressources d'image sont l'unité de construction de base de plusieurs formats de fichiers, y compris le format de fichier natif de Photoshop, JPEG et TIFF. Les ressources d'image sont utilisées pour stocker des données non pixelisées associées à des images, telles que des chemins d'outils de stylet.

```csharp
public sealed class ImageResourceBlock : CustomPackage
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [Data](../../groupdocs.metadata.formats.image/imageresourceblock/data) { get; } | Obtient les données de ressource. |
| [ID](../../groupdocs.metadata.formats.image/imageresourceblock/id) { get; } | Obtient l'identifiant unique de la ressource. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [Name](../../groupdocs.metadata.formats.image/imageresourceblock/name) { get; } | Obtient le nom du bloc de ressources d'image. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [Signature](../../groupdocs.metadata.formats.image/imageresourceblock/signature) { get; } | Obtient la signature du bloc de ressources d'image. |

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

* [Utilisation des métadonnées dans les images PSD](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PSD+images)

### Voir également

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espace de noms [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
