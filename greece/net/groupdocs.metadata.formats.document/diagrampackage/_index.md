---
title: DiagramPackage
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει ένα εγγενές πακέτο μεταδεδομένων σε μορφή διαγράμματος.
type: docs
weight: 890
url: /el/net/groupdocs.metadata.formats.document/diagrampackage/
---
## DiagramPackage class

Αντιπροσωπεύει ένα εγγενές πακέτο μεταδεδομένων σε μορφή διαγράμματος.

```csharp
public class DiagramPackage : DocumentPackage
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AlternateNames](../../groupdocs.metadata.formats.document/diagrampackage/alternatenames) { get; set; } | Λαμβάνει ή ορίζει τα εναλλακτικά ονόματα για το έγγραφο. Μπορεί να ενημερωθεί μόνο σε μορφές VDX και VSX. |
| [BuildNumberCreated](../../groupdocs.metadata.formats.document/diagrampackage/buildnumbercreated) { get; } | Λαμβάνει τον πλήρη αριθμό έκδοσης του στιγμιότυπου που χρησιμοποιήθηκε για τη δημιουργία του εγγράφου. |
| [BuildNumberEdited](../../groupdocs.metadata.formats.document/diagrampackage/buildnumberedited) { get; } | Λαμβάνει τον αριθμό έκδοσης του στιγμιότυπου που χρησιμοποιήθηκε τελευταία για την επεξεργασία του εγγράφου. |
| [Category](../../groupdocs.metadata.formats.document/diagrampackage/category) { get; set; } | Λαμβάνει ή ορίζει το περιγραφικό κείμενο για τον τύπο του σχεδίου, όπως διάγραμμα ροής ή διάταξη γραφείου. Αυτό το κείμενο μπορεί επίσης να εισαχθεί στη διεπαφή χρήστη του Microsoft Visio στο πλαίσιο Κατηγορία στο πλαίσιο διαλόγου Ιδιότητες. |
| [Company](../../groupdocs.metadata.formats.document/diagrampackage/company) { get; set; } | Λαμβάνει ή ορίζει τις πληροφορίες που έχουν εισαχθεί από τον χρήστη που προσδιορίζουν την εταιρεία που δημιουργεί το σχέδιο ή την εταιρεία για την οποία δημιουργείται το σχέδιο. Το μέγιστο μήκος είναι 63 χαρακτήρες. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [Creator](../../groupdocs.metadata.formats.document/diagrampackage/creator) { get; set; } | Λαμβάνει ή ορίζει το άτομο που δημιούργησε ή ενημέρωσε την τελευταία φορά το αρχείο. Το μέγιστο μήκος είναι 63 χαρακτήρες.. |
| [Description](../../groupdocs.metadata.formats.document/diagrampackage/description) { get; set; } | Λαμβάνει ή ορίζει μια περιγραφική συμβολοσειρά κειμένου για το έγγραφο. Χρησιμοποιήστε αυτό το στοιχείο για να αποθηκεύσετε σημαντικές πληροφορίες σχετικά με το έγγραφο, όπως ο σκοπός του, οι πρόσφατες αλλαγές ή οι εκκρεμείς αλλαγές. Το μέγιστο είναι 191 χαρακτήρες. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/diagrampackage/hyperlinkbase) { get; set; } | Λαμβάνει ή ορίζει τη διαδρομή που θα χρησιμοποιηθεί για σχετικούς υπερσυνδέσμους (υπερσύνδεσμοι για τους οποίους η θέση του συνδεδεμένου αρχείου περιγράφεται σε σχέση με το διάγραμμα του Microsoft Visio). σε αυτό το στοιχείο. Το μέγιστο μήκος είναι 256 χαρακτήρες. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [Keywords](../../groupdocs.metadata.formats.document/diagrampackage/keywords) { get; set; } | Λαμβάνει ή ορίζει μια συμβολοσειρά κειμένου που προσδιορίζει θέματα ή άλλες σημαντικές πληροφορίες σχετικά με το αρχείο, όπως όνομα έργου, όνομα πελάτη ή αριθμός έκδοσης. Το μέγιστο μήκος συμβολοσειράς είναι 63 χαρακτήρες. |
| [Language](../../groupdocs.metadata.formats.document/diagrampackage/language) { get; set; } | Λαμβάνει ή ορίζει τη γλώσσα του εγγράφου. Μπορεί να ενημερωθεί μόνο σε μορφές VSD και VSDX. |
| [Manager](../../groupdocs.metadata.formats.document/diagrampackage/manager) { get; set; } | Λαμβάνει ή ορίζει μια συμβολοσειρά κειμένου που εισάγει ο χρήστης που προσδιορίζει τον υπεύθυνο του έργου ή του τμήματος. Το μέγιστο μήκος είναι 63 χαρακτήρες. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [PreviewPicture](../../groupdocs.metadata.formats.document/diagrampackage/previewpicture) { get; set; } | Λαμβάνει ή ορίζει την εικόνα προεπισκόπησης. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [Subject](../../groupdocs.metadata.formats.document/diagrampackage/subject) { get; set; } | Λαμβάνει ή ορίζει μια συμβολοσειρά κειμένου που ορίζεται από το χρήστη που περιγράφει τα περιεχόμενα του εγγράφου. Το μέγιστο μήκος είναι 63 χαρακτήρες. |
| [Template](../../groupdocs.metadata.formats.document/diagrampackage/template) { get; set; } | Λαμβάνει ή ορίζει μια τιμή συμβολοσειράς που καθορίζει το όνομα αρχείου του προτύπου από το οποίο δημιουργήθηκε το έγγραφο. |
| [TimeCreated](../../groupdocs.metadata.formats.document/diagrampackage/timecreated) { get; set; } | Λαμβάνει ή ορίζει μια τιμή ημερομηνίας και ώρας που υποδεικνύει πότε δημιουργήθηκε το έγγραφο. |
| [TimeEdited](../../groupdocs.metadata.formats.document/diagrampackage/timeedited) { get; } | Λαμβάνει μια τιμή ημερομηνίας και ώρας που υποδεικνύει πότε έγινε η τελευταία επεξεργασία του εγγράφου. |
| [TimePrinted](../../groupdocs.metadata.formats.document/diagrampackage/timeprinted) { get; } | Λαμβάνει μια τιμή ημερομηνίας και ώρας που υποδεικνύει την τελευταία φορά που εκτυπώθηκε το έγγραφο. |
| [TimeSaved](../../groupdocs.metadata.formats.document/diagrampackage/timesaved) { get; } | Λαμβάνει μια τιμή ημερομηνίας και ώρας που υποδεικνύει πότε αποθηκεύτηκε το έγγραφο για τελευταία φορά. |
| [Title](../../groupdocs.metadata.formats.document/diagrampackage/title) { get; set; } | Λαμβάνει ή ορίζει μια συμβολοσειρά κειμένου που ορίζεται από το χρήστη που χρησιμεύει ως περιγραφικός τίτλος για το έγγραφο. Το μέγιστο μήκος είναι 63 χαρακτήρες. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Προσθέτει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | Καταργεί όλες τις εγγράψιμες ιδιότητες μεταδεδομένων από το πακέτο. |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | Καταργεί όλες τις ενσωματωμένες ιδιότητες μεταδεδομένων. |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | Καταργεί όλες τις προσαρμοσμένες ιδιότητες μεταδεδομένων. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Καθορίζει εάν το πακέτο περιέχει μια ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Βρίσκει τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η αναζήτηση είναι αναδρομική, επομένως επηρεάζει όλα τα ένθετα πακέτα επίσης. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Επιστρέφει έναν απαριθμητή που επαναλαμβάνει τη συλλογή. |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | Καταργεί μια εγγράψιμη ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Καταργεί τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Αφαιρεί τις ιδιότητες μεταδεδομένων με δυνατότητα εγγραφής από το πακέτο. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set)(string, bool) | Προσθέτει ή αντικαθιστά την ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_2)(string, DateTime) | Προσθέτει ή αντικαθιστά την ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_1)(string, double) | Προσθέτει ή αντικαθιστά την ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_3)(string, string) | Προσθέτει ή αντικαθιστά την ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ορίζει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. Αυτή η μέθοδος είναι ένας συνδυασμός[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) και[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Εάν μια υπάρχουσα ιδιότητα ικανοποιεί το κατηγόρημα, η τιμή της ενημερώνεται. Εάν λείπει μια γνωστή ιδιότητα στο πακέτο που ικανοποιεί το κατηγόρημα, προστίθεται στο πακέτο. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ενημερώνει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Εργασία με μεταδεδομένα σε διαγράμματα](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### Παραδείγματα

Αυτό το δείγμα κώδικα δείχνει πώς να εξαγάγετε ενσωματωμένες ιδιότητες μεταδεδομένων από ένα διάγραμμα.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVsdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    Console.WriteLine(root.DocumentProperties.Creator);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.Language);
    Console.WriteLine(root.DocumentProperties.TimeCreated);
    Console.WriteLine(root.DocumentProperties.Category);

    //... 
}
```

### Δείτε επίσης

* class [DocumentPackage](../documentpackage)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
