---
title: XmpPagedTextPackage
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει το πακέτο XMP PagedText.
type: docs
weight: 3180
url: /el/net/groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/
---
## XmpPagedTextPackage class

Αντιπροσωπεύει το πακέτο XMP Paged-Text.

```csharp
public sealed class XmpPagedTextPackage : XmpPackage
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [XmpPagedTextPackage](xmppagedtextpackage)() | Αρχικοποιεί μια νέα παρουσία του[`XmpPagedTextPackage`](../xmppagedtextpackage) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Colorants](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/colorants) { get; set; } | Λαμβάνει ή ορίζει μια σειρά από χρωστικές ουσίες (δείγματα) που χρησιμοποιούνται στο έγγραφο (συμπεριλαμβανομένων τυχόν εγγράφων που περιέχονται). |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [Fonts](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/fonts) { get; set; } | Λαμβάνει ή ορίζει έναν μη ταξινομημένο πίνακα γραμματοσειρών που χρησιμοποιούνται στο έγγραφο (συμπεριλαμβανομένων τυχόν εγγράφων που περιέχονται). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [MaxPageSize](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/maxpagesize) { get; set; } | Λαμβάνει ή ορίζει το μέγεθος της μεγαλύτερης σελίδας στο έγγραφο (συμπεριλαμβανομένων οποιωνδήποτε εγγράφων που περιέχονται). |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Λαμβάνει το URI χώρου ονομάτων. |
| [NumberOfPages](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/numberofpages) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό των σελίδων στο έγγραφο. |
| [PlateNames](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/platenames) { get; set; } | Λαμβάνει ή ορίζει μια διατεταγμένη σειρά ονομάτων πινακίδων που απαιτούνται για την εκτύπωση του εγγράφου (συμπεριλαμβανομένων τυχόν εγγράφων που περιέχονται). |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Παίρνει το πρόθεμα xmlns. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Λαμβάνει τον χώρο ονομάτων XML. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Προσθέτει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Καταργεί όλες τις ιδιότητες XMP. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Καθορίζει εάν το πακέτο περιέχει μια ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Βρίσκει τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η αναζήτηση είναι αναδρομική, επομένως επηρεάζει όλα τα ένθετα πακέτα επίσης. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Επιστρέφει έναν απαριθμητή που επαναλαμβάνει τη συλλογή. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Μετατρέπει την τιμή XMP στην αναπαράσταση XML. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Καταργεί την ιδιότητα με το καθορισμένο όνομα. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Καταργεί τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Αφαιρεί τις ιδιότητες μεταδεδομένων με δυνατότητα εγγραφής από το πακέτο. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Ορίζει την δυαδική ιδιότητα. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | ΣετDateTime ιδιοκτησία. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Ορίζει διπλή ιδιότητα. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Ορίζει την ιδιότητα ακέραιου αριθμού. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/set#set_7)(string, string) | Ορίζει την ιδιότητα συμβολοσειράς. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/set#set_2)(string, XmpArray) | Ορίζει την τιμή που κληρονομείται από[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Ορίζει την τιμή που κληρονομείται από[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Ορίζει την τιμή που κληρονομείται από[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ορίζει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. Αυτή η μέθοδος είναι ένας συνδυασμός[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) και[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Εάν μια υπάρχουσα ιδιότητα ικανοποιεί το κατηγόρημα, η τιμή της ενημερώνεται. Εάν λείπει μια γνωστή ιδιότητα στο πακέτο που ικανοποιεί το κατηγόρημα, προστίθεται στο πακέτο. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ενημερώνει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |

### Δείτε επίσης

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* χώρος ονομάτων [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
