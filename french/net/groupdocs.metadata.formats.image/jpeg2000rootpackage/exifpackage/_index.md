---
title: ExifPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Obtient ou définit le package de métadonnées EXIF.
type: docs
weight: 10
url: /fr/net/groupdocs.metadata.formats.image/jpeg2000rootpackage/exifpackage/
---
## Jpeg2000RootPackage.ExifPackage property

Obtient ou définit le package de métadonnées EXIF.

```csharp
public ExifPackage ExifPackage { get; set; }
```

### Valeur de la propriété

Le package de métadonnées EXIF.

### Remarques

**Apprendre encore plus**

* [Travailler avec les métadonnées EXIF](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Exemples

Cet exemple de code montre comment extraire les propriétés de base des métadonnées EXIF.

```csharp
using (Metadata metadata = new Metadata(Constants.Jpeg2000WithExif))
{
    var root = metadata.GetRootPackage<Jpeg2000RootPackage>();
    if (root.ExifPackage != null)
    {
        Console.WriteLine(root.ExifPackage.Artist);
        Console.WriteLine(root.ExifPackage.Copyright);
        Console.WriteLine(root.ExifPackage.ImageDescription);
        Console.WriteLine(root.ExifPackage.Make);
        Console.WriteLine(root.ExifPackage.Model);
        Console.WriteLine(root.ExifPackage.Software);
        Console.WriteLine(root.ExifPackage.ImageWidth);
        Console.WriteLine(root.ExifPackage.ImageLength);

        // ...

        Console.WriteLine(root.ExifPackage.ExifIfdPackage.BodySerialNumber);
        Console.WriteLine(root.ExifPackage.ExifIfdPackage.CameraOwnerName);
        Console.WriteLine(root.ExifPackage.ExifIfdPackage.UserComment);

        // ...

        Console.WriteLine(root.ExifPackage.GpsPackage.Altitude);
        Console.WriteLine(root.ExifPackage.GpsPackage.LatitudeRef);
        Console.WriteLine(root.ExifPackage.GpsPackage.LongitudeRef);

        // ...
    }
}
```

### Voir également

* class [ExifPackage](../../../groupdocs.metadata.standards.exif/exifpackage)
* class [Jpeg2000RootPackage](../../jpeg2000rootpackage)
* espace de noms [GroupDocs.Metadata.Formats.Image](../../jpeg2000rootpackage)
* Assemblée [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
