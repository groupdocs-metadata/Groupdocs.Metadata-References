---
title: ExifPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mendapat atau menyetel paket metadata EXIF.
type: docs
weight: 10
url: /id/net/groupdocs.metadata.formats.image/psdrootpackage/exifpackage/
---
## PsdRootPackage.ExifPackage property

Mendapat atau menyetel paket metadata EXIF.

```csharp
public ExifPackage ExifPackage { get; set; }
```

### Nilai properti

Paket metadata EXIF.

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata EXIF](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Contoh

Contoh kode ini menunjukkan cara mengekstrak properti metadata EXIF dasar dari gambar PSD.

```csharp
using (Metadata metadata = new Metadata(Constants.PsdWithExif))
{
    var root = metadata.GetRootPackage<PsdRootPackage>();
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

### Lihat juga

* class [ExifPackage](../../../groupdocs.metadata.standards.exif/exifpackage)
* class [PsdRootPackage](../../psdrootpackage)
* ruang nama [GroupDocs.Metadata.Formats.Image](../../psdrootpackage)
* perakitan [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->