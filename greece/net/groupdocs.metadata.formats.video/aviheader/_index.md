---
title: AviHeader
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει τη δομή AVIMAINHEADER σε ένα βίντεο AVI.
type: docs
weight: 2380
url: /el/net/groupdocs.metadata.formats.video/aviheader/
---
## AviHeader class

Αντιπροσωπεύει τη δομή AVIMAINHEADER σε ένα βίντεο AVI.

```csharp
public sealed class AviHeader : CustomPackage
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [AviHeader](aviheader)() | Αρχικοποιεί μια νέα παρουσία του[`AviHeader`](../aviheader) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AviHeaderFlags](../../groupdocs.metadata.formats.video/aviheader/aviheaderflags) { get; } | Λαμβάνει έναν συνδυασμό μηδέν ή περισσότερων από τις σημαίες AVI. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [Height](../../groupdocs.metadata.formats.video/aviheader/height) { get; } | Λαμβάνει το ύψος του αρχείου AVI σε pixel. |
| [InitialFrames](../../groupdocs.metadata.formats.video/aviheader/initialframes) { get; } | Λαμβάνει το αρχικό πλαίσιο για τα παρεμβαλλόμενα αρχεία.  Τα μη ενδιάμεσα αρχεία θα πρέπει να ορίζουν το μηδέν. Εάν δημιουργείτε παρεμβαλλόμενα αρχεία, καθορίστε τον αριθμό των πλαισίων στο αρχείο πριν από το αρχικό πλαίσιο της ακολουθίας AVI σε αυτό το μέλος. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [MaxBytesPerSec](../../groupdocs.metadata.formats.video/aviheader/maxbytespersec) { get; } | Λαμβάνει τον κατά προσέγγιση μέγιστο ρυθμό δεδομένων του αρχείου.  Αυτή η τιμή υποδεικνύει τον αριθμό των byte ανά δευτερόλεπτο που πρέπει να χειριστεί το σύστημα για να παρουσιάσει μια ακολουθία AVI ως που καθορίζεται από τις άλλες παραμέτρους που περιέχονται στα κύρια τμήματα κεφαλίδας και ροής. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [MicroSecPerFrame](../../groupdocs.metadata.formats.video/aviheader/microsecperframe) { get; } | Λαμβάνει τον αριθμό των μικροδευτερόλεπτων μεταξύ των καρέ. Αυτή η τιμή υποδεικνύει τον συνολικό χρόνο για το αρχείο. |
| [PaddingGranularity](../../groupdocs.metadata.formats.video/aviheader/paddinggranularity) { get; } | Λαμβάνει τη στοίχιση για δεδομένα, σε byte. Συμπληρώστε τα δεδομένα σε πολλαπλάσια αυτής της τιμής. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [Streams](../../groupdocs.metadata.formats.video/aviheader/streams) { get; } | Λαμβάνει τον αριθμό των ροών στο αρχείο. Για παράδειγμα, ένα αρχείο με ήχο και βίντεο έχει δύο ροές. |
| [SuggestedBufferSize](../../groupdocs.metadata.formats.video/aviheader/suggestedbuffersize) { get; } | Λαμβάνει το προτεινόμενο μέγεθος buffer για την ανάγνωση του αρχείου.  Γενικά, αυτό το μέγεθος πρέπει να είναι αρκετά μεγάλο ώστε να περιέχει το μεγαλύτερο κομμάτι στο αρχείο. Εάν οριστεί στο μηδέν ή αν είναι πολύ μικρό, το λογισμικό αναπαραγωγής θα πρέπει να ανακατανείμει τη μνήμη κατά την αναπαραγωγή, γεγονός που θα μειώσει την απόδοση. Για ένα παρεμβαλλόμενο αρχείο, το μέγεθος της προσωρινής μνήμης θα πρέπει να είναι αρκετά μεγάλο για να διαβάσει μια ολόκληρη εγγραφή και όχι μόνο ένα κομμάτι. |
| [TotalFrames](../../groupdocs.metadata.formats.video/aviheader/totalframes) { get; } | Λαμβάνει τον συνολικό αριθμό πλαισίων δεδομένων στο αρχείο. |
| [Width](../../groupdocs.metadata.formats.video/aviheader/width) { get; } | Λαμβάνει το πλάτος του αρχείου AVI σε pixel. |

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

* [Εργασία με μεταδεδομένα σε αρχεία AVI](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+AVI+files)

### Δείτε επίσης

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
