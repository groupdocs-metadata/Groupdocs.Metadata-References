---
title: ExifPackage
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει ένα πακέτο μεταδεδομένων EXIF Exchangeable Image File Format.
type: docs
weight: 2790
url: /el/net/groupdocs.metadata.standards.exif/exifpackage/
---
## ExifPackage class

Αντιπροσωπεύει ένα πακέτο μεταδεδομένων EXIF (Exchangeable Image File Format).

```csharp
public class ExifPackage : ExifDictionaryBasePackage
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [ExifPackage](exifpackage)() | Αρχικοποιεί μια νέα παρουσία του[`ExifPackage`](../exifpackage) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Artist](../../groupdocs.metadata.standards.exif/exifpackage/artist) { get; set; } | Λαμβάνει ή ορίζει το όνομα του κατόχου της κάμερας, του φωτογράφου ή του δημιουργού εικόνας. |
| [Copyright](../../groupdocs.metadata.standards.exif/exifpackage/copyright) { get; set; } | Λαμβάνει ή ορίζει τη σημείωση πνευματικών δικαιωμάτων. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [DateTime](../../groupdocs.metadata.standards.exif/exifpackage/datetime) { get; set; } | Λαμβάνει ή ορίζει την ημερομηνία και την ώρα δημιουργίας εικόνας. Στο πρότυπο EXIF, είναι η ημερομηνία και η ώρα που άλλαξε το αρχείο. |
| [ExifIfdPackage](../../groupdocs.metadata.standards.exif/exifpackage/exififdpackage) { get; } | Λαμβάνει τα δεδομένα EXIF IFD. |
| [GpsPackage](../../groupdocs.metadata.standards.exif/exifpackage/gpspackage) { get; } | Λαμβάνει τα δεδομένα GPS. |
| [ImageDescription](../../groupdocs.metadata.standards.exif/exifpackage/imagedescription) { get; set; } | Λαμβάνει ή ορίζει μια συμβολοσειρά χαρακτήρων που δίνει τον τίτλο της εικόνας. Μπορεί να είναι ένα σχόλιο όπως "1988 εταιρικό πικνίκ" ή κάτι παρόμοιο. |
| [ImageLength](../../groupdocs.metadata.standards.exif/exifpackage/imagelength) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό των σειρών δεδομένων εικόνας. |
| [ImageWidth](../../groupdocs.metadata.standards.exif/exifpackage/imagewidth) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό των στηλών δεδομένων εικόνας, ίσο με τον αριθμό των pixel ανά σειρά. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Λαμβάνει την ετικέτα TIFF με το καθορισμένο αναγνωριστικό. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [Make](../../groupdocs.metadata.standards.exif/exifpackage/make) { get; set; } | Παίρνει ή ρυθμίζει τον κατασκευαστή της συσκευής εγγραφής. Αυτός είναι ο κατασκευαστής του DSC, του σαρωτή, του ψηφιοποιητή βίντεο ή άλλου εξοπλισμού που δημιούργησε την εικόνα. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [Model](../../groupdocs.metadata.standards.exif/exifpackage/model) { get; set; } | Λαμβάνει ή ορίζει το όνομα μοντέλου ή τον αριθμό μοντέλου του εξοπλισμού. Αυτό είναι το όνομα μοντέλου ή ο αριθμός του DSC, του σαρωτή, του ψηφιοποιητή βίντεο ή άλλου εξοπλισμού που δημιούργησε την εικόνα. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [Software](../../groupdocs.metadata.standards.exif/exifpackage/software) { get; set; } | Λαμβάνει ή ορίζει το όνομα και την έκδοση του λογισμικού ή του υλικολογισμικού της κάμερας ή της συσκευής εισαγωγής εικόνας που χρησιμοποιείται για τη δημιουργία της εικόνας. |
| [Thumbnail](../../groupdocs.metadata.standards.exif/exifpackage/thumbnail) { get; } | Λαμβάνει τη μικρογραφία της εικόνας που αναπαρίσταται ως μια σειρά από byte. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Προσθέτει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Αφαιρεί όλες τις ετικέτες TIFF που είναι αποθηκευμένες στη συσκευασία. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Καθορίζει εάν το πακέτο περιέχει μια ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Βρίσκει τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η αναζήτηση είναι αναδρομική, επομένως επηρεάζει όλα τα ένθετα πακέτα επίσης. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Επιστρέφει έναν απαριθμητή που επαναλαμβάνει τη συλλογή. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Καταργεί την ιδιότητα με το καθορισμένο αναγνωριστικό. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Καταργεί τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Αφαιρεί τις ιδιότητες μεταδεδομένων με δυνατότητα εγγραφής από το πακέτο. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Προσθέτει ή αντικαθιστά την καθορισμένη ετικέτα. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ορίζει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. Αυτή η μέθοδος είναι ένας συνδυασμός[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) και[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Εάν μια υπάρχουσα ιδιότητα ικανοποιεί το κατηγόρημα, η τιμή της ενημερώνεται. Εάν λείπει μια γνωστή ιδιότητα στο πακέτο που ικανοποιεί το κατηγόρημα, προστίθεται στο πακέτο. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Δημιουργεί μια λίστα από το πακέτο. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ενημερώνει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Εργασία με μεταδεδομένα EXIF](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Παραδείγματα

Αυτό το δείγμα κώδικα δείχνει πώς να ενημερώσετε κοινές ιδιότητες EXIF.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        // Ορίστε το πακέτο EXIF εάν λείπει
        if (root.ExifPackage == null)
        {
            root.ExifPackage = new ExifPackage();
        }

        root.ExifPackage.Copyright = "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.";
        root.ExifPackage.ImageDescription = "test image";
        root.ExifPackage.Software = "GroupDocs.Metadata";

        //...

        root.ExifPackage.ExifIfdPackage.BodySerialNumber = "test";
        root.ExifPackage.ExifIfdPackage.CameraOwnerName = "GroupDocs";
        root.ExifPackage.ExifIfdPackage.UserComment = "test comment";

        //...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Δείτε επίσης

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* χώρος ονομάτων [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
