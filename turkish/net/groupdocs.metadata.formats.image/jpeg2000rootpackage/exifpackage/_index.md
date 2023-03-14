---
title: ExifPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: EXIF meta veri paketini alır veya ayarlar.
type: docs
weight: 10
url: /tr/net/groupdocs.metadata.formats.image/jpeg2000rootpackage/exifpackage/
---
## Jpeg2000RootPackage.ExifPackage property

EXIF meta veri paketini alır veya ayarlar.

```csharp
public ExifPackage ExifPackage { get; set; }
```

### Mülk değeri

EXIF meta veri paketi.

### Notlar

**Daha fazla bilgi edin**

* [EXIF meta verileriyle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Örnekler

Bu kod örneği, temel EXIF meta veri özelliklerinin nasıl çıkarılacağını gösterir.

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

### Ayrıca bakınız

* class [ExifPackage](../../../groupdocs.metadata.standards.exif/exifpackage)
* class [Jpeg2000RootPackage](../../jpeg2000rootpackage)
* ad alanı [GroupDocs.Metadata.Formats.Image](../../jpeg2000rootpackage)
* toplantı [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->