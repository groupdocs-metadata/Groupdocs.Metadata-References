---
title: CadRootPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente le package racine permettant de travailler avec des métadonnées dans un dessin CAO.
type: docs
weight: 850
url: /fr/net/groupdocs.metadata.formats.cad/cadrootpackage/
---
## CadRootPackage class

Représente le package racine permettant de travailler avec des métadonnées dans un dessin CAO.

```csharp
public abstract class CadRootPackage : RootMetadataPackage
```

## Propriétés

| Nom | La description |
| --- | --- |
| [CadPackage](../../groupdocs.metadata.formats.cad/cadrootpackage/cadpackage) { get; } | Obtient le package de métadonnées CAO. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Obtient le package de métadonnées de type de fichier. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ajoute des propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Détermine si le package contient une propriété de métadonnées avec le nom spécifié. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trouve les propriétés de métadonnées satisfaisant le prédicat spécifié. La recherche est récursive, elle affecte donc également tous les packages imbriqués. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Supprime les propriétés de métadonnées satisfaisant le prédicat spécifié. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Supprime les propriétés de métadonnées inscriptibles du package. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Définit les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. Cette méthode est une combinaison de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) et[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si une propriété existante satisfait le prédicat, sa valeur est mise à jour. S'il manque une propriété connue dans le package qui satisfait le prédicat, elle est ajoutée au package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Remarques

**Apprendre encore plus**

* [Utilisation des métadonnées CAO](https://docs.groupdocs.com/display/metadatanet/Working+with+CAD+metadata)

### Exemples

Cet exemple de code montre comment lire les métadonnées d'un dessin CAO.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDxf))
{
    var root = metadata.GetRootPackage<CadRootPackage>();

    Console.WriteLine(root.CadPackage.AcadVersion);
    Console.WriteLine(root.CadPackage.Author);
    Console.WriteLine(root.CadPackage.Comments);
    Console.WriteLine(root.CadPackage.CreatedDateTime);
    Console.WriteLine(root.CadPackage.HyperlinkBase);
    Console.WriteLine(root.CadPackage.Keywords);
    Console.WriteLine(root.CadPackage.LastSavedBy);
    Console.WriteLine(root.CadPackage.Title);

    // ...
}
```

### Voir également

* class [RootMetadataPackage](../../groupdocs.metadata.common/rootmetadatapackage)
* espace de noms [GroupDocs.Metadata.Formats.Cad](../../groupdocs.metadata.formats.cad)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
