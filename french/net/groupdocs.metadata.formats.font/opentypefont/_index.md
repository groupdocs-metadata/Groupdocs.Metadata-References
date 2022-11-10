---
title: OpenTypeFont
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente une seule police extraite dun fichier.
type: docs
weight: 1460
url: /fr/net/groupdocs.metadata.formats.font/opentypefont/
---
## OpenTypeFont class

Représente une seule police extraite d'un fichier.

```csharp
public class OpenTypeFont : CustomPackage
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [Created](../../groupdocs.metadata.formats.font/opentypefont/created) { get; } | Obtient la date de création. |
| [DirectionHint](../../groupdocs.metadata.formats.font/opentypefont/directionhint) { get; } | Obtient l'indication de direction. |
| [EmbeddingLicensingRights](../../groupdocs.metadata.formats.font/opentypefont/embeddinglicensingrights) { get; } | Obtient le type de droits de licence d'intégration. |
| [Flags](../../groupdocs.metadata.formats.font/opentypefont/flags) { get; } | Obtient les drapeaux d'en-tête. |
| [FontFamilyName](../../groupdocs.metadata.formats.font/opentypefont/fontfamilyname) { get; } | Obtient le nom de la famille de polices. |
| [FontRevision](../../groupdocs.metadata.formats.font/opentypefont/fontrevision) { get; } | Obtient la révision de la police. |
| [FontSubfamilyName](../../groupdocs.metadata.formats.font/opentypefont/fontsubfamilyname) { get; } | Obtient le nom de la sous-famille de polices. |
| [FullFontName](../../groupdocs.metadata.formats.font/opentypefont/fullfontname) { get; } | Obtient le nom complet de la police. |
| [GlyphBounds](../../groupdocs.metadata.formats.font/opentypefont/glyphbounds) { get; } | Obtient les limites du glyphe. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MajorVersion](../../groupdocs.metadata.formats.font/opentypefont/majorversion) { get; } | Obtient la version majeure de l'en-tête. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [MinorVersion](../../groupdocs.metadata.formats.font/opentypefont/minorversion) { get; } | Obtient la version mineure de l'en-tête. |
| [Modified](../../groupdocs.metadata.formats.font/opentypefont/modified) { get; } | Obtient la date modifiée. |
| [Names](../../groupdocs.metadata.formats.font/opentypefont/names) { get; } | Obtient les enregistrements de nom. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [SfntVersion](../../groupdocs.metadata.formats.font/opentypefont/sfntversion) { get; } | Obtient la version SFNT de l'en-tête. |
| [Style](../../groupdocs.metadata.formats.font/opentypefont/style) { get; } | Obtient le style de police. |
| [TypographicFamily](../../groupdocs.metadata.formats.font/opentypefont/typographicfamily) { get; } | Obtient la famille typographique. |
| [TypographicSubfamily](../../groupdocs.metadata.formats.font/opentypefont/typographicsubfamily) { get; } | Obtient la sous-famille typographique. |
| [Weight](../../groupdocs.metadata.formats.font/opentypefont/weight) { get; } | Obtient le poids de la police. |
| [Width](../../groupdocs.metadata.formats.font/opentypefont/width) { get; } | Obtient la largeur de la police. |

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

* [Utilisation des polices OpenType](https://docs.groupdocs.com/display/metadatanet/Working+with+OpenType+fonts)

### Voir également

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espace de noms [GroupDocs.Metadata.Formats.Font](../../groupdocs.metadata.formats.font)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
