---
title: XmpPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Obtient ou définit le package de métadonnées XMP.
type: docs
weight: 20
url: /fr/net/groupdocs.metadata.formats.video/asfrootpackage/xmppackage/
---
## AsfRootPackage.XmpPackage property

Obtient ou définit le package de métadonnées XMP.

```csharp
public XmpPacketWrapper XmpPackage { get; set; }
```

### Valeur de la propriété

Le package de métadonnées XMP.

### Remarques

**Apprendre encore plus**

* [Utilisation des métadonnées XMP](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Exemples

Cet exemple montre comment extraire les métadonnées XMP d'un fichier.

```csharp
using (Metadata metadata = new Metadata(Constants.AsfWithXmp))
{
    var root = metadata.GetRootPackage<AsfRootPackage>();
    if (root.XmpPackage != null)
    {
        if (root.XmpPackage.Schemes.XmpBasic != null)
        {
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.CreatorTool);
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.CreateDate);
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.ModifyDate);
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.Label);
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.Nickname);

            // ...
        }

        if (root.XmpPackage.Schemes.DublinCore != null)
        {
            Console.WriteLine(root.XmpPackage.Schemes.DublinCore.Format);
            Console.WriteLine(root.XmpPackage.Schemes.DublinCore.Coverage);
            Console.WriteLine(root.XmpPackage.Schemes.DublinCore.Identifier);
            Console.WriteLine(root.XmpPackage.Schemes.DublinCore.Source);

            // ...
        }

        if (root.XmpPackage.Schemes.Photoshop != null)
        {
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.ColorMode);
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.IccProfile);
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.Country);
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.City);
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.DateCreated);

            // ... 
        }

        // ...
    }
}
```

### Voir également

* class [XmpPacketWrapper](../../../groupdocs.metadata.standards.xmp/xmppacketwrapper)
* class [AsfRootPackage](../../asfrootpackage)
* espace de noms [GroupDocs.Metadata.Formats.Video](../../asfrootpackage)
* Assemblée [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->