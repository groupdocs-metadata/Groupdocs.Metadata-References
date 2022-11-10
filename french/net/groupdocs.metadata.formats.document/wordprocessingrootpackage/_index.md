---
title: WordProcessingRootPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente le package racine permettant de travailler avec des métadonnées dans un document de traitement de texte.
type: docs
weight: 1310
url: /fr/net/groupdocs.metadata.formats.document/wordprocessingrootpackage/
---
## WordProcessingRootPackage class

Représente le package racine permettant de travailler avec des métadonnées dans un document de traitement de texte.

```csharp
public class WordProcessingRootPackage : DocumentRootPackage<WordProcessingPackage>, IDublinCore
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| virtual [DocumentProperties](../../groupdocs.metadata.formats.document/documentrootpackage-1/documentproperties) { get; } | Obtient les propriétés de métadonnées natives présentées dans le document. |
| [DocumentStatistics](../../groupdocs.metadata.formats.document/wordprocessingrootpackage/documentstatistics) { get; } | Obtient le package de statistiques de document. |
| [DublinCorePackage](../../groupdocs.metadata.formats.document/wordprocessingrootpackage/dublincorepackage) { get; } | Obtient le package de métadonnées Dublin Core extrait du document. |
| [FileType](../../groupdocs.metadata.formats.document/wordprocessingrootpackage/filetype) { get; } | Obtient le package de métadonnées de type de fichier. (2 properties) |
| [InspectionPackage](../../groupdocs.metadata.formats.document/wordprocessingrootpackage/inspectionpackage) { get; } | Obtient un package de métadonnées contenant les résultats d'inspection pour le document. Le package contient des informations sur les parties de document qui peuvent être considérées comme des métadonnées dans certains cas. |
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
| [UpdateDocumentStatistics](../../groupdocs.metadata.formats.document/wordprocessingrootpackage/updatedocumentstatistics)() | Recalcule le nombre de pages, paragraphes, mots, lignes, caractères dans le document et met à jour les packages de métadonnées appropriés. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Remarques

**Apprendre encore plus**

* [Utilisation des métadonnées dans les documents de traitement de texte](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### Exemples

Cet exemple de code montre comment lire les propriétés de métadonnées intégrées d'un document WordProcessing.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDocx))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    Console.WriteLine(root.DocumentProperties.Author);
    Console.WriteLine(root.DocumentProperties.CreatedTime);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Category);
    Console.WriteLine(root.DocumentProperties.Keywords);

    // ... 
}
```

### Voir également

* class [DocumentRootPackage&lt;TPackage&gt;](../documentrootpackage-1)
* class [WordProcessingPackage](../wordprocessingpackage)
* interface [IDublinCore](../../groupdocs.metadata.standards.dublincore/idublincore)
* espace de noms [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
