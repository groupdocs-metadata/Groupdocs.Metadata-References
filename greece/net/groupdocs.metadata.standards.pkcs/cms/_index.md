---
title: Cms
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει ένα ψηφιακό σήμα που δημιουργήθηκε με Cryptographic Message Syntax CMS  το πρότυπο του IETF για κρυπτογραφικά προστατευμένα μηνύματα. Το CMS βασίζεται στη σύνταξη του PKCS 7 που καθορίζεται στο RFC 5652. Δείτεhttps//tools.ietf.org/html/rfc5652https//tools.ietf.org/html/rfc5652 για περισσότερες πληροφορίες.
type: docs
weight: 2960
url: /el/net/groupdocs.metadata.standards.pkcs/cms/
---
## Cms class

Αντιπροσωπεύει ένα ψηφιακό σήμα που δημιουργήθηκε με Cryptographic Message Syntax (CMS) - το πρότυπο του IETF για κρυπτογραφικά προστατευμένα μηνύματα. Το CMS βασίζεται στη σύνταξη του PKCS #7, που καθορίζεται στο RFC 5652. Δείτε[https://tools.ietf.org/html/rfc5652](https://tools.ietf.org/html/rfc5652) για περισσότερες πληροφορίες.

```csharp
public class Cms : DigitalSignature
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [CertificateRawData](../../groupdocs.metadata.standards.signing/digitalsignature/certificaterawdata) { get; } | Λαμβάνει τα πρωτογενή δεδομένα του πιστοποιητικού. |
| [Certificates](../../groupdocs.metadata.standards.pkcs/cms/certificates) { get; } | Λαμβάνει τη συλλογή των πιστοποιητικών. |
| [CertificateSubject](../../groupdocs.metadata.standards.signing/digitalsignature/certificatesubject) { get; } | Λαμβάνει το διακριτικό όνομα θέματος από ένα πιστοποιητικό. |
| [Comments](../../groupdocs.metadata.standards.signing/digitalsignature/comments) { get; } | Λαμβάνει το σχόλιο για το σκοπό της υπογραφής. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [DigestAlgorithms](../../groupdocs.metadata.standards.pkcs/cms/digestalgorithms) { get; } | Λαμβάνει τη σειρά των αναγνωριστικών αλγορίθμων σύνοψης μηνυμάτων. Μπορεί να υπάρχει οποιοσδήποτε αριθμός στοιχείων στη συλλογή, συμπεριλαμβανομένου του μηδενός. |
| [EncapsulatedContent](../../groupdocs.metadata.standards.pkcs/cms/encapsulatedcontent) { get; } | Λαμβάνει το υπογεγραμμένο περιεχόμενο, που αποτελείται από ένα αναγνωριστικό τύπου περιεχομένου και το ίδιο το περιεχόμενο. |
| virtual [IsValid](../../groupdocs.metadata.standards.signing/digitalsignature/isvalid) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η υπογραφή είναι έγκυρη. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [Signers](../../groupdocs.metadata.standards.pkcs/cms/signers) { get; } | Λαμβάνει τη συλλογή των πακέτων πληροφοριών ανά υπογράφοντα. |
| override [SignTime](../../groupdocs.metadata.standards.pkcs/cms/signtime) { get; } | Λαμβάνει την ώρα κατά την οποία ο υπογράφοντος (υποτίθεται ότι) εκτέλεσε τη διαδικασία υπογραφής. |

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

* class [DigitalSignature](../../groupdocs.metadata.standards.signing/digitalsignature)
* χώρος ονομάτων [GroupDocs.Metadata.Standards.Pkcs](../../groupdocs.metadata.standards.pkcs)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
