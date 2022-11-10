---
title: XmpResourceEvent
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente un événement de haut niveau qui sest produit lors du traitement dune ressource.
type: docs
weight: 3540
url: /fr/net/groupdocs.metadata.standards.xmp/xmpresourceevent/
---
## XmpResourceEvent class

Représente un événement de haut niveau qui s'est produit lors du traitement d'une ressource.

```csharp
public sealed class XmpResourceEvent : XmpComplexType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [XmpResourceEvent](xmpresourceevent)() | Initialise une nouvelle instance du[`XmpResourceEvent`](../xmpresourceevent) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Action](../../groupdocs.metadata.standards.xmp/xmpresourceevent/action) { get; set; } | Obtient ou définit l'action qui s'est produite. |
| [Changed](../../groupdocs.metadata.standards.xmp/xmpresourceevent/changed) { get; set; } | Obtient ou définit une liste délimitée par des points-virgules des parties de la ressource qui ont été modifiées depuis l'historique des événements précédents. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [InstanceID](../../groupdocs.metadata.standards.xmp/xmpresourceevent/instanceid) { get; set; } | Obtient ou définit la valeur de la propriété xmpMM:InstanceID pour la ressource (de sortie) modifiée. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Obtient les URI d'espace de noms utilisés dans le[`XmpComplexType`](../xmpcomplextype) instance. |
| [Parameters](../../groupdocs.metadata.standards.xmp/xmpresourceevent/parameters) { get; set; } | Obtient ou définit la description supplémentaire de l'action. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Obtient les préfixes d'espace de noms utilisés dans le[`XmpComplexType`](../xmpcomplextype) instance. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [SoftwareAgent](../../groupdocs.metadata.standards.xmp/xmpresourceevent/softwareagent) { get; set; } | Obtient ou définit l'agent logiciel qui a effectué l'action. |
| [When](../../groupdocs.metadata.standards.xmp/xmpresourceevent/when) { get; set; } | Obtient ou définit l'horodatage du moment où l'action s'est produite. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ajoute des propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Détermine si le package contient une propriété de métadonnées avec le nom spécifié. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trouve les propriétés de métadonnées satisfaisant le prédicat spécifié. La recherche est récursive, elle affecte donc également tous les packages imbriqués. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | Obtient l'URI de l'espace de noms associé au préfixe spécifié. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | Renvoie la valeur contenue dans la chaîne au format XMP. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Supprime les propriétés de métadonnées satisfaisant le prédicat spécifié. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Supprime les propriétés de métadonnées inscriptibles du package. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Définit les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. Cette méthode est une combinaison de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) et[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si une propriété existante satisfait le prédicat, sa valeur est mise à jour. S'il manque une propriété connue dans le package qui satisfait le prédicat, elle est ajoutée au package. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | Renvoie unString qui représente cette instance. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Voir également

* class [XmpComplexType](../xmpcomplextype)
* espace de noms [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
