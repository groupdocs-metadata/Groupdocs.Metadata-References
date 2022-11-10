---
title: VCardCustomRecord
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente la classe de métadonnées denregistrement personnalisé vCard.
type: docs
weight: 680
url: /fr/net/groupdocs.metadata.formats.businesscard/vcardcustomrecord/
---
## VCardCustomRecord class

Représente la classe de métadonnées d'enregistrement personnalisé vCard.

```csharp
public class VCardCustomRecord : VCardRecord
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AltIdParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/altidparameter) { get; } | Obtient la valeur du paramètre des représentations alternatives. |
| [AnonymParameters](../../groupdocs.metadata.formats.businesscard/vcardrecord/anonymparameters) { get; } | Obtient les paramètres anonymes. |
| override [ContentType](../../groupdocs.metadata.formats.businesscard/vcardcustomrecord/contenttype) { get; } | Obtient le type de contenu de l'enregistrement. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [EncodingParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/encodingparameter) { get; } | Obtient la valeur du paramètre d'encodage. |
| [Group](../../groupdocs.metadata.formats.businesscard/vcardrecord/group) { get; } | Obtient la valeur de regroupement. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [LanguageParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/languageparameter) { get; } | Obtient la valeur du paramètre de langue. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [PrefParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/prefparameter) { get; } | Obtient le paramètre préféré. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [TypeName](../../groupdocs.metadata.formats.businesscard/vcardrecord/typename) { get; } | Obtient le type de l'enregistrement. |
| [TypeParameters](../../groupdocs.metadata.formats.businesscard/vcardrecord/typeparameters) { get; } | Obtient les valeurs des paramètres de type. |
| [Value](../../groupdocs.metadata.formats.businesscard/vcardcustomrecord/value) { get; } | Obtient la valeur d'enregistrement. |
| [ValueParameters](../../groupdocs.metadata.formats.businesscard/vcardrecord/valueparameters) { get; } | Récupère les paramètres de valeur. |

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

* [Travailler avec les métadonnées vCard](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Voir également

* class [VCardRecord](../vcardrecord)
* espace de noms [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
