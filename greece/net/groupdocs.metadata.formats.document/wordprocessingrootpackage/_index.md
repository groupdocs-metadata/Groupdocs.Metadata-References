---
title: WordProcessingRootPackage
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει το ριζικό πακέτο που επιτρέπει την εργασία με μεταδεδομένα σε ένα έγγραφο επεξεργασίας κειμένου.
type: docs
weight: 1310
url: /el/net/groupdocs.metadata.formats.document/wordprocessingrootpackage/
---
## WordProcessingRootPackage class

Αντιπροσωπεύει το ριζικό πακέτο που επιτρέπει την εργασία με μεταδεδομένα σε ένα έγγραφο επεξεργασίας κειμένου.

```csharp
public class WordProcessingRootPackage : DocumentRootPackage<WordProcessingPackage>, IDublinCore
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| virtual [DocumentProperties](../../groupdocs.metadata.formats.document/documentrootpackage-1/documentproperties) { get; } | Λαμβάνει τις ιδιότητες εγγενών μεταδεδομένων που παρουσιάζονται στο έγγραφο. |
| [DocumentStatistics](../../groupdocs.metadata.formats.document/wordprocessingrootpackage/documentstatistics) { get; } | Λαμβάνει το πακέτο στατιστικών εγγράφων. |
| [DublinCorePackage](../../groupdocs.metadata.formats.document/wordprocessingrootpackage/dublincorepackage) { get; } | Λαμβάνει το πακέτο μεταδεδομένων Dublin Core που εξάγεται από το έγγραφο. |
| [FileType](../../groupdocs.metadata.formats.document/wordprocessingrootpackage/filetype) { get; } | Λαμβάνει το πακέτο μεταδεδομένων τύπου αρχείου. (2 properties) |
| [InspectionPackage](../../groupdocs.metadata.formats.document/wordprocessingrootpackage/inspectionpackage) { get; } | Λαμβάνει ένα πακέτο μεταδεδομένων που περιέχει αποτελέσματα επιθεώρησης για το έγγραφο. Το πακέτο περιέχει πληροφορίες σχετικά με μέρη εγγράφου που μπορούν να θεωρηθούν ως μεταδεδομένα σε ορισμένες περιπτώσεις. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |

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
| [UpdateDocumentStatistics](../../groupdocs.metadata.formats.document/wordprocessingrootpackage/updatedocumentstatistics)() | Υπολογίζει εκ νέου τον αριθμό των σελίδων, παραγράφων, λέξεων, γραμμών, χαρακτήρων στο έγγραφο και ενημερώνει τα κατάλληλα πακέτα μεταδεδομένων. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ενημερώνει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Εργασία με μεταδεδομένα σε έγγραφα WordProcessing](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### Παραδείγματα

Αυτό το δείγμα κώδικα δείχνει πώς να διαβάζετε τις ενσωματωμένες ιδιότητες μεταδεδομένων ενός εγγράφου WordProcessing.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDocx))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    Console.WriteLine(root.DocumentProperties.Author);
    Console.WriteLine(root.DocumentProperties.CreatedTime);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Category);
    Console.WriteLine(root.DocumentProperties.Keywords);

    //... 
}
```

### Δείτε επίσης

* class [DocumentRootPackage&lt;TPackage&gt;](../documentrootpackage-1)
* class [WordProcessingPackage](../wordprocessingpackage)
* interface [IDublinCore](../../groupdocs.metadata.standards.dublincore/idublincore)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
