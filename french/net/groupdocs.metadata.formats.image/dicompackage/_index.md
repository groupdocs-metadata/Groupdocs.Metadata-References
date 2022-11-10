---
title: DicomPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente les métadonnées DICOM natives.
type: docs
weight: 1670
url: /fr/net/groupdocs.metadata.formats.image/dicompackage/
---
## DicomPackage class

Représente les métadonnées DICOM natives.

```csharp
public sealed class DicomPackage : CustomPackage
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [DicomPackage](dicompackage)() | Initialise une nouvelle instance du[`Metadata`](../../groupdocs.metadata/metadata) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BitsAllocated](../../groupdocs.metadata.formats.image/dicompackage/bitsallocated) { get; } | Obtient la valeur allouée des bits. |
| [Blues](../../groupdocs.metadata.formats.image/dicompackage/blues) { get; } | Obtient les couleurs du tableau du bleu. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [DicomInfo](../../groupdocs.metadata.formats.image/dicompackage/dicominfo) { get; } | Obtient les informations d'en-tête du fichier DICOM. |
| [Greens](../../groupdocs.metadata.formats.image/dicompackage/greens) { get; } | Obtient les couleurs du tableau du vert. |
| [HeaderBytes](../../groupdocs.metadata.formats.image/dicompackage/headerbytes) { get; } | Obtient les informations d'en-tête par octets. |
| [HeaderOffset](../../groupdocs.metadata.formats.image/dicompackage/headeroffset) { get; } | Obtient le décalage d'en-tête. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [NumberOfFrames](../../groupdocs.metadata.formats.image/dicompackage/numberofframes) { get; } | Obtient le nombre d'images. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [Reds](../../groupdocs.metadata.formats.image/dicompackage/reds) { get; } | Obtient les couleurs du tableau du rouge. |

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

* [Travailler avec les métadonnées DICOM](https://docs.groupdocs.com/display/metadatanet/Working+with+DICOM+metadata)

### Voir également

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espace de noms [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
