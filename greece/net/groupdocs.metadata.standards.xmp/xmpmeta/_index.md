---
title: XmpMeta
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει το xmpmeta. Προαιρετικό. Ο σκοπός αυτού του στοιχείου είναι να προσδιορίσει μεταδεδομένα XMP μέσα σε γενικό κείμενο XML που μπορεί να περιέχει άλλες μη XMP χρήσεις του RDF.
type: docs
weight: 3460
url: /el/net/groupdocs.metadata.standards.xmp/xmpmeta/
---
## XmpMeta class

Αντιπροσωπεύει το xmpmeta. Προαιρετικό. Ο σκοπός αυτού του στοιχείου είναι να προσδιορίσει μεταδεδομένα XMP μέσα σε γενικό κείμενο XML που μπορεί να περιέχει άλλες μη XMP χρήσεις του RDF.

```csharp
public sealed class XmpMeta : XmpElementBase, IXmpType
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [XmpMeta](xmpmeta)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AdobeXmpToolkit](../../groupdocs.metadata.standards.xmp/xmpmeta/adobexmptoolkit) { get; } | Αποκτά την έκδοση του Adobe XMP toolkit. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Προσθέτει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [ClearAttributes](../../groupdocs.metadata.standards.xmp/xmpelementbase/clearattributes)() | Καταργεί όλα τα χαρακτηριστικά. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Καθορίζει εάν το πακέτο περιέχει μια ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| [ContainsAttribute](../../groupdocs.metadata.standards.xmp/xmpelementbase/containsattribute)(string) | Καθορίζει εάν το στοιχείο περιέχει ένα συγκεκριμένο χαρακτηριστικό. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Βρίσκει τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η αναζήτηση είναι αναδρομική, επομένως επηρεάζει όλα τα ένθετα πακέτα επίσης. |
| [GetAttribute](../../groupdocs.metadata.standards.xmp/xmpelementbase/getattribute)(string) | Παίρνει το χαρακτηριστικό. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Επιστρέφει έναν απαριθμητή που επαναλαμβάνει τη συλλογή. |
| [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpmeta/getxmprepresentation)() | Μετατρέπει την τιμή XMP στην αναπαράσταση xml. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Καταργεί τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Αφαιρεί τις ιδιότητες μεταδεδομένων με δυνατότητα εγγραφής από το πακέτο. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| override [SetAttribute](../../groupdocs.metadata.standards.xmp/xmpmeta/setattribute)(string, string) | Προσθέτει ένα χαρακτηριστικό. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ορίζει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. Αυτή η μέθοδος είναι ένας συνδυασμός[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) και[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Εάν μια υπάρχουσα ιδιότητα ικανοποιεί το κατηγόρημα, η τιμή της ενημερώνεται. Εάν λείπει μια γνωστή ιδιότητα στο πακέτο που ικανοποιεί το κατηγόρημα, προστίθεται στο πακέτο. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ενημερώνει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |

### Δείτε επίσης

* class [XmpElementBase](../xmpelementbase)
* interface [IXmpType](../ixmptype)
* χώρος ονομάτων [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
