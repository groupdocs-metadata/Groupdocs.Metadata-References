---
title: Jpeg2000RootPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente le package racine destiné à fonctionner avec les métadonnées dans une image JPEG2000.
type: docs
weight: 1800
url: /fr/net/groupdocs.metadata.formats.image/jpeg2000rootpackage/
---
## Jpeg2000RootPackage class

Représente le package racine destiné à fonctionner avec les métadonnées dans une image JPEG2000.

```csharp
public class Jpeg2000RootPackage : ImageRootPackage, IExif, IXmp
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [ExifPackage](../../groupdocs.metadata.formats.image/jpeg2000rootpackage/exifpackage) { get; set; } | Obtient ou définit le package de métadonnées EXIF. |
| [FileType](../../groupdocs.metadata.formats.image/imagerootpackage/filetype) { get; } | Obtient le package de métadonnées de type de fichier. (2 properties) |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Jpeg2000Package](../../groupdocs.metadata.formats.image/jpeg2000rootpackage/jpeg2000package) { get; } | Obtient le package de métadonnées natives JPEG2000. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [XmpPackage](../../groupdocs.metadata.formats.image/jpeg2000rootpackage/xmppackage) { get; set; } | Obtient ou définit le package de métadonnées XMP. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ajoute des propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Détermine si le package contient une propriété de métadonnées avec le nom spécifié. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trouve les propriétés de métadonnées satisfaisant le prédicat spécifié. La recherche est récursive, elle affecte donc également tous les packages imbriqués. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Supprime les propriétés de métadonnées satisfaisant le prédicat spécifié. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Supprime les propriétés de métadonnées inscriptibles du package. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Définit les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. Cette méthode est une combinaison de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) et[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si une propriété existante satisfait le prédicat, sa valeur est mise à jour. S'il manque une propriété connue dans le package qui satisfait le prédicat, elle est ajoutée au package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Remarques

**Apprendre encore plus**

* [Utilisation des métadonnées dans les images JPEG2000](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG2000+images)
* [Utilisation des métadonnées XMP](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Voir également

* class [ImageRootPackage](../imagerootpackage)
* interface [IExif](../../groupdocs.metadata.standards.exif/iexif)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* espace de noms [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
