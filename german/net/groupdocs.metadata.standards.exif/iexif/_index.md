---
title: IExif
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Definiert Basisoperationen die mit EXIFMetadaten arbeiten sollen.
type: docs
weight: 2800
url: /de/net/groupdocs.metadata.standards.exif/iexif/
---
## IExif interface

Definiert Basisoperationen, die mit EXIF-Metadaten arbeiten sollen.

```csharp
public interface IExif
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ExifPackage](../../groupdocs.metadata.standards.exif/iexif/exifpackage) { get; set; } | Ruft das mit der Datei verknüpfte EXIF-Metadatenpaket ab oder legt es fest. |

### Bemerkungen

**Mehr erfahren**

* [Arbeiten mit EXIF-Metadaten](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Beispiele

Dieses Codebeispiel zeigt, wie grundlegende EXIF-Metadateneigenschaften extrahiert werden.

```csharp
using (Metadata metadata = new Metadata(Constants.TiffWithExif))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null && root.ExifPackage != null)
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

### Siehe auch

* namensraum [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->