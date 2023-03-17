---
title: MatroskaSubtitleTrack
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει μεταδεδομένα υπότιτλων σε βίντεο Matroska.
type: docs
weight: 2520
url: /el/net/groupdocs.metadata.formats.video/matroskasubtitletrack/
---
## MatroskaSubtitleTrack class

Αντιπροσωπεύει μεταδεδομένα υπότιτλων σε βίντεο Matroska.

```csharp
public class MatroskaSubtitleTrack : MatroskaTrack
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [CodecID](../../groupdocs.metadata.formats.video/matroskatrack/codecid) { get; } | Λαμβάνει ένα αναγνωριστικό που αντιστοιχεί στον κωδικοποιητή. |
| [CodecName](../../groupdocs.metadata.formats.video/matroskatrack/codecname) { get; } | Λαμβάνει μια συμβολοσειρά αναγνώσιμη από τον άνθρωπο που καθορίζει τον κωδικοποιητή. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [DefaultDuration](../../groupdocs.metadata.formats.video/matroskatrack/defaultduration) { get; } | Λαμβάνει τον αριθμό των νανοδευτερόλεπτων (δεν κλιμακώνεται μέσω[`TimecodeScale`](../matroskasegment/timecodescale) ) ανά πλαίσιο. |
| [FlagEnabled](../../groupdocs.metadata.formats.video/matroskatrack/flagenabled) { get; } | Λαμβάνει την ενεργοποιημένη σημαία, true αν το κομμάτι είναι χρησιμοποιήσιμο. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [Language](../../groupdocs.metadata.formats.video/matroskatrack/language) { get; } | Λαμβάνει τη γλώσσα του κομματιού στη φόρμα γλωσσών Matroska. Αυτό το στοιχείο ΠΡΕΠΕΙ να αγνοηθεί εάν[`LanguageIetf`](../matroskatrack/languageietf) Το στοιχείο χρησιμοποιείται στο ίδιο TrackEntry. |
| [LanguageIetf](../../groupdocs.metadata.formats.video/matroskatrack/languageietf) { get; } | Λαμβάνει τη γλώσσα του κομματιού σύμφωνα με το BCP 47 και χρησιμοποιώντας το Μητρώο υποετικέτας γλώσσας IANA. Εάν χρησιμοποιείται αυτό το Στοιχείο, τότε οποιοδήποτε[`Language`](../matroskatrack/language) Τα στοιχεία που χρησιμοποιούνται στο ίδιο TrackEntry ΠΡΕΠΕΙ να αγνοηθούν. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [Name](../../groupdocs.metadata.formats.video/matroskatrack/name) { get; } | Λαμβάνει το όνομα του κομματιού αναγνώσιμο από τον άνθρωπο. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [Subtitles](../../groupdocs.metadata.formats.video/matroskasubtitletrack/subtitles) { get; } | Παίρνει τους υπότιτλους. |
| [TrackNumber](../../groupdocs.metadata.formats.video/matroskatrack/tracknumber) { get; } | Λαμβάνει τον αριθμό κομματιού όπως χρησιμοποιείται στην κεφαλίδα μπλοκ. Η χρήση περισσότερων από 127 κομματιών δεν ενθαρρύνεται, αν και η σχεδίαση επιτρέπει απεριόριστο αριθμό. |
| [TrackType](../../groupdocs.metadata.formats.video/matroskatrack/tracktype) { get; } | Παίρνει τον τύπο του κομματιού. |
| [TrackUid](../../groupdocs.metadata.formats.video/matroskatrack/trackuid) { get; } | Λαμβάνει το μοναδικό αναγνωριστικό για την αναγνώριση του κομματιού. Αυτό ΠΡΕΠΕΙ να διατηρηθεί το ίδιο όταν δημιουργείτε ένα αντίγραφο απευθείας ροής του κομματιού σε άλλο αρχείο. |

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

* class [MatroskaTrack](../matroskatrack)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
