---
title: ExifPackage
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Λαμβάνει ή ορίζει το πακέτο μεταδεδομένων EXIF που σχετίζεται με το αρχείο.
type: docs
weight: 10
url: /el/net/groupdocs.metadata.standards.exif/iexif/exifpackage/
---
## IExif.ExifPackage property

Λαμβάνει ή ορίζει το πακέτο μεταδεδομένων EXIF που σχετίζεται με το αρχείο.

```csharp
public ExifPackage ExifPackage { get; set; }
```

### Αξία περιουσίας

Το πακέτο μεταδεδομένων EXIF που σχετίζεται με το αρχείο.

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Εργασία με μεταδεδομένα EXIF](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Παραδείγματα

Αυτό το δείγμα κώδικα δείχνει πώς να αφαιρέσετε μεταδεδομένα EXIF από ένα αρχείο.

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithExif))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        root.ExifPackage = null;

        metadata.Save(Constants.OutputJpeg);
     }
}
```

### Δείτε επίσης

* class [ExifPackage](../../exifpackage)
* interface [IExif](../../iexif)
* χώρος ονομάτων [GroupDocs.Metadata.Standards.Exif](../../iexif)
* συνέλευση [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->