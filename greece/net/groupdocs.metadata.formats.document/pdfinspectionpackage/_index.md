---
title: PdfInspectionPackage
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Περιέχει πληροφορίες σχετικά με μέρη εγγράφου PDF που μπορούν να θεωρηθούν ως μεταδεδομένα σε ορισμένες περιπτώσεις.
type: docs
weight: 1020
url: /el/net/groupdocs.metadata.formats.document/pdfinspectionpackage/
---
## PdfInspectionPackage class

Περιέχει πληροφορίες σχετικά με μέρη εγγράφου PDF που μπορούν να θεωρηθούν ως μεταδεδομένα σε ορισμένες περιπτώσεις.

```csharp
public sealed class PdfInspectionPackage : CustomPackage
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Annotations](../../groupdocs.metadata.formats.document/pdfinspectionpackage/annotations) { get; } | Λαμβάνει μια σειρά από σχολιασμούς. |
| [Attachments](../../groupdocs.metadata.formats.document/pdfinspectionpackage/attachments) { get; } | Λαμβάνει μια σειρά από τα συνημμένα. |
| [Bookmarks](../../groupdocs.metadata.formats.document/pdfinspectionpackage/bookmarks) { get; } | Λαμβάνει μια σειρά από σελιδοδείκτες. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/pdfinspectionpackage/digitalsignatures) { get; } | Λαμβάνει μια σειρά από ψηφιακές υπογραφές. |
| [Fields](../../groupdocs.metadata.formats.document/pdfinspectionpackage/fields) { get; } | Παίρνει έναν πίνακα με τα πεδία φόρμας. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Προσθέτει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [ClearAnnotations](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearannotations)() | Αφαιρεί όλους τους σχολιασμούς που εντοπίστηκαν από το έγγραφο. |
| [ClearAttachments](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearattachments)() | Καταργεί όλα τα συνημμένα που εντοπίστηκαν από το έγγραφο. |
| [ClearBookmarks](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearbookmarks)() | Αφαιρεί όλους τους σελιδοδείκτες που εντοπίστηκαν από το έγγραφο. |
| [ClearDigitalSignatures](../../groupdocs.metadata.formats.document/pdfinspectionpackage/cleardigitalsignatures)() | Αφαιρεί όλες τις ψηφιακές υπογραφές που έχουν εντοπιστεί από το έγγραφο. |
| [ClearFields](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearfields)() | Καταργεί όλα τα πεδία φόρμας που εντοπίστηκαν από το έγγραφο. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Καθορίζει εάν το πακέτο περιέχει μια ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Βρίσκει τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η αναζήτηση είναι αναδρομική, επομένως επηρεάζει όλα τα ένθετα πακέτα επίσης. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Επιστρέφει έναν απαριθμητή που επαναλαμβάνει τη συλλογή. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/pdfinspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Καταργεί τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. |
| override [Sanitize](../../groupdocs.metadata.formats.document/pdfinspectionpackage/sanitize)() | Αφαιρεί τις ιδιότητες μεταδεδομένων με δυνατότητα εγγραφής από το πακέτο. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ορίζει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. Αυτή η μέθοδος είναι ένας συνδυασμός[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) και[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Εάν μια υπάρχουσα ιδιότητα ικανοποιεί το κατηγόρημα, η τιμή της ενημερώνεται. Εάν λείπει μια γνωστή ιδιότητα στο πακέτο που ικανοποιεί το κατηγόρημα, προστίθεται στο πακέτο. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ενημερώνει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Εργασία με μεταδεδομένα σε έγγραφα PDF](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)

### Παραδείγματα

Αυτό το δείγμα κώδικα δείχνει πώς να αφαιρέσετε τις ιδιότητες επιθεώρησης σε ένα έγγραφο PDF.

```csharp
using (Metadata metadata = new Metadata(Constants.SignedPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    root.InspectionPackage.ClearAnnotations();
    root.InspectionPackage.ClearAttachments();
    root.InspectionPackage.ClearFields();
    root.InspectionPackage.ClearBookmarks();
    root.InspectionPackage.ClearDigitalSignatures();

    metadata.Save(Constants.OutputPdf);
}
```

### Δείτε επίσης

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
