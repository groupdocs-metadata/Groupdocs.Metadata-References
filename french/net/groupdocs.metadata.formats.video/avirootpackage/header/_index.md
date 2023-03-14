---
title: Header
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Obtient le package dentête AVI.
type: docs
weight: 10
url: /fr/net/groupdocs.metadata.formats.video/avirootpackage/header/
---
## AviRootPackage.Header property

Obtient le package d'en-tête AVI.

```csharp
public AviHeader Header { get; }
```

### Valeur de la propriété

Le package d'en-tête AVI.

### Remarques

**Apprendre encore plus**

* [Utilisation des métadonnées dans les fichiers AVI](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+AVI+files)

### Exemples

Cet extrait de code montre comment lire les propriétés d'en-tête AVI.

```csharp
using (Metadata metadata = new Metadata(Constants.InputAvi))
{
    var root = metadata.GetRootPackage<AviRootPackage>();

    Console.WriteLine(root.Header.AviHeaderFlags);
    Console.WriteLine(root.Header.Height);
    Console.WriteLine(root.Header.Width);
    Console.WriteLine(root.Header.TotalFrames);
    Console.WriteLine(root.Header.InitialFrames);
    Console.WriteLine(root.Header.MaxBytesPerSec);
    Console.WriteLine(root.Header.PaddingGranularity);
    Console.WriteLine(root.Header.Streams);

    // ...
}
```

### Voir également

* class [AviHeader](../../aviheader)
* class [AviRootPackage](../../avirootpackage)
* espace de noms [GroupDocs.Metadata.Formats.Video](../../avirootpackage)
* Assemblée [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->