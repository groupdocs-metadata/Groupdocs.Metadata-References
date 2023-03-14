---
title: GifImageTypePackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente un package de métadonnées contenant des informations de format de fichier spécifiques au format GIF.
type: docs
weight: 1710
url: /fr/net/groupdocs.metadata.formats.image/gifimagetypepackage/
---
## GifImageTypePackage class

Représente un package de métadonnées contenant des informations de format de fichier spécifiques au format GIF.

```csharp
public class GifImageTypePackage : ImageTypePackage
```

## Propriétés

| Nom | La description |
| --- | --- |
| [ByteOrder](../../groupdocs.metadata.formats.image/imagetypepackage/byteorder) { get; } | Obtient l'ordre des octets de l'image. Veuillez consulter[https://en.wikipedia.org/wiki/Endianness](https://en.wikipedia.org/wiki/Endianness) pour plus d'informations. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [Extension](../../groupdocs.metadata.common/filetypepackage/extension) { get; } | Obtient l'extension de fichier. |
| [FileFormat](../../groupdocs.metadata.common/filetypepackage/fileformat) { get; } | Obtient le format de fichier. |
| [Height](../../groupdocs.metadata.formats.image/imagetypepackage/height) { get; } | Obtient la hauteur de l'image. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [MimeType](../../groupdocs.metadata.common/filetypepackage/mimetype) { get; } | Obtient le type MIME. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [Version](../../groupdocs.metadata.formats.image/gifimagetypepackage/version) { get; } | Obtient la version du format. |
| [Width](../../groupdocs.metadata.formats.image/imagetypepackage/width) { get; } | Obtient la largeur de l'image. |

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

* class [ImageTypePackage](../imagetypepackage)
* espace de noms [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->