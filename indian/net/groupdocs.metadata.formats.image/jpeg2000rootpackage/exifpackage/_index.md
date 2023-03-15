---
title: ExifPackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: EXIF मेटडेट पैकेज प्रप्त य सेट करत है
type: docs
weight: 10
url: /hi/net/groupdocs.metadata.formats.image/jpeg2000rootpackage/exifpackage/
---
## Jpeg2000RootPackage.ExifPackage property

EXIF मेटाडेटा पैकेज प्राप्त या सेट करता है।

```csharp
public ExifPackage ExifPackage { get; set; }
```

### संपत्ति मूल्य

EXIF मेटाडेटा पैकेज.

### टिप्पणियों

**और अधिक जानें**

* [EXIF मेटाडेटा के साथ काम करना](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### उदाहरण

यह कोड नमूना प्रदर्शित करता है कि बुनियादी EXIF मेटाडेटा गुणों को कैसे निकाला जाए।

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

### यह सभी देखें

* class [ExifPackage](../../../groupdocs.metadata.standards.exif/exifpackage)
* class [Jpeg2000RootPackage](../../jpeg2000rootpackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Image](../../jpeg2000rootpackage)
* सभा [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->