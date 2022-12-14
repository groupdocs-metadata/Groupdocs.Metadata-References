---
title: DocumentStatistics
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Obtient le package de statistiques de document.
type: docs
weight: 10
url: /fr/net/groupdocs.metadata.formats.document/presentationrootpackage/documentstatistics/
---
## PresentationRootPackage.DocumentStatistics property

Obtient le package de statistiques de document.

```csharp
public DocumentStatistics DocumentStatistics { get; }
```

### Valeur de la propriété

Le package de statistiques de documents.

### Remarques

**Apprendre encore plus**

* [Utilisation des métadonnées dans les présentations](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Presentations)

### Exemples

Cet exemple de code montre comment obtenir des statistiques textuelles simples pour une présentation.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPpt))
{
    var root = metadata.GetRootPackage<PresentationRootPackage>();

    Console.WriteLine(root.DocumentStatistics.CharacterCount);
    Console.WriteLine(root.DocumentStatistics.PageCount);
    Console.WriteLine(root.DocumentStatistics.WordCount);
}
```

### Voir également

* class [DocumentStatistics](../../documentstatistics)
* class [PresentationRootPackage](../../presentationrootpackage)
* espace de noms [GroupDocs.Metadata.Formats.Document](../../presentationrootpackage)
* Assemblée [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
