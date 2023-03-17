---
title: Jpeg2000RootPackage
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει το ριζικό πακέτο που προορίζεται για εργασία με μεταδεδομένα σε μια εικόνα JPEG2000.
type: docs
weight: 1800
url: /el/net/groupdocs.metadata.formats.image/jpeg2000rootpackage/
---
## Jpeg2000RootPackage class

Αντιπροσωπεύει το ριζικό πακέτο που προορίζεται για εργασία με μεταδεδομένα σε μια εικόνα JPEG2000.

```csharp
public class Jpeg2000RootPackage : ImageRootPackage, IExif, IXmp
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [ExifPackage](../../groupdocs.metadata.formats.image/jpeg2000rootpackage/exifpackage) { get; set; } | Λαμβάνει ή ορίζει το πακέτο μεταδεδομένων EXIF. |
| [FileType](../../groupdocs.metadata.formats.image/imagerootpackage/filetype) { get; } | Λαμβάνει το πακέτο μεταδεδομένων τύπου αρχείου. (2 properties) |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Jpeg2000Package](../../groupdocs.metadata.formats.image/jpeg2000rootpackage/jpeg2000package) { get; } | Λαμβάνει το πακέτο εγγενών μεταδεδομένων JPEG2000. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [XmpPackage](../../groupdocs.metadata.formats.image/jpeg2000rootpackage/xmppackage) { get; set; } | Λαμβάνει ή ορίζει το πακέτο μεταδεδομένων XMP. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Προσθέτει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Καθορίζει εάν το πακέτο περιέχει μια ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Βρίσκει τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η αναζήτηση είναι αναδρομική, επομένως επηρεάζει όλα τα ένθετα πακέτα επίσης. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Επιστρέφει έναν απαριθμητή που επαναλαμβάνει τη συλλογή. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Καταργεί τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Αφαιρεί τις ιδιότητες μεταδεδομένων με δυνατότητα εγγραφής από το πακέτο. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ορίζει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. Αυτή η μέθοδος είναι ένας συνδυασμός[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) και[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Εάν μια υπάρχουσα ιδιότητα ικανοποιεί το κατηγόρημα, η τιμή της ενημερώνεται. Εάν λείπει μια γνωστή ιδιότητα στο πακέτο που ικανοποιεί το κατηγόρημα, προστίθεται στο πακέτο. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ενημερώνει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Εργασία με μεταδεδομένα σε εικόνες JPEG2000](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG2000+images)
* [Εργασία με μεταδεδομένα XMP](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Δείτε επίσης

* class [ImageRootPackage](../imagerootpackage)
* interface [IExif](../../groupdocs.metadata.standards.exif/iexif)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
