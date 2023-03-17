---
title: MatroskaSegment
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει ένα στοιχείο SEGMENTINFO που περιέχει γενικές πληροφορίες για το SEGMENT σε ένα βίντεο Matroska.
type: docs
weight: 2490
url: /el/net/groupdocs.metadata.formats.video/matroskasegment/
---
## MatroskaSegment class

Αντιπροσωπεύει ένα στοιχείο SEGMENTINFO που περιέχει γενικές πληροφορίες για το SEGMENT σε ένα βίντεο Matroska.

```csharp
public class MatroskaSegment : MatroskaBasePackage
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [DateUtc](../../groupdocs.metadata.formats.video/matroskasegment/dateutc) { get; } | Λαμβάνει την ημερομηνία και την ώρα που δημιουργήθηκε το Τμήμα από την εφαρμογή muxing ή τη βιβλιοθήκη. |
| [Duration](../../groupdocs.metadata.formats.video/matroskasegment/duration) { get; } | Λαμβάνει τη διάρκεια του SEGMENT. Δείτε[`TimecodeScale`](./timecodescale) για περισσότερες πληροφορίες. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [MuxingApp](../../groupdocs.metadata.formats.video/matroskasegment/muxingapp) { get; } | Λαμβάνει το πλήρες όνομα της εφαρμογής ή της βιβλιοθήκης ακολουθούμενο από τον αριθμό έκδοσης. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [ScaledDuration](../../groupdocs.metadata.formats.video/matroskasegment/scaledduration) { get; } | Λαμβάνει την κλιμακούμενη διάρκεια του SEGMENT. |
| [SegmentFilename](../../groupdocs.metadata.formats.video/matroskasegment/segmentfilename) { get; } | Λαμβάνει το όνομα αρχείου που αντιστοιχεί σε αυτό το Τμήμα. |
| [SegmentUid](../../groupdocs.metadata.formats.video/matroskasegment/segmentuid) { get; } | Λαμβάνει τον μοναδικό αριθμό 128 bit που προσδιορίζει ένα SEGMENT. Προφανώς, ένα αρχείο μπορεί να αναφέρεται από άλλο αρχείο μόνο εάν υπάρχει SEGMENTUID, ωστόσο, η αναπαραγωγή είναι δυνατή χωρίς αυτό το UID. |
| [TimecodeScale](../../groupdocs.metadata.formats.video/matroskasegment/timecodescale) { get; } | Λαμβάνει την τιμή κλίμακας του χρονικού κωδικού. Κάθε κλιμακούμενος κωδικός χρόνου σε ένα αρχείο MATROSKA πολλαπλασιάζεται επί TIMECODESCALE για να ληφθεί ο κωδικός χρόνου σε νανοδευτερόλεπτα. Σημειώστε ότι δεν κλιμακώνονται όλοι οι κωδικοί χρόνου! |
| [Title](../../groupdocs.metadata.formats.video/matroskasegment/title) { get; } | Παίρνει το γενικό όνομα του Τμήματος. |
| [WritingApp](../../groupdocs.metadata.formats.video/matroskasegment/writingapp) { get; } | Λαμβάνει το πλήρες όνομα της εφαρμογής ακολουθούμενο από τον αριθμό έκδοσης. |

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
