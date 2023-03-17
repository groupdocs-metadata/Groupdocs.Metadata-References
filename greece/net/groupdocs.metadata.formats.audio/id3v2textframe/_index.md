---
title: ID3V2TextFrame
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει ένα πλαίσιο κειμένου σε έναID3V2Tag./id3v2tag . Σχεδόν όλα τα καρέ που ξεκινούν με τον χαρακτήρα T ανήκουν σε αυτήν την κατηγορία. Υπάρχει μόνο μία εξαίρεση η οποία είναι το πλαίσιο TXXX που αντιπροσωπεύεται από τοID3V2UserDefinedFrame./id3v2userdefinedframe τάξη.
type: docs
weight: 520
url: /el/net/groupdocs.metadata.formats.audio/id3v2textframe/
---
## ID3V2TextFrame class

Αντιπροσωπεύει ένα πλαίσιο κειμένου σε ένα[`ID3V2Tag`](../id3v2tag) . Σχεδόν όλα τα καρέ που ξεκινούν με τον χαρακτήρα T ανήκουν σε αυτήν την κατηγορία. Υπάρχει μόνο μία εξαίρεση, η οποία είναι το πλαίσιο TXXX που αντιπροσωπεύεται από το[`ID3V2UserDefinedFrame`](../id3v2userdefinedframe) τάξη.

```csharp
public class ID3V2TextFrame : ID3V2TagFrame
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [ID3V2TextFrame](id3v2textframe)(string, ID3V2EncodingType, string) | Αρχικοποιεί μια νέα παρουσία του[`ID3V2TextFrame`](../id3v2textframe) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [Data](../../groupdocs.metadata.formats.audio/id3v2tagframe/data) { get; } | Λαμβάνει τα δεδομένα πλαισίου. |
| [Flags](../../groupdocs.metadata.formats.audio/id3v2tagframe/flags) { get; } | Λαμβάνει τις σημαίες πλαισίου. |
| [Id](../../groupdocs.metadata.formats.audio/id3v2tagframe/id) { get; } | Λαμβάνει το αναγνωριστικό του πλαισίου (τέσσερις χαρακτήρες που ταιριάζουν με το μοτίβο [A-Z0-9]). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [Text](../../groupdocs.metadata.formats.audio/id3v2textframe/text) { get; } | Λαμβάνει την τιμή κειμένου. |
| [TextEncoding](../../groupdocs.metadata.formats.audio/id3v2textframe/textencoding) { get; } | Λαμβάνει την κωδικοποίηση κειμένου. |

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

* [Χειρισμός της ετικέτας ID3v2](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Δείτε επίσης

* class [ID3V2TagFrame](../id3v2tagframe)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
