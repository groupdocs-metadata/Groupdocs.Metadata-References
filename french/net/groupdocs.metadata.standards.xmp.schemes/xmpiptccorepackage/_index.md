---
title: XmpIptcCorePackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente le package IPTC Core XMP.
type: docs
weight: 3140
url: /fr/net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/
---
## XmpIptcCorePackage class

Représente le package IPTC Core XMP.

```csharp
public sealed class XmpIptcCorePackage : XmpPackage
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [XmpIptcCorePackage](xmpiptccorepackage)() | Initialise une nouvelle instance du[`XmpIptcCorePackage`](../xmpiptccorepackage) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [CountryCode](../../groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/countrycode) { get; set; } | Obtient ou définit le code du pays sur lequel le contenu se concentre. Le code doit être extrait du code ISO 3166 à deux ou trois lettres. |
| [IntellectualGenre](../../groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/intellectualgenre) { get; set; } | Obtient ou définit le genre intellectuel. Décrit la nature, la caractéristique intellectuelle, artistique ou journalistique d'un objet d'actualité, et non spécifiquement son contenu. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [Location](../../groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/location) { get; set; } | Obtient ou définit l'emplacement sur lequel le contenu se concentre. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Obtient l'URI de l'espace de noms. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Récupère le préfixe xmlns. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [Scenes](../../groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/scenes) { get; set; } | Obtient ou définit la scène du contenu de la photo. |
| [SubjectCodes](../../groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/subjectcodes) { get; set; } | Obtient ou définit un ou plusieurs sujets de la taxonomie IPTC "Subject-NewsCodes" pour catégoriser le contenu. Chaque sujet est représenté par une chaîne de 8 chiffres dans une liste non ordonnée. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Obtient l'espace de noms XML. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ajoute des propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Supprime toutes les propriétés XMP. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Détermine si le package contient une propriété de métadonnées avec le nom spécifié. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trouve les propriétés de métadonnées satisfaisant le prédicat spécifié. La recherche est récursive, elle affecte donc également tous les packages imbriqués. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Convertit la valeur XMP en représentation XML. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Supprime la propriété avec le nom spécifié. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Supprime les propriétés de métadonnées satisfaisant le prédicat spécifié. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Supprime les propriétés de métadonnées inscriptibles du package. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Définit la propriété booléenne. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | EnsemblesDateTime propriété. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Définit la propriété double. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Définit la propriété entière. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, string) | Définit la propriété de chaîne. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Définit la valeur héritée de[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Définit la valeur héritée de[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Définit la valeur héritée de[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Définit les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. Cette méthode est une combinaison de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) et[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si une propriété existante satisfait le prédicat, sa valeur est mise à jour. S'il manque une propriété connue dans le package qui satisfait le prédicat, elle est ajoutée au package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Voir également

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* espace de noms [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
