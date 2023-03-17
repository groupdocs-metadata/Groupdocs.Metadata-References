---
title: ExifPackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Haalt het EXIFmetadatapakket op of stelt het in.
type: docs
weight: 10
url: /nl/net/groupdocs.metadata.formats.image/heifrootpackage/exifpackage/
---
## HeifRootPackage.ExifPackage property

Haalt het EXIF-metadatapakket op of stelt het in.

```csharp
public ExifPackage ExifPackage { get; set; }
```

### Eigendoms-waarde

Het EXIF-metadatapakket.

### Opmerkingen

**Kom meer te weten**

* [Werken met EXIF-metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Voorbeelden

Dit codevoorbeeld laat zien hoe u basis-EXIF-metadata-eigenschappen extraheert.

```csharp
using (Metadata metadata = new Metadata(Constants.HeifWithExif))
{
    var root = metadata.GetRootPackage<HeifRootPackage>();
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

### Zie ook

* class [ExifPackage](../../../groupdocs.metadata.standards.exif/exifpackage)
* class [HeifRootPackage](../../heifrootpackage)
* naamruimte [GroupDocs.Metadata.Formats.Image](../../heifrootpackage)
* montage [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->