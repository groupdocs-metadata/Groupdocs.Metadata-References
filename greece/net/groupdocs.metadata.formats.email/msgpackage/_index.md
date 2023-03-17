---
title: MsgPackage
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει μεταδεδομένα μηνύματος MSG.
type: docs
weight: 1400
url: /el/net/groupdocs.metadata.formats.email/msgpackage/
---
## MsgPackage class

Αντιπροσωπεύει μεταδεδομένα μηνύματος MSG.

```csharp
public class MsgPackage : EmailPackage
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AttachedFileNames](../../groupdocs.metadata.formats.email/emailpackage/attachedfilenames) { get; } | Λαμβάνει έναν πίνακα με τα ονόματα των συνημμένων αρχείων. |
| [BlindCarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/blindcarboncopyrecipients) { get; set; } | Λαμβάνει ή ορίζει τη σειρά των παραληπτών BCC (blind carbon copy) του μηνύματος email. |
| [Body](../../groupdocs.metadata.formats.email/msgpackage/body) { get; } | Λαμβάνει το κείμενο του μηνύματος email. |
| [CarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/carboncopyrecipients) { get; set; } | Λαμβάνει ή ορίζει τη σειρά των παραληπτών CC (αντίγραφο άνθρακα) του μηνύματος email. |
| [Categories](../../groupdocs.metadata.formats.email/msgpackage/categories) { get; } | Λαμβάνει τον πίνακα κατηγοριών ή λέξεων-κλειδιών. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [DeliveryTime](../../groupdocs.metadata.formats.email/msgpackage/deliverytime) { get; } | Λαμβάνει την ημερομηνία και την ώρα παράδοσης του μηνύματος. |
| [Headers](../../groupdocs.metadata.formats.email/emailpackage/headers) { get; } | Λαμβάνει ένα πακέτο μεταδεδομένων που περιέχει τις κεφαλίδες email. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [Recipients](../../groupdocs.metadata.formats.email/emailpackage/recipients) { get; set; } | Λαμβάνει ή ορίζει τη σειρά των παραληπτών email. |
| [Sender](../../groupdocs.metadata.formats.email/emailpackage/sender) { get; } | Λαμβάνει τη διεύθυνση email του αποστολέα. |
| [Subject](../../groupdocs.metadata.formats.email/emailpackage/subject) { get; set; } | Λαμβάνει ή ορίζει το θέμα του email. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Προσθέτει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Καθορίζει εάν το πακέτο περιέχει μια ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Βρίσκει τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η αναζήτηση είναι αναδρομική, επομένως επηρεάζει όλα τα ένθετα πακέτα επίσης. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Επιστρέφει έναν απαριθμητή που επαναλαμβάνει τη συλλογή. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Καταργεί τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Αφαιρεί τις ιδιότητες μεταδεδομένων με δυνατότητα εγγραφής από το πακέτο. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ορίζει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. Αυτή η μέθοδος είναι ένας συνδυασμός[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) και[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Εάν μια υπάρχουσα ιδιότητα ικανοποιεί το κατηγόρημα, η τιμή της ενημερώνεται. Εάν λείπει μια γνωστή ιδιότητα στο πακέτο που ικανοποιεί το κατηγόρημα, προστίθεται στο πακέτο. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ενημερώνει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Εργασία με αποθηκευμένα email](https://docs.groupdocs.com/display/metadatanet/Working+with+saved+Emails)

### Δείτε επίσης

* class [EmailPackage](../emailpackage)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.Email](../../groupdocs.metadata.formats.email)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
