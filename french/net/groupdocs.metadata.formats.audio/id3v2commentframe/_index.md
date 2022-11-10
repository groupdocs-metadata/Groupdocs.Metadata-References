---
title: ID3V2CommentFrame
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente une trame COMM dans unID3V2Tag./id3v2tag .
type: docs
weight: 440
url: /fr/net/groupdocs.metadata.formats.audio/id3v2commentframe/
---
## ID3V2CommentFrame class

Représente une trame COMM dans un[`ID3V2Tag`](../id3v2tag) .

```csharp
public sealed class ID3V2CommentFrame : ID3V2TagFrame
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ID3V2CommentFrame](id3v2commentframe)(ID3V2EncodingType, string, string, string) | Initialise une nouvelle instance du[`ID3V2CommentFrame`](../id3v2commentframe) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [CommentEncoding](../../groupdocs.metadata.formats.audio/id3v2commentframe/commentencoding) { get; } | Récupère l'encodage du commentaire. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [Data](../../groupdocs.metadata.formats.audio/id3v2tagframe/data) { get; } | Obtient les données de trame. |
| [Flags](../../groupdocs.metadata.formats.audio/id3v2tagframe/flags) { get; } | Obtient les drapeaux de trame. |
| [Id](../../groupdocs.metadata.formats.audio/id3v2tagframe/id) { get; } | Obtient l'identifiant du cadre (quatre caractères correspondant au modèle [A-Z0-9]). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [Language](../../groupdocs.metadata.formats.audio/id3v2commentframe/language) { get; } | Obtient la langue du commentaire (3 caractères). |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [ShortContentDescription](../../groupdocs.metadata.formats.audio/id3v2commentframe/shortcontentdescription) { get; } | Obtient la courte description du contenu. |
| [Text](../../groupdocs.metadata.formats.audio/id3v2commentframe/text) { get; } | Obtient le texte du commentaire. |

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

Ce cadre est destiné à tout type d'information en texte intégral qui ne rentre dans aucun autre cadre.

**Apprendre encore plus**

* [Gestion de la balise ID3v2](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Voir également

* class [ID3V2TagFrame](../id3v2tagframe)
* espace de noms [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
