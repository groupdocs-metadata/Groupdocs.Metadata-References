---
title: ZipRootPackage
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει το ριζικό πακέτο που επιτρέπει την εργασία με μεταδεδομένα σε ένα αρχείο ZIP.
type: docs
weight: 370
url: /el/net/groupdocs.metadata.formats.archive/ziprootpackage/
---
## ZipRootPackage class

Αντιπροσωπεύει το ριζικό πακέτο που επιτρέπει την εργασία με μεταδεδομένα σε ένα αρχείο ZIP.

```csharp
public class ZipRootPackage : RootMetadataPackage
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Λαμβάνει το πακέτο μεταδεδομένων τύπου αρχείου. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [ZipPackage](../../groupdocs.metadata.formats.archive/ziprootpackage/zippackage) { get; } | Λαμβάνει το πακέτο μεταδεδομένων ZIP. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Προσθέτει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Καθορίζει εάν το πακέτο περιέχει μια ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Βρίσκει τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η αναζήτηση είναι αναδρομική, επομένως επηρεάζει όλα τα ένθετα πακέτα επίσης. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Επιστρέφει έναν απαριθμητή που επαναλαμβάνει τη συλλογή. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Καταργεί τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Αφαιρεί τις ιδιότητες μεταδεδομένων με δυνατότητα εγγραφής από το πακέτο. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ορίζει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. Αυτή η μέθοδος είναι ένας συνδυασμός[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) και[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Εάν μια υπάρχουσα ιδιότητα ικανοποιεί το κατηγόρημα, η τιμή της ενημερώνεται. Εάν λείπει μια γνωστή ιδιότητα στο πακέτο που ικανοποιεί το κατηγόρημα, προστίθεται στο πακέτο. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ενημερώνει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Εργασία με αρχεία ZIP](https://docs.groupdocs.com/display/metadatanet/Working+with+ZIP+archives)

### Παραδείγματα

Το ακόλουθο απόσπασμα κώδικα δείχνει πώς να λαμβάνετε μεταδεδομένα από ένα αρχείο ZIP.

```csharp
Encoding encoding = Encoding.GetEncoding(866);

using (Metadata metadata = new Metadata(Constants.InputZip))
{
    var root = metadata.GetRootPackage<ZipRootPackage>();

    Console.WriteLine(root.ZipPackage.Comment);
    Console.WriteLine(root.ZipPackage.TotalEntries);

    foreach (var file in root.ZipPackage.Files)
    {
        Console.WriteLine(file.Name);
        Console.WriteLine(file.CompressedSize);
        Console.WriteLine(file.CompressionMethod);
        Console.WriteLine(file.Flags);
        Console.WriteLine(file.ModificationDateTime);
        Console.WriteLine(file.UncompressedSize);

        // Χρησιμοποιήστε μια συγκεκριμένη κωδικοποίηση για τα ονόματα των αρχείων
        Console.WriteLine(encoding.GetString(file.RawName));
    }
}
```

### Δείτε επίσης

* class [RootMetadataPackage](../../groupdocs.metadata.common/rootmetadatapackage)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.Archive](../../groupdocs.metadata.formats.archive)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
