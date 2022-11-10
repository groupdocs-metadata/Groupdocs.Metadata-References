---
title: AviHeader
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente la structure AVIMAINHEADER dans une vidéo AVI.
type: docs
weight: 2380
url: /fr/net/groupdocs.metadata.formats.video/aviheader/
---
## AviHeader class

Représente la structure AVIMAINHEADER dans une vidéo AVI.

```csharp
public sealed class AviHeader : CustomPackage
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [AviHeader](aviheader)() | Initialise une nouvelle instance du[`AviHeader`](../aviheader) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AviHeaderFlags](../../groupdocs.metadata.formats.video/aviheader/aviheaderflags) { get; } | Obtient une combinaison au niveau du bit de zéro ou plusieurs drapeaux AVI. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [Height](../../groupdocs.metadata.formats.video/aviheader/height) { get; } | Obtient la hauteur du fichier AVI en pixels. |
| [InitialFrames](../../groupdocs.metadata.formats.video/aviheader/initialframes) { get; } | Obtient la trame initiale pour les fichiers entrelacés.  Les fichiers non entrelacés doivent spécifier zéro. Si vous créez des fichiers entrelacés, spécifiez le nombre d'images dans le fichier avant l'image initiale de la séquence AVI dans ce membre. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MaxBytesPerSec](../../groupdocs.metadata.formats.video/aviheader/maxbytespersec) { get; } | Obtient le débit de données maximal approximatif du fichier.  Cette valeur indique le nombre d'octets par seconde que le système doit gérer pour présenter une séquence AVI comme spécifié par les autres paramètres contenus dans l'en-tête principal et les morceaux d'en-tête de flux. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [MicroSecPerFrame](../../groupdocs.metadata.formats.video/aviheader/microsecperframe) { get; } | Obtient le nombre de microsecondes entre les trames. Cette valeur indique la durée globale du fichier. |
| [PaddingGranularity](../../groupdocs.metadata.formats.video/aviheader/paddinggranularity) { get; } | Obtient l'alignement des données, en octets. Complétez les données en multiples de cette valeur. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [Streams](../../groupdocs.metadata.formats.video/aviheader/streams) { get; } | Obtient le nombre de flux dans le fichier. Par exemple, un fichier audio et vidéo a deux flux. |
| [SuggestedBufferSize](../../groupdocs.metadata.formats.video/aviheader/suggestedbuffersize) { get; } | Obtient la taille de tampon suggérée pour lire le fichier.  Généralement, cette taille doit être suffisamment grande pour contenir le plus gros morceau du fichier. S'il est défini sur zéro, ou s'il est trop petit, le logiciel de lecture devra réallouer de la mémoire pendant la lecture, ce qui réduira les performances. Pour un fichier entrelacé, la taille de la mémoire tampon doit être suffisamment grande pour lire un enregistrement entier, et pas seulement un morceau. |
| [TotalFrames](../../groupdocs.metadata.formats.video/aviheader/totalframes) { get; } | Obtient le nombre total de trames de données dans le fichier. |
| [Width](../../groupdocs.metadata.formats.video/aviheader/width) { get; } | Obtient la largeur du fichier AVI en pixels. |

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

* [Utilisation des métadonnées dans les fichiers AVI](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+AVI+files)

### Voir également

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espace de noms [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
