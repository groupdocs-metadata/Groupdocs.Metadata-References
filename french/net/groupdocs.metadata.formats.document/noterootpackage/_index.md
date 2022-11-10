---
title: NoteRootPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente le package racine destiné à fonctionner avec les métadonnées dans un fichier de note électronique.
type: docs
weight: 970
url: /fr/net/groupdocs.metadata.formats.document/noterootpackage/
---
## NoteRootPackage class

Représente le package racine destiné à fonctionner avec les métadonnées dans un fichier de note électronique.

```csharp
public class NoteRootPackage : RootMetadataPackage
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [DocumentStatistics](../../groupdocs.metadata.formats.document/noterootpackage/documentstatistics) { get; } | Obtient le package de statistiques de document. |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Obtient le package de métadonnées de type de fichier. |
| [InspectionPackage](../../groupdocs.metadata.formats.document/noterootpackage/inspectionpackage) { get; } | Obtient un package de métadonnées contenant les résultats d'inspection pour le document. Le package contient des informations sur les parties de document qui peuvent être considérées comme des métadonnées dans certains cas. |
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

* [Utilisation des métadonnées dans les formats Note](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Note+formats)

### Exemples

Cet exemple de code montre comment inspecter un document de note.

```csharp
using (Metadata metadata = new Metadata(Constants.InputOne))
{
    var root = metadata.GetRootPackage<NoteRootPackage>();

    if (root.InspectionPackage.Pages != null)
    {
        foreach (var page in root.InspectionPackage.Pages)
        {
            Console.WriteLine(page.Title);
            Console.WriteLine(page.Author);
            Console.WriteLine(page.CreationTime);
            Console.WriteLine(page.LastModificationTime);
        }
    }
}
```

### Voir également

* class [RootMetadataPackage](../../groupdocs.metadata.common/rootmetadatapackage)
* espace de noms [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
