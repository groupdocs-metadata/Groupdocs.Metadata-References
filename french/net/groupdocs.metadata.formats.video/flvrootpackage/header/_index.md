---
title: Header
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Obtient le package dentête FLV.
type: docs
weight: 10
url: /fr/net/groupdocs.metadata.formats.video/flvrootpackage/header/
---
## FlvRootPackage.Header property

Obtient le package d'en-tête FLV.

```csharp
public FlvHeader Header { get; }
```

### Valeur de la propriété

Le paquet d'en-tête FLV.

### Remarques

**Apprendre encore plus**

* [Utilisation des métadonnées dans les fichiers FLV](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+FLV+files)

### Exemples

Cet exemple montre comment lire les propriétés d'en-tête FLV.

```csharp
using (Metadata metadata = new Metadata(Constants.InputFlv))
{
    var root = metadata.GetRootPackage<FlvRootPackage>();

    Console.WriteLine(root.Header.Version);
    Console.WriteLine(root.Header.HasAudioTags);
    Console.WriteLine(root.Header.HasVideoTags);
    Console.WriteLine(root.Header.TypeFlags);
}
```

### Voir également

* class [FlvHeader](../../flvheader)
* class [FlvRootPackage](../../flvrootpackage)
* espace de noms [GroupDocs.Metadata.Formats.Video](../../flvrootpackage)
* Assemblée [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
