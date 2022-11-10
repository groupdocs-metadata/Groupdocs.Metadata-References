---
title: PsdRootPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente le package racine permettant de travailler avec des métadonnées dans un document Photoshop.
type: docs
weight: 1930
url: /fr/net/groupdocs.metadata.formats.image/psdrootpackage/
---
## PsdRootPackage class

Représente le package racine permettant de travailler avec des métadonnées dans un document Photoshop.

```csharp
public class PsdRootPackage : ImageRootPackage, IExif, IIptc, IXmp
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [ExifPackage](../../groupdocs.metadata.formats.image/psdrootpackage/exifpackage) { get; set; } | Obtient ou définit le package de métadonnées EXIF. |
| [FileType](../../groupdocs.metadata.formats.image/imagerootpackage/filetype) { get; } | Obtient le package de métadonnées de type de fichier. (2 properties) |
| [ImageResourcePackage](../../groupdocs.metadata.formats.image/psdrootpackage/imageresourcepackage) { get; } | Obtient le package de métadonnées Photoshop Image Resource. Les blocs de ressources d'image constituent l'unité de construction de base du format de fichier natif Photoshop. |
| [IptcPackage](../../groupdocs.metadata.formats.image/psdrootpackage/iptcpackage) { get; set; } | Obtient ou définit le package de métadonnées IPTC. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [PsdPackage](../../groupdocs.metadata.formats.image/psdrootpackage/psdpackage) { get; } | Obtient le package de métadonnées contenant des informations sur le fichier PSD. |
| [XmpPackage](../../groupdocs.metadata.formats.image/psdrootpackage/xmppackage) { get; set; } | Obtient ou définit le package de métadonnées XMP. |

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

* [Utilisation des métadonnées dans les images PSD](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PSD+images)
* [Travailler avec les métadonnées EXIF](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)
* [Utilisation des métadonnées XMP](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)
* [Utilisation des métadonnées IPTC IIM](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Voir également

* class [ImageRootPackage](../imagerootpackage)
* interface [IExif](../../groupdocs.metadata.standards.exif/iexif)
* interface [IIptc](../../groupdocs.metadata.standards.iptc/iiptc)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* espace de noms [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
