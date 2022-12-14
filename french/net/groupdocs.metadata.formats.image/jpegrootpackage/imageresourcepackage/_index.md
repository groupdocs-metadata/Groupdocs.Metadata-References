---
title: ImageResourcePackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Obtient le package de métadonnées Photoshop Image Resource. Les blocs de ressources dimage constituent lunité de construction de base du format de fichier natif Photoshop.
type: docs
weight: 20
url: /fr/net/groupdocs.metadata.formats.image/jpegrootpackage/imageresourcepackage/
---
## JpegRootPackage.ImageResourcePackage property

Obtient le package de métadonnées Photoshop Image Resource. Les blocs de ressources d'image constituent l'unité de construction de base du format de fichier natif Photoshop.

```csharp
public ImageResourcePackage ImageResourcePackage { get; }
```

### Valeur de la propriété

Le package de métadonnées Image Resource.

### Remarques

**Apprendre encore plus**

* [Utilisation des métadonnées dans les images JPEG](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG+images)

### Exemples

L'exemple de code ci-dessous montre comment extraire des blocs de ressources d'image (blocs de construction du format de fichier Photoshop) à partir d'une image JPEG.

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithIrb))
{
    var root = metadata.GetRootPackage<JpegRootPackage>();

    if (root.ImageResourcePackage != null)
    {
        foreach (var block in root.ImageResourcePackage.ToList())
        {
            Console.WriteLine(block.Signature);
            Console.WriteLine(block.ID);
            Console.WriteLine(block.Name);
            Console.WriteLine(block.Data);
        }
    }
}
```

### Voir également

* class [ImageResourcePackage](../../imageresourcepackage)
* class [JpegRootPackage](../../jpegrootpackage)
* espace de noms [GroupDocs.Metadata.Formats.Image](../../jpegrootpackage)
* Assemblée [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
