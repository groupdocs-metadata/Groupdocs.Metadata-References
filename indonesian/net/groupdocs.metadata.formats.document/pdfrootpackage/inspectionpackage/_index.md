---
title: InspectionPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mendapat paket metadata yang berisi hasil pemeriksaan untuk dokumen tersebut. Paket tersebut berisi informasi tentang bagian dokumen yang dapat dianggap sebagai metadata dalam beberapa kasus.
type: docs
weight: 30
url: /id/net/groupdocs.metadata.formats.document/pdfrootpackage/inspectionpackage/
---
## PdfRootPackage.InspectionPackage property

Mendapat paket metadata yang berisi hasil pemeriksaan untuk dokumen tersebut. Paket tersebut berisi informasi tentang bagian dokumen yang dapat dianggap sebagai metadata dalam beberapa kasus.

```csharp
public PdfInspectionPackage InspectionPackage { get; }
```

### Nilai properti

Paket metadata berisi hasil pemeriksaan dokumen.

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata dalam dokumen PDF](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)

### Contoh

Contoh ini menunjukkan cara memeriksa dokumen PDF.

```csharp
using (Metadata metadata = new Metadata(Constants.SignedPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    if (root.InspectionPackage.Annotations != null)
    {
        foreach (var annotation in root.InspectionPackage.Annotations)
        {
            Console.WriteLine(annotation.Name);
            Console.WriteLine(annotation.Text);
            Console.WriteLine(annotation.PageNumber);
        }
    }

    if (root.InspectionPackage.Attachments != null)
    {
        foreach (var attachment in root.InspectionPackage.Attachments)
        {
            Console.WriteLine(attachment.Name);
            Console.WriteLine(attachment.MimeType);
            Console.WriteLine(attachment.Description);
        }
    }

    if (root.InspectionPackage.Bookmarks != null)
    {
        foreach (var bookmark in root.InspectionPackage.Bookmarks)
        {
            Console.WriteLine(bookmark.Title);
        }
    }

    if (root.InspectionPackage.DigitalSignatures != null)
    {
        foreach (var signature in root.InspectionPackage.DigitalSignatures)
        {
            Console.WriteLine(signature.CertificateSubject);
            Console.WriteLine(signature.Comments);
            Console.WriteLine(signature.SignTime);

            // ...
        }
    }

    if (root.InspectionPackage.Fields != null)
    {
        foreach (var field in root.InspectionPackage.Fields)
        {
            Console.WriteLine(field.Name);
            Console.WriteLine(field.Value);

            // ...
        }
    }
}
```

### Lihat juga

* class [PdfInspectionPackage](../../pdfinspectionpackage)
* class [PdfRootPackage](../../pdfrootpackage)
* ruang nama [GroupDocs.Metadata.Formats.Document](../../pdfrootpackage)
* perakitan [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->