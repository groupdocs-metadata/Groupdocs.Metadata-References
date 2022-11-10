---
title: PngInternationalTextChunk
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente des données textuelles internationales extraites dune image PNG.
type: docs
weight: 1840
url: /fr/net/groupdocs.metadata.formats.image/pnginternationaltextchunk/
---
## PngInternationalTextChunk class

Représente des données textuelles internationales extraites d'une image PNG.

```csharp
public class PngInternationalTextChunk : PngCompressedTextChunk
```

## Propriétés

| Nom | La description |
| --- | --- |
| [CompressionMethod](../../groupdocs.metadata.formats.image/pngcompressedtextchunk/compressionmethod) { get; } | Obtient l'algorithme utilisé pour compresser les données de bloc. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [IsCompressed](../../groupdocs.metadata.formats.image/pnginternationaltextchunk/iscompressed) { get; } | Obtient une valeur indiquant si le bloc est compressé. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [Keyword](../../groupdocs.metadata.formats.image/pngtextchunk/keyword) { get; } | Obtient le mot-clé qui indique le type d'informations représentées par le morceau. |
| [Language](../../groupdocs.metadata.formats.image/pnginternationaltextchunk/language) { get; } | Obtient le langage humain utilisé par le mot-clé traduit et le texte. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [Text](../../groupdocs.metadata.formats.image/pngtextchunk/text) { get; } | Obtient la chaîne de texte réelle représentée par le morceau. |
| [TranslatedKeyword](../../groupdocs.metadata.formats.image/pnginternationaltextchunk/translatedkeyword) { get; } | Obtient le mot-clé traduit qui contient une traduction du mot-clé dans la langue indiquée par la propriété language. |

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

* class [PngCompressedTextChunk](../pngcompressedtextchunk)
* espace de noms [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
