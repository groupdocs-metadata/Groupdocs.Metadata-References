---
title: XmpDimensions
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Περιέχει διαστάσεις για ένα σχεδιασμένο αντικείμενο.
type: docs
weight: 3380
url: /el/net/groupdocs.metadata.standards.xmp/xmpdimensions/
---
## XmpDimensions class

Περιέχει διαστάσεις για ένα σχεδιασμένο αντικείμενο.

```csharp
public sealed class XmpDimensions : XmpComplexType
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [XmpDimensions](xmpdimensions#constructor)() | Αρχικοποιεί μια νέα παρουσία του[`XmpDimensions`](../xmpdimensions) τάξη. |
| [XmpDimensions](xmpdimensions#constructor_1)(double, double) | Αρχικοποιεί μια νέα παρουσία του[`XmpDimensions`](../xmpdimensions) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [Height](../../groupdocs.metadata.standards.xmp/xmpdimensions/height) { get; set; } | Παίρνει ή ρυθμίζει το ύψος. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Λαμβάνει τα URI χώρου ονομάτων που χρησιμοποιούνται στο[`XmpComplexType`](../xmpcomplextype) παράδειγμα. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Λαμβάνει τα προθέματα του χώρου ονομάτων που χρησιμοποιούνται στο[`XmpComplexType`](../xmpcomplextype) παράδειγμα. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [Units](../../groupdocs.metadata.standards.xmp/xmpdimensions/units) { get; set; } | Λαμβάνει ή ορίζει τις μονάδες. |
| [Width](../../groupdocs.metadata.standards.xmp/xmpdimensions/width) { get; set; } | Λαμβάνει ή ορίζει το πλάτος. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Προσθέτει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Καθορίζει εάν το πακέτο περιέχει μια ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Βρίσκει τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η αναζήτηση είναι αναδρομική, επομένως επηρεάζει όλα τα ένθετα πακέτα επίσης. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Επιστρέφει έναν απαριθμητή που επαναλαμβάνει τη συλλογή. |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | Λαμβάνει το URI χώρου ονομάτων που σχετίζεται με το καθορισμένο πρόθεμα. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | Επιστρέφει την τιμή που περιέχεται στη συμβολοσειρά σε μορφή XMP. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Καταργεί τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Αφαιρεί τις ιδιότητες μεταδεδομένων με δυνατότητα εγγραφής από το πακέτο. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ορίζει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. Αυτή η μέθοδος είναι ένας συνδυασμός[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) και[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Εάν μια υπάρχουσα ιδιότητα ικανοποιεί το κατηγόρημα, η τιμή της ενημερώνεται. Εάν λείπει μια γνωστή ιδιότητα στο πακέτο που ικανοποιεί το κατηγόρημα, προστίθεται στο πακέτο. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | Επιστρέφει αString που αντιπροσωπεύει αυτήν την περίπτωση. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ενημερώνει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |

### Δείτε επίσης

* class [XmpComplexType](../xmpcomplextype)
* χώρος ονομάτων [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
