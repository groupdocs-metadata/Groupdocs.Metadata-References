---
title: InspectionPackage
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Λαμβάνει ένα πακέτο μεταδεδομένων που περιέχει αποτελέσματα επιθεώρησης για το έγγραφο. Το πακέτο περιέχει πληροφορίες σχετικά με μέρη εγγράφου που μπορούν να θεωρηθούν ως μεταδεδομένα σε ορισμένες περιπτώσεις.
type: docs
weight: 30
url: /el/net/groupdocs.metadata.formats.document/presentationrootpackage/inspectionpackage/
---
## PresentationRootPackage.InspectionPackage property

Λαμβάνει ένα πακέτο μεταδεδομένων που περιέχει αποτελέσματα επιθεώρησης για το έγγραφο. Το πακέτο περιέχει πληροφορίες σχετικά με μέρη εγγράφου που μπορούν να θεωρηθούν ως μεταδεδομένα σε ορισμένες περιπτώσεις.

```csharp
public PresentationInspectionPackage InspectionPackage { get; }
```

### Αξία περιουσίας

Ένα πακέτο μεταδεδομένων που περιέχει αποτελέσματα επιθεώρησης για το έγγραφο.

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Εργασία με μεταδεδομένα σε Παρουσιάσεις](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Presentations)

### Παραδείγματα

Αυτό το δείγμα κώδικα δείχνει πώς να επιθεωρήσετε μια παρουσίαση.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPpt))
{
     var root = metadata.GetRootPackage<PresentationRootPackage>();

     if (root.InspectionPackage.Comments != null)
     {
         foreach (var comment in root.InspectionPackage.Comments)
         {
             Console.WriteLine(comment.Author);
             Console.WriteLine(comment.Text);
             Console.WriteLine(comment.CreatedTime);
             Console.WriteLine(comment.SlideNumber);
         }
     }

     if (root.InspectionPackage.HiddenSlides != null)
     {
         foreach (var slide in root.InspectionPackage.HiddenSlides)
         {
             Console.WriteLine(slide.Name);
             Console.WriteLine(slide.Number);
             Console.WriteLine(slide.SlideId);
         }
     }
}
```

### Δείτε επίσης

* class [PresentationInspectionPackage](../../presentationinspectionpackage)
* class [PresentationRootPackage](../../presentationrootpackage)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.Document](../../presentationrootpackage)
* συνέλευση [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
