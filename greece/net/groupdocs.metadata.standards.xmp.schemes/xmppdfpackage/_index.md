---
title: XmpPdfPackage
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Καθορίζει ιδιότητες που χρησιμοποιούνται με έγγραφα Adobe PDF.
type: docs
weight: 3190
url: /el/net/groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/
---
## XmpPdfPackage class

Καθορίζει ιδιότητες που χρησιμοποιούνται με έγγραφα Adobe PDF.

```csharp
public sealed class XmpPdfPackage : XmpPackage
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [XmpPdfPackage](xmppdfpackage)() | Αρχικοποιεί μια νέα παρουσία του[`XmpPdfPackage`](../xmppdfpackage) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [IsTrapped](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/istrapped) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το έγγραφο έχει παγιδευτεί. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [Keywords](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/keywords) { get; set; } | Λαμβάνει ή ορίζει τις λέξεις-κλειδιά. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Λαμβάνει το URI χώρου ονομάτων. |
| [PdfVersion](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/pdfversion) { get; set; } | Λαμβάνει ή ορίζει την έκδοση του αρχείου PDF. Για παράδειγμα, 1.0, 1.3 και ούτω καθεξής. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Παίρνει το πρόθεμα xmlns. |
| [Producer](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/producer) { get; set; } | Λαμβάνει ή ορίζει το όνομα του εργαλείου που δημιούργησε το έγγραφο PDF. |
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
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/set#set_7)(string, string) | Ορίζει την ιδιότητα συμβολοσειράς. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Ορίζει την τιμή που κληρονομείται από[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Ορίζει την τιμή που κληρονομείται από[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Ορίζει την τιμή που κληρονομείται από[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ορίζει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. Αυτή η μέθοδος είναι ένας συνδυασμός[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) και[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Εάν μια υπάρχουσα ιδιότητα ικανοποιεί το κατηγόρημα, η τιμή της ενημερώνεται. Εάν λείπει μια γνωστή ιδιότητα στο πακέτο που ικανοποιεί το κατηγόρημα, προστίθεται στο πακέτο. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ενημερώνει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |

### Δείτε επίσης

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* χώρος ονομάτων [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
