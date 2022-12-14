---
title: FileType
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Obtient le package de métadonnées de type de fichier.
type: docs
weight: 20
url: /fr/net/groupdocs.metadata.formats.document/diagramrootpackage/filetype/
---
## DiagramRootPackage.FileType property

Obtient le package de métadonnées de type de fichier.

```csharp
public DiagramTypePackage FileType { get; }
```

### Valeur de la propriété

Le package de métadonnées de type de fichier.

### Exemples

Cet exemple de code montre comment détecter le type exact d'un diagramme chargé et extraire des informations supplémentaires sur le format de fichier.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    Console.WriteLine(root.FileType.FileFormat);
    Console.WriteLine(root.FileType.DiagramFormat);
    Console.WriteLine(root.FileType.MimeType);
    Console.WriteLine(root.FileType.Extension);
}
```

### Voir également

* class [DiagramTypePackage](../../diagramtypepackage)
* class [DiagramRootPackage](../../diagramrootpackage)
* espace de noms [GroupDocs.Metadata.Formats.Document](../../diagramrootpackage)
* Assemblée [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
