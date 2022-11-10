---
title: DiagramRootPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente le package racine destiné à fonctionner avec les métadonnées dans un diagramme.
type: docs
weight: 900
url: /fr/net/groupdocs.metadata.formats.document/diagramrootpackage/
---
## DiagramRootPackage class

Représente le package racine destiné à fonctionner avec les métadonnées dans un diagramme.

```csharp
public class DiagramRootPackage : DocumentRootPackage<DiagramPackage>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| virtual [DocumentProperties](../../groupdocs.metadata.formats.document/documentrootpackage-1/documentproperties) { get; } | Obtient les propriétés de métadonnées natives présentées dans le document. |
| [DocumentStatistics](../../groupdocs.metadata.formats.document/diagramrootpackage/documentstatistics) { get; } | Obtient le package de statistiques de document. |
| [FileType](../../groupdocs.metadata.formats.document/diagramrootpackage/filetype) { get; } | Obtient le package de métadonnées de type de fichier. (2 properties) |
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

* [Utilisation des métadonnées dans les diagrammes](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### Exemples

L'exemple de code suivant montre comment mettre à jour les propriétés de métadonnées intégrées dans un document de diagramme.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    root.DocumentProperties.Creator = "test author";
    root.DocumentProperties.TimeCreated = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputVdx);
}
```

### Voir également

* class [DocumentRootPackage&lt;TPackage&gt;](../documentrootpackage-1)
* class [DiagramPackage](../diagrampackage)
* espace de noms [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
