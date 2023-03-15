---
title: ExifGpsPackage
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει τα μεταδεδομένα GPS σε ένα πακέτο μεταδεδομένων EXIF.
type: docs
weight: 2770
url: /el/net/groupdocs.metadata.standards.exif/exifgpspackage/
---
## ExifGpsPackage class

Αντιπροσωπεύει τα μεταδεδομένα GPS σε ένα πακέτο μεταδεδομένων EXIF.

```csharp
public sealed class ExifGpsPackage : ExifDictionaryBasePackage
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [ExifGpsPackage](exifgpspackage)() | Αρχικοποιεί μια νέα παρουσία του[`ExifGpsPackage`](../exifgpspackage) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Altitude](../../groupdocs.metadata.standards.exif/exifgpspackage/altitude) { get; set; } | Λαμβάνει ή ορίζει το υψόμετρο με βάση την αναφορά σε[`AltitudeRef`](./altituderef) . Η μονάδα αναφοράς είναι μέτρα. |
| [AltitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/altituderef) { get; set; } | Λαμβάνει ή ορίζει το υψόμετρο που χρησιμοποιείται ως υψόμετρο αναφοράς. Εάν η αναφορά είναι η στάθμη της θάλασσας και το υψόμετρο είναι πάνω από την επιφάνεια της θάλασσας, δίνεται το 0. Εάν το υψόμετρο είναι κάτω από την επιφάνεια της θάλασσας, δίνεται η τιμή 1 και το υψόμετρο υποδεικνύεται ως απόλυτη τιμή στο[`Altitude`](./altitude) tag. |
| [AreaInformation](../../groupdocs.metadata.standards.exif/exifgpspackage/areainformation) { get; set; } | Λαμβάνει ή ορίζει τη συμβολοσειρά χαρακτήρων που καταγράφει το όνομα της περιοχής GPS. Το πρώτο byte υποδεικνύει τον κωδικό χαρακτήρα που χρησιμοποιείται και ακολουθεί το όνομα της περιοχής GPS. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [DataDegreeOfPrecision](../../groupdocs.metadata.standards.exif/exifgpspackage/datadegreeofprecision) { get; set; } | Λαμβάνει ή ρυθμίζει το GPS DOP (βαθμός ακρίβειας δεδομένων). Μια τιμή HDOP γράφεται κατά τη δισδιάστατη μέτρηση και η τιμή PDOP κατά τη διάρκεια της τρισδιάστατης μέτρησης. |
| [DateStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/datestamp) { get; set; } | Λαμβάνει ή ορίζει τις πληροφορίες ημερομηνίας και ώρας εγγραφής συμβολοσειράς χαρακτήρων σε σχέση με το UTC (Συντονισμένη Παγκόσμια Ώρα). Η μορφή είναι ΕΕΕΕ:ΜΜ:ΗΗ. |
| [DestBearing](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearing) { get; set; } | Λαμβάνει ή ρυθμίζει το ρουλεμάν GPS στο σημείο προορισμού. Το εύρος τιμών είναι από 0,00 έως 359,99. |
| [DestBearingRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearingref) { get; set; } | Λαμβάνει ή ορίζει την αναφορά GPS που χρησιμοποιείται για να δώσει το ρουλεμάν στο σημείο προορισμού. Το 'T' υποδηλώνει την πραγματική κατεύθυνση και το 'M' είναι η μαγνητική κατεύθυνση. |
| [DestDistance](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistance) { get; set; } | Λαμβάνει ή ορίζει την απόσταση GPS στο σημείο προορισμού. |
| [DestDistanceRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistanceref) { get; set; } | Λαμβάνει ή ρυθμίζει τη μονάδα GPS που χρησιμοποιείται για την έκφραση της απόστασης από το σημείο προορισμού. Τα 'K', 'M' και 'N' αντιπροσωπεύουν χιλιόμετρα, μίλια και κόμβους. |
| [DestLatitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatitude) { get; set; } | Λαμβάνει ή ορίζει το γεωγραφικό πλάτος GPS του σημείου προορισμού. |
| [DestLatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatituderef) { get; set; } | Λαμβάνει ή ορίζει την τιμή GPS που υποδεικνύει εάν το γεωγραφικό πλάτος του σημείου προορισμού είναι βόρειο ή νότιο γεωγραφικό πλάτος. Η τιμή ASCII 'N' υποδεικνύει το βόρειο γεωγραφικό πλάτος και το 'S' είναι το νότιο γεωγραφικό πλάτος. |
| [DestLongitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongitude) { get; set; } | Λαμβάνει ή ορίζει το γεωγραφικό μήκος GPS του σημείου προορισμού. |
| [DestLongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongituderef) { get; set; } | Λαμβάνει ή ορίζει την τιμή GPS που υποδεικνύει εάν το γεωγραφικό μήκος του σημείου προορισμού είναι ανατολικό ή δυτικό γεωγραφικό μήκος. Το ASCII 'E' υποδεικνύει ανατολικό γεωγραφικό μήκος και το 'W' είναι δυτικό γεωγραφικό μήκος. |
| [Differential](../../groupdocs.metadata.standards.exif/exifgpspackage/differential) { get; set; } | Λαμβάνει ή ορίζει μια τιμή GPS που υποδεικνύει εάν εφαρμόζεται διόρθωση διαφορικού στον δέκτη GPS. |
| [GpsTrack](../../groupdocs.metadata.standards.exif/exifgpspackage/gpstrack) { get; set; } | Λαμβάνει ή ρυθμίζει την κατεύθυνση της κίνησης του δέκτη GPS. |
| [ImgDirection](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirection) { get; set; } | Λαμβάνει ή ορίζει την κατεύθυνση GPS της εικόνας όταν τραβήχτηκε. Το εύρος τιμών είναι από 0,00 έως 359,99. |
| [ImgDirectionRef](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirectionref) { get; set; } | Λαμβάνει ή ορίζει την αναφορά GPS για να δώσει την κατεύθυνση της εικόνας κατά τη λήψη της. Το 'T' υποδηλώνει την πραγματική κατεύθυνση και το 'M' είναι η μαγνητική κατεύθυνση. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Λαμβάνει την ετικέτα TIFF με το καθορισμένο αναγνωριστικό. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [Latitude](../../groupdocs.metadata.standards.exif/exifgpspackage/latitude) { get; set; } | Λαμβάνει ή ρυθμίζει το γεωγραφικό πλάτος GPS. |
| [LatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/latituderef) { get; set; } | Λαμβάνει ή ορίζει μια τιμή GPS που υποδεικνύει εάν το γεωγραφικό πλάτος είναι βόρειο ή νότιο γεωγραφικό πλάτος. |
| [Longitude](../../groupdocs.metadata.standards.exif/exifgpspackage/longitude) { get; set; } | Λαμβάνει ή ρυθμίζει το γεωγραφικό μήκος GPS. |
| [LongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/longituderef) { get; set; } | Λαμβάνει ή ορίζει μια τιμή GPS που υποδεικνύει εάν το γεωγραφικό μήκος είναι ανατολικό ή δυτικό γεωγραφικό μήκος. |
| [MapDatum](../../groupdocs.metadata.standards.exif/exifgpspackage/mapdatum) { get; set; } | Λαμβάνει ή ορίζει τα δεδομένα γεωδαιτικής έρευνας που χρησιμοποιούνται από τον δέκτη GPS. |
| [MeasureMode](../../groupdocs.metadata.standards.exif/exifgpspackage/measuremode) { get; set; } | Λαμβάνει ή ρυθμίζει τη λειτουργία μέτρησης GPS. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [ProcessingMethod](../../groupdocs.metadata.standards.exif/exifgpspackage/processingmethod) { get; set; } | Λαμβάνει ή ορίζει μια συμβολοσειρά χαρακτήρων που καταγράφει το όνομα της μεθόδου που χρησιμοποιείται για την εύρεση θέσης. Το πρώτο byte υποδεικνύει τον κωδικό χαρακτήρα που χρησιμοποιείται και ακολουθεί το όνομα της μεθόδου. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [Satellites](../../groupdocs.metadata.standards.exif/exifgpspackage/satellites) { get; set; } | Λαμβάνει ή ορίζει τους δορυφόρους GPS που χρησιμοποιούνται για μετρήσεις. Αυτή η ετικέτα μπορεί να χρησιμοποιηθεί για να περιγράψει τον αριθμό των δορυφόρων, τον αριθμό ID τους, τη γωνία ανύψωσης, το αζιμούθιο, το SNR και άλλες πληροφορίες σε συμβολισμό ASCII. Η μορφή δεν έχει καθοριστεί . Εάν ο δέκτης GPS δεν μπορεί να πραγματοποιήσει μετρήσεις, η τιμή της ετικέτας θα οριστεί σε NULL. |
| [Speed](../../groupdocs.metadata.standards.exif/exifgpspackage/speed) { get; set; } | Λαμβάνει ή ρυθμίζει την ταχύτητα κίνησης του δέκτη GPS. |
| [SpeedRef](../../groupdocs.metadata.standards.exif/exifgpspackage/speedref) { get; set; } | Λαμβάνει ή ρυθμίζει τη μονάδα που χρησιμοποιείται για την έκφραση της ταχύτητας κίνησης του δέκτη GPS. 'K' 'M' και 'N' αντιπροσωπεύουν χιλιόμετρα ανά ώρα, μίλια ανά ώρα και κόμβους. |
| [Status](../../groupdocs.metadata.standards.exif/exifgpspackage/status) { get; set; } | Λαμβάνει ή ρυθμίζει την κατάσταση του δέκτη GPS κατά την εγγραφή της εικόνας. |
| [TimeStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/timestamp) { get; set; } | Λαμβάνει ή ορίζει την ώρα ως UTC (Συντονισμένη Παγκόσμια Ώρα). Η Χρονική Σφραγίδα εκφράζεται ως τρεις ΛΟΓΙΚΕΣ τιμές που δίνουν την ώρα, το λεπτό και το δευτερόλεπτο. |
| [TrackRef](../../groupdocs.metadata.standards.exif/exifgpspackage/trackref) { get; set; } | Λαμβάνει ή ορίζει την αναφορά για να δώσει την κατεύθυνση της κίνησης του δέκτη GPS. Το 'T' υποδηλώνει την αληθινή κατεύθυνση και το 'M' είναι η μαγνητική κατεύθυνση. |
| [VersionID](../../groupdocs.metadata.standards.exif/exifgpspackage/versionid) { get; set; } | Λαμβάνει ή ορίζει την έκδοση του GPS IFD. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Προσθέτει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Αφαιρεί όλες τις ετικέτες TIFF που είναι αποθηκευμένες στη συσκευασία. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Καθορίζει εάν το πακέτο περιέχει μια ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Βρίσκει τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η αναζήτηση είναι αναδρομική, επομένως επηρεάζει όλα τα ένθετα πακέτα επίσης. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Επιστρέφει έναν απαριθμητή που επαναλαμβάνει τη συλλογή. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Καταργεί την ιδιότητα με το καθορισμένο αναγνωριστικό. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Καταργεί τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Αφαιρεί τις ιδιότητες μεταδεδομένων με δυνατότητα εγγραφής από το πακέτο. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Προσθέτει ή αντικαθιστά την καθορισμένη ετικέτα. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ορίζει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. Αυτή η μέθοδος είναι ένας συνδυασμός[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) και[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Εάν μια υπάρχουσα ιδιότητα ικανοποιεί το κατηγόρημα, η τιμή της ενημερώνεται. Εάν λείπει μια γνωστή ιδιότητα στο πακέτο που ικανοποιεί το κατηγόρημα, προστίθεται στο πακέτο. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Δημιουργεί μια λίστα από το πακέτο. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ενημερώνει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Εργασία με μεταδεδομένα EXIF](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Δείτε επίσης

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* χώρος ονομάτων [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
