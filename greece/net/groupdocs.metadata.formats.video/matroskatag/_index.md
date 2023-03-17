---
title: MatroskaTag
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Το Αντιπροσωπεύει μεταδεδομένα που περιγράφουν Κομμάτια Εκδόσεις Κεφάλαια Συνημμένα ή το Τμήμα ως σύνολο σε ένα βίντεο Matroska.
type: docs
weight: 2530
url: /el/net/groupdocs.metadata.formats.video/matroskatag/
---
## MatroskaTag class

Το Αντιπροσωπεύει μεταδεδομένα που περιγράφουν Κομμάτια, Εκδόσεις, Κεφάλαια, Συνημμένα ή το Τμήμα ως σύνολο σε ένα βίντεο Matroska.

```csharp
public class MatroskaTag : MatroskaBasePackage
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [SimpleTags](../../groupdocs.metadata.formats.video/matroskatag/simpletags) { get; } | Λαμβάνει τις γενικές πληροφορίες σχετικά με τον στόχο. |
| [TagTrackUid](../../groupdocs.metadata.formats.video/matroskatag/tagtrackuid) { get; } | Λαμβάνει ένα μοναδικό αναγνωριστικό για τον προσδιορισμό των κομματιών στα οποία ανήκουν οι ετικέτες. Εάν η τιμή είναι 0 σε αυτό το επίπεδο, οι ετικέτες ισχύουν για όλα τα κομμάτια στο Τμήμα. |
| [TargetType](../../groupdocs.metadata.formats.video/matroskatag/targettype) { get; } | Λαμβάνει μια συμβολοσειρά πληροφοριών που μπορεί να χρησιμοποιηθεί για την εμφάνιση του λογικού επιπέδου του στόχου. Όπως "ALBUM", "TRACK", "MOVIE", "CHAPTER" κ.λπ. |
| [TargetTypeValue](../../groupdocs.metadata.formats.video/matroskatag/targettypevalue) { get; } | Παίρνει τον αριθμό που υποδεικνύει το λογικό επίπεδο του στόχου. |

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

* [Εργασία με μεταδεδομένα σε αρχεία Matroska (MKV).](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### Δείτε επίσης

* class [MatroskaBasePackage](../matroskabasepackage)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
