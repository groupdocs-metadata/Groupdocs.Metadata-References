---
title: IptcRecordSet
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει μια συλλογή εγγραφών IPTC.
type: docs
weight: 2940
url: /el/net/groupdocs.metadata.standards.iptc/iptcrecordset/
---
## IptcRecordSet class

Αντιπροσωπεύει μια συλλογή εγγραφών IPTC.

```csharp
public sealed class IptcRecordSet : CustomPackage
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [IptcRecordSet](iptcrecordset#constructor)() | Αρχικοποιεί μια νέα παρουσία του[`IptcRecordSet`](../iptcrecordset) τάξη. |
| [IptcRecordSet](iptcrecordset#constructor_1)(IptcDataSet[]) | Αρχικοποιεί μια νέα παρουσία του[`IptcRecordSet`](../iptcrecordset) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [ApplicationRecord](../../groupdocs.metadata.standards.iptc/iptcrecordset/applicationrecord) { get; set; } | Λαμβάνει ή ορίζει το αρχείο της εφαρμογής. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [EnvelopeRecord](../../groupdocs.metadata.standards.iptc/iptcrecordset/enveloperecord) { get; set; } | Λαμβάνει ή ορίζει την εγγραφή φακέλου. |
| [Item](../../groupdocs.metadata.standards.iptc/iptcrecordset/item) { get; } | Λαμβάνει το[`IptcRecord`](../iptcrecord) με τον καθορισμένο αριθμό. (3 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Add](../../groupdocs.metadata.standards.iptc/iptcrecordset/add)(IptcDataSet) | Προσθέτει το καθορισμένο σύνολο δεδομένων στην κατάλληλη εγγραφή. Το σύνολο δεδομένων θεωρείται επαναλαμβανόμενο εάν υπάρχει ήδη σύνολο δεδομένων με τον καθορισμένο αριθμό. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Προσθέτει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Clear](../../groupdocs.metadata.standards.iptc/iptcrecordset/clear)() | Αφαιρεί όλες τις εγγραφές από τη συλλογή. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Καθορίζει εάν το πακέτο περιέχει μια ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Βρίσκει τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η αναζήτηση είναι αναδρομική, επομένως επηρεάζει όλα τα ένθετα πακέτα επίσης. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Επιστρέφει έναν απαριθμητή που επαναλαμβάνει τη συλλογή. |
| [Remove](../../groupdocs.metadata.standards.iptc/iptcrecordset/remove#remove)(byte) | Καταργεί την εγγραφή με τον καθορισμένο αριθμό εγγραφής. |
| [Remove](../../groupdocs.metadata.standards.iptc/iptcrecordset/remove#remove_1)(byte, byte) | Καταργεί το σύνολο δεδομένων με τον καθορισμένο αριθμό εγγραφής και συνόλου δεδομένων. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Καταργεί τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Αφαιρεί τις ιδιότητες μεταδεδομένων με δυνατότητα εγγραφής από το πακέτο. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Set](../../groupdocs.metadata.standards.iptc/iptcrecordset/set)(IptcDataSet) | Προσθέτει ή ενημερώνει το καθορισμένο σύνολο δεδομένων στην κατάλληλη εγγραφή. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ορίζει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. Αυτή η μέθοδος είναι ένας συνδυασμός[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) και[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Εάν μια υπάρχουσα ιδιότητα ικανοποιεί το κατηγόρημα, η τιμή της ενημερώνεται. Εάν λείπει μια γνωστή ιδιότητα στο πακέτο που ικανοποιεί το κατηγόρημα, προστίθεται στο πακέτο. |
| [ToDataSetList](../../groupdocs.metadata.standards.iptc/iptcrecordset/todatasetlist)() | Δημιουργεί μια λίστα συνόλων δεδομένων από το πακέτο. |
| [ToList](../../groupdocs.metadata.standards.iptc/iptcrecordset/tolist)() | Δημιουργεί μια λίστα από το πακέτο. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ενημερώνει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Εργασία με μεταδεδομένα IPTC IIM](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Παραδείγματα

Αυτό το δείγμα κώδικα δείχνει ζεστό για ενημέρωση βασικών ιδιοτήτων μεταδεδομένων IPTC.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IIptc root = metadata.GetRootPackage() as IIptc;
    if (root != null)
    {
        // Ορίστε το πακέτο IPTC εάν λείπει
        if (root.IptcPackage == null)
        {
            root.IptcPackage = new IptcRecordSet();
        }

        if (root.IptcPackage.EnvelopeRecord == null)
        {
            root.IptcPackage.EnvelopeRecord = new IptcEnvelopeRecord();
        }

        root.IptcPackage.EnvelopeRecord.DateSent = DateTime.Now;
        root.IptcPackage.EnvelopeRecord.ProductID = Guid.NewGuid().ToString();

        //...

        if (root.IptcPackage.ApplicationRecord == null)
        {
            root.IptcPackage.ApplicationRecord = new IptcApplicationRecord();
        }

        root.IptcPackage.ApplicationRecord.ByLine = "GroupDocs";
        root.IptcPackage.ApplicationRecord.Headline = "test";
        root.IptcPackage.ApplicationRecord.ByLineTitle = "code sample";
        root.IptcPackage.ApplicationRecord.ReleaseDate = DateTime.Today;

        //...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Δείτε επίσης

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* χώρος ονομάτων [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
