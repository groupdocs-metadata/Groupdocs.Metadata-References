---
title: XmpIptcExtensionPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente le package IPTC Extension XMP.
type: docs
weight: 3150
url: /fr/net/groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/
---
## XmpIptcExtensionPackage class

Représente le package IPTC Extension XMP.

```csharp
public sealed class XmpIptcExtensionPackage : XmpPackage
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [XmpIptcExtensionPackage](xmpiptcextensionpackage)() | Initialise une nouvelle instance du[`XmpIptcExtensionPackage`](../xmpiptcextensionpackage) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AdditionalModelInformation](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/additionalmodelinformation) { get; set; } | Obtient ou définit les informations sur l'origine ethnique et les autres facettes du ou des modèles dans une image publiée par le modèle. |
| [AgesOfModels](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/agesofmodels) { get; set; } | Obtient ou définit l'âge des modèles humains au moment où cette image a été prise dans une image publiée par le modèle. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [DigitalImageGuid](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/digitalimageguid) { get; set; } | Obtient ou définit l'identifiant global unique pour cette image numérique. |
| [DigitalSourceType](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/digitalsourcetype) { get; set; } | Obtient ou définit le type de la source de cette image numérique. |
| [Event](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/event) { get; set; } | Obtient ou définit la description de l'événement spécifique au cours duquel la photo a été prise. |
| [IptcLastEdited](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/iptclastedited) { get; set; } | Obtient ou définit la date et éventuellement l'heure à laquelle l'un des champs de métadonnées de photo IPTC a été modifié pour la dernière fois. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MaxAvailableHeight](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/maxavailableheight) { get; set; } | Obtient ou définit la hauteur maximale disponible en pixels de la photo d'origine à partir de laquelle cette photo a été dérivée par réduction. |
| [MaxAvailableWidth](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/maxavailablewidth) { get; set; } | Obtient ou définit la largeur maximale disponible en pixels de la photo d'origine à partir de laquelle cette photo a été dérivée par réduction. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Obtient l'URI de l'espace de noms. |
| [OrganisationInImageCodes](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/organisationinimagecodes) { get; set; } | Obtient ou définit des codes à partir d'un vocabulaire contrôlé pour identifier les organisations ou les entreprises qui sont présentées dans l'image. |
| [OrganisationInImageNames](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/organisationinimagenames) { get; set; } | Obtient ou définit les noms des organisations ou des entreprises qui figurent dans l'image. |
| [PersonsInImage](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/personsinimage) { get; set; } | Obtient ou définit les noms des personnes dont parle le contenu de l'élément. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Récupère le préfixe xmlns. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
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
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/set#set_7)(string, string) | Définit la propriété de chaîne. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/set#set_2)(string, XmpArray) | Définit la valeur héritée de[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Définit la valeur héritée de[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Définit la valeur héritée de[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Définit les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. Cette méthode est une combinaison de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) et[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si une propriété existante satisfait le prédicat, sa valeur est mise à jour. S'il manque une propriété connue dans le package qui satisfait le prédicat, elle est ajoutée au package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Voir également

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* espace de noms [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
