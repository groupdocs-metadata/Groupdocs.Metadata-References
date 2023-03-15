---
title: ExifPackage
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Λαμβάνει ή ορίζει το πακέτο μεταδεδομένων EXIF.
type: docs
weight: 10
url: /el/net/groupdocs.metadata.formats.image/jpeg2000rootpackage/exifpackage/
---
## Jpeg2000RootPackage.ExifPackage property

Λαμβάνει ή ορίζει το πακέτο μεταδεδομένων EXIF.

```csharp
public ExifPackage ExifPackage { get; set; }
```

### Αξία περιουσίας

Το πακέτο μεταδεδομένων EXIF.

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Εργασία με μεταδεδομένα EXIF](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Παραδείγματα

Αυτό το δείγμα κώδικα δείχνει πώς να εξαγάγετε βασικές ιδιότητες μεταδεδομένων EXIF.

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

        //...

        Console.WriteLine(root.ExifPackage.ExifIfdPackage.BodySerialNumber);
        Console.WriteLine(root.ExifPackage.ExifIfdPackage.CameraOwnerName);
        Console.WriteLine(root.ExifPackage.ExifIfdPackage.UserComment);

        //...

        Console.WriteLine(root.ExifPackage.GpsPackage.Altitude);
        Console.WriteLine(root.ExifPackage.GpsPackage.LatitudeRef);
        Console.WriteLine(root.ExifPackage.GpsPackage.LongitudeRef);

        //...
    }
}
```

### Δείτε επίσης

* class [ExifPackage](../../../groupdocs.metadata.standards.exif/exifpackage)
* class [Jpeg2000RootPackage](../../jpeg2000rootpackage)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.Image](../../jpeg2000rootpackage)
* συνέλευση [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->