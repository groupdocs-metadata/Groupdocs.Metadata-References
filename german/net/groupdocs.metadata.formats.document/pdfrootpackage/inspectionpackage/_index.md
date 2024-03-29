---
title: InspectionPackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Ruft ein Metadatenpaket ab das Inspektionsergebnisse für das Dokument enthält. Das Paket enthält Informationen zu Dokumententeilen die in einigen Fällen als Metadaten betrachtet werden können.
type: docs
weight: 30
url: /de/net/groupdocs.metadata.formats.document/pdfrootpackage/inspectionpackage/
---
## PdfRootPackage.InspectionPackage property

Ruft ein Metadatenpaket ab, das Inspektionsergebnisse für das Dokument enthält. Das Paket enthält Informationen zu Dokumententeilen, die in einigen Fällen als Metadaten betrachtet werden können.

```csharp
public PdfInspectionPackage InspectionPackage { get; }
```

### Eigentumswert

Ein Metadatenpaket mit Prüfergebnissen für das Dokument.

### Bemerkungen

**Erfahren Sie mehr**

* [Arbeiten mit Metadaten in PDF-Dokumenten](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)

### Beispiele

Dieses Beispiel zeigt, wie ein PDF-Dokument geprüft wird.

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

### Siehe auch

* class [PdfInspectionPackage](../../pdfinspectionpackage)
* class [PdfRootPackage](../../pdfrootpackage)
* namensraum [GroupDocs.Metadata.Formats.Document](../../pdfrootpackage)
* Montage [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
