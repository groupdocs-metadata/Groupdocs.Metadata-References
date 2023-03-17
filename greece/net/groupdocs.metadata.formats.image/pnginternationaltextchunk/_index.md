---
title: PngInternationalTextChunk
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει διεθνή δεδομένα κειμένου που εξάγονται από μια εικόνα PNG.
type: docs
weight: 1840
url: /el/net/groupdocs.metadata.formats.image/pnginternationaltextchunk/
---
## PngInternationalTextChunk class

Αντιπροσωπεύει διεθνή δεδομένα κειμένου που εξάγονται από μια εικόνα PNG.

```csharp
public class PngInternationalTextChunk : PngCompressedTextChunk
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [CompressionMethod](../../groupdocs.metadata.formats.image/pngcompressedtextchunk/compressionmethod) { get; } | Λαμβάνει τον αλγόριθμο που χρησιμοποιείται για τη συμπίεση των τμημάτων δεδομένων. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [IsCompressed](../../groupdocs.metadata.formats.image/pnginternationaltextchunk/iscompressed) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν το κομμάτι είναι συμπιεσμένο. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [Keyword](../../groupdocs.metadata.formats.image/pngtextchunk/keyword) { get; } | Λαμβάνει τη λέξη-κλειδί που υποδεικνύει τον τύπο των πληροφοριών που αντιπροσωπεύεται από το κομμάτι. |
| [Language](../../groupdocs.metadata.formats.image/pnginternationaltextchunk/language) { get; } | Λαμβάνει την ανθρώπινη γλώσσα που χρησιμοποιείται από τη μεταφρασμένη λέξη-κλειδί και το κείμενο. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [Text](../../groupdocs.metadata.formats.image/pngtextchunk/text) { get; } | Λαμβάνει την πραγματική συμβολοσειρά κειμένου που αντιπροσωπεύεται από το κομμάτι. |
| [TranslatedKeyword](../../groupdocs.metadata.formats.image/pnginternationaltextchunk/translatedkeyword) { get; } | Λαμβάνει τη μεταφρασμένη λέξη-κλειδί που περιέχει μια μετάφραση της λέξης-κλειδιού στη γλώσσα που υποδεικνύεται από την ιδιότητα γλώσσας. |

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

### Δείτε επίσης

* class [PngCompressedTextChunk](../pngcompressedtextchunk)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
