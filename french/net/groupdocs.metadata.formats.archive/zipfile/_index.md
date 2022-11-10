---
title: ZipFile
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente les métadonnées associées à un fichier ou un répertoire archivé.
type: docs
weight: 350
url: /fr/net/groupdocs.metadata.formats.archive/zipfile/
---
## ZipFile class

Représente les métadonnées associées à un fichier ou un répertoire archivé.

```csharp
public sealed class ZipFile : CustomPackage
```

## Propriétés

| Nom | La description |
| --- | --- |
| [CompressedSize](../../groupdocs.metadata.formats.archive/zipfile/compressedsize) { get; } | Obtient la taille compressée en octets. |
| [CompressionMethod](../../groupdocs.metadata.formats.archive/zipfile/compressionmethod) { get; } | Obtient la méthode de compression. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [Flags](../../groupdocs.metadata.formats.archive/zipfile/flags) { get; } | Obtient les indicateurs d'entrée ZIP. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [ModificationDateTime](../../groupdocs.metadata.formats.archive/zipfile/modificationdatetime) { get; } | Obtient la date et l'heure de la dernière modification. |
| [Name](../../groupdocs.metadata.formats.archive/zipfile/name) { get; } | Obtient le nom de l'entrée. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [RawName](../../groupdocs.metadata.formats.archive/zipfile/rawname) { get; } | Obtient un tableau d'octets représentant le nom de l'entrée. |
| [UncompressedSize](../../groupdocs.metadata.formats.archive/zipfile/uncompressedsize) { get; } | Obtient la taille non compressée en octets. |

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

* [Travailler avec des archives ZIP](https://docs.groupdocs.com/display/metadatanet/Working+with+ZIP+archives)

### Voir également

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espace de noms [GroupDocs.Metadata.Formats.Archive](../../groupdocs.metadata.formats.archive)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
