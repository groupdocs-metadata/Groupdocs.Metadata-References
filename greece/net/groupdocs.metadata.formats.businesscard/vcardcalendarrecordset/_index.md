---
title: VCardCalendarRecordset
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει ένα σύνολο εγγραφών vCard Ημερολογίου.
type: docs
weight: 640
url: /el/net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/
---
## VCardCalendarRecordset class

Αντιπροσωπεύει ένα σύνολο εγγραφών vCard Ημερολογίου.

```csharp
public class VCardCalendarRecordset : VCardRecordset
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BusyTimeEntries](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/busytimeentries) { get; } | Λαμβάνει τα URI για τον απασχολημένο χρόνο που σχετίζεται με το αντικείμενο. |
| [BusyTimeRecords](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/busytimerecords) { get; } | Λαμβάνει τα URI για τον απασχολημένο χρόνο που σχετίζεται με το αντικείμενο. |
| [CalendarAddresses](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendaraddresses) { get; } | Λαμβάνει τις διευθύνσεις χρηστών ημερολογίου στις οποίες θα πρέπει να σταλεί ένα αίτημα προγραμματισμού για το αντικείμενο που αντιπροσωπεύεται από την vCard. |
| [CalendarAddressRecords](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendaraddressrecords) { get; } | Λαμβάνει τις διευθύνσεις χρηστών ημερολογίου στις οποίες θα πρέπει να σταλεί ένα αίτημα προγραμματισμού για το αντικείμενο που αντιπροσωπεύεται από την vCard. |
| [CalendarUriRecords](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendarurirecords) { get; } | Λαμβάνει τα URI για το ημερολόγιο που σχετίζεται με το αντικείμενο που αντιπροσωπεύεται από την vCard. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [UriCalendarEntries](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/uricalendarentries) { get; } | Λαμβάνει τα URI για το ημερολόγιο που σχετίζεται με το αντικείμενο που αντιπροσωπεύεται από την vCard. |

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

* [Εργασία με μεταδεδομένα vCard](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Δείτε επίσης

* class [VCardRecordset](../vcardrecordset)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
