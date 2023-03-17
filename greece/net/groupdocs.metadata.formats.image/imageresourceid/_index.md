---
title: ImageResourceID
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Τυπικοί αριθμοί ID πόρων εικόνας. Δεν χρησιμοποιούν όλες οι μορφές αρχείων όλα τα αναγνωριστικά. Ορισμένες πληροφορίες ενδέχεται να αποθηκευτούν σε άλλες ενότητες του αρχείου.
type: docs
weight: 1750
url: /el/net/groupdocs.metadata.formats.image/imageresourceid/
---
## ImageResourceID enumeration

Τυπικοί αριθμοί ID πόρων εικόνας. Δεν χρησιμοποιούν όλες οι μορφές αρχείων όλα τα αναγνωριστικά. Ορισμένες πληροφορίες ενδέχεται να αποθηκευτούν σε άλλες ενότητες του αρχείου.

```csharp
public enum ImageResourceID
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| ResolutionInfo | `1005` | Δομή ResolutionInfo. Δείτε το Παράρτημα Α στο έγγραφο PDF του Οδηγού API του Photoshop. |
| NamesOfAlphaChannels | `1006` | Ονόματα των καναλιών άλφα ως σειρά συμβολοσειρών Pascal. |
| Caption | `1008` | Η λεζάντα ως συμβολοσειρά Pascal. |
| BorderInformation | `1009` | Πληροφορίες συνόρων. Περιέχει έναν σταθερό αριθμό (2 byte πραγματικό, 2 bytes κλάσμα) για το πλάτος του περιγράμματος, και 2 byte για τις μονάδες περιγράμματος (1 = ίντσες, 2 = cm, 3 = σημεία, 4 = picas, 5 = στήλες). |
| BackgroundColor | `1010` | Χρώμα φόντου. [Δείτε περισσότερα.](http://www.adobe.com/devnet-apps/photoshop/fileformatashtml/#50577411_31265) |
| PrintFlags | `1011` | Εκτύπωση σημαιών. Μια σειρά από δυαδικές τιμές ενός byte (δείτε το παράθυρο διαλόγου Διαμόρφωση σελίδας): ετικέτες, σημάδια περικοπής, έγχρωμες γραμμές, σημάδια εγγραφής, αρνητικό, αναστροφή, παρεμβολή, λεζάντα, σημαίες εκτύπωσης. |
| Grayscale | `1012` | Πληροφορίες κλίμακας του γκρι και πολλαπλών καναλιών ημίτονο. |
| ColorHalftoning | `1013` | Πληροφορίες ημιτονισμού χρώματος. |
| DuotoneHalftoning | `1014` | Πληροφορίες ημιτονικής διχρωμίας. |
| GrayscaleFunction | `1015` | Κλίμακα του γκρι και λειτουργία μεταφοράς πολλαπλών καναλιών. |
| ColorTransferFunctions | `1016` | Λειτουργίες μεταφοράς χρώματος. |
| DuotoneTransferFunctions | `1017` | Λειτουργίες μεταφοράς Duotone. |
| DuotoneImageInformation | `1018` | Πληροφορίες εικόνας Duotone. |
| EPSOptions | `1021` | Επιλογές EPS. |
| QuickMaskInformation | `1022` | Πληροφορίες Quick Mask. 2 byte που περιέχουν το αναγνωριστικό καναλιού Quick Mask. 1- byte boolean που υποδεικνύει εάν η μάσκα ήταν αρχικά άδεια. |
| LayerStateInformation | `1024` | Πληροφορίες κατάστασης επιπέδου. 2 byte που περιέχουν τον δείκτη του επιπέδου στόχου (0 = κάτω στρώμα). |
| WorkingPath | `1025` | Διαδρομή εργασίας (δεν έχει αποθηκευτεί). Δείτε τη μορφή πόρου διαδρομής. |
| LayersGroupInformation | `1026` | Πληροφορίες ομάδας επιπέδων. 2 byte ανά επίπεδο που περιέχει ένα αναγνωριστικό ομάδας για τις ομάδες που σύρουν. Τα επίπεδα σε μια ομάδα έχουν το ίδιο αναγνωριστικό ομάδας. |
| Iptc | `1028` | Εγγραφή IPTC-NAA. Περιέχει τις πληροφορίες αρχείου... Δείτε την τεκμηρίωση στο φάκελο IPTC του φακέλου Documentation. |
| ImageModeForRawFormat | `1029` | Λειτουργία εικόνας για αρχεία ακατέργαστης μορφής. |
| JpegQuality | `1030` | Ποιότητα JPEG. Ιδιωτικό. |
| GridAndGuidesInfoPhotoshop4 | `1032` | Πληροφορίες πλέγματος και οδηγών. |
| ThumbnailResourcePhotoshop4 | `1033` | Πόρος μικρογραφιών μόνο για το Photoshop 4.0. |
| CopyrightFlagPhotoshop4 | `1034` | Σημαία πνευματικών δικαιωμάτων. Boolean που υποδεικνύει εάν η εικόνα προστατεύεται από πνευματικά δικαιώματα. Μπορεί να οριστεί μέσω της σουίτας ιδιοκτησίας ή από τον χρήστη στις Πληροφορίες αρχείου... |
| UrlPhotoshop4 | `1035` | URL . Λαβή συμβολοσειράς κειμένου με ενιαίο εντοπιστή πόρων. Μπορεί να οριστεί μέσω της σουίτας ιδιοκτησίας ή από τον χρήστη στις Πληροφορίες αρχείου... |
| ThumbnailResourcePhotoshop5 | `1036` | Πόρος μικρογραφιών (αντικαθιστά τον πόρο 1033). Δείτε τη μορφή πόρου μικρογραφίας. |
| GlobalAnglePhotoshop5 | `1037` | Καθολική γωνία. 4 byte που περιέχουν έναν ακέραιο μεταξύ 0 και 359, που είναι η συνολική γωνία φωτισμού για το επίπεδο εφέ. Εάν δεν υπάρχει, υποτίθεται ότι είναι 30, |
| IccProfilePhotoshop5 | `1039` | (Photoshop 5.0) Προφίλ ICC. Τα ακατέργαστα byte ενός προφίλ μορφής ICC (International Color Consortium). Δείτε το ICC1v42_2006-05.pdf στο φάκελο Documentation και το icProfileHeader.h στο Sample Code\Common\Includes. |
| WatermarkPhotoshop5 | `1040` | Υδατογράφημα. Ένα byte. |
| IccUntaggedProfilePhotoshop5 | `1041` | Προφίλ χωρίς ετικέτα ICC. 1 byte που απενεργοποιεί οποιονδήποτε υποτιθέμενο χειρισμό προφίλ κατά το άνοιγμα του αρχείου. 1 = σκόπιμα χωρίς ετικέτα. |
| TransparencyIndexPhotoshop6 | `1047` | Δείκτης διαφάνειας. 2 byte για τον δείκτη διαφανούς χρώματος, εάν υπάρχει. |
| GlobalAltitudePhotoshop6 | `1049` | Παγκόσμιο υψόμετρο. Καταχώρηση 4 byte για υψόμετρο. |
| SlicesPhotoshop6 | `1050` | Slices (Photoshop 6). |
| WorkflowUrlPhotoshop6 | `1051` | URL ροής εργασίας. Συμβολοσειρά Unicode. Photoshop 6. |
| AlphaIdentifiersPhotoshop6 | `1053` | Αναγνωριστικά Alpha. 4 byte μήκους, ακολουθούμενα από 4 byte το καθένα για κάθε αναγνωριστικό άλφα. |
| UrlListPhotoshop6 | `1054` | URL InternalList. 4 byte πλήθος διευθύνσεων URL, ακολουθούμενο από μήκος 4 byte, αναγνωριστικό 4 byte και συμβολοσειρά Unicode για κάθε μέτρηση. |
| VersionInfoPhotoshop6 | `1057` | Πληροφορίες έκδοσης. Έκδοση 4 byte, 1 byte έχειRealMergedData, συμβολοσειρά Unicode: όνομα συγγραφέα, συμβολοσειρά Unicode: όνομα αναγνώστη, έκδοση αρχείου 4 byte. |
| ExifData1Photoshop7 | `1058` | Δεδομένα EXIF 1,[δείτε περισσότερα](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) . |
| ExifData3Photoshop7 | `1059` | [ Δεδομένα EXIF 3.](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) |
| XmpPhotoshop7 | `1060` | Μεταδεδομένα XMP. Πληροφορίες αρχείου ως περιγραφή XML,[δείτε περισσότερα](http://www.adobe.com/devnet/xmp) . |
| CaptionDigestPhotoshop7 | `1061` | Ανακεφαλαίωση λεζάντας. 16 byte: Ασφάλεια δεδομένων RSA, αλγόριθμος σύνοψης μηνυμάτων MD5. |
| PrintScalePhotoshop7 | `1062` | Κλίμακα εκτύπωσης. Στυλ 2 byte (0 = κεντραρισμένο, 1 = μέγεθος που ταιριάζει, 2 = ορίζεται από το χρήστη). 4 byte x θέση (κινητή υποδιαστολή). 4 byte y θέση (κινητή υποδιαστολή). Κλίμακα 4 byte (κινητή υποδιαστολή). |
| PixelAspectRatio | `1064` | Αναλογία διαστάσεων εικονοστοιχείων. 4 byte (έκδοση = 1 ή 2), 8 byte διπλά, x / y ενός pixel. Έκδοση 2, προσπαθεί να διορθώσει τιμές για NTSC και PAL, που προηγουμένως ήταν απενεργοποιημένες κατά έναν παράγοντα περίπου. 5%. |
| LayerComps | `1065` | Σύνθ. 4 byte (έκδοση περιγραφής = 16), Περιγραφέας. |
| LayerSelectionIds | `1069` | Αναγνωριστικό(α) επιλογής επιπέδου. Αριθμός 2 byte, επαναλαμβάνεται το εξής για κάθε μέτρηση: 4 byte ID επιπέδου. |
| PrintInfoCS2 | `1071` | Εκτύπωση πληροφοριών (Photoshop CS2). |
| LayerGroupEnabledIdCS2 | `1072` | Ενεργοποιημένο αναγνωριστικό ομάδας(ών) επιπέδων. 1 byte για κάθε επίπεδο στο έγγραφο, επαναλαμβανόμενο κατά μήκος του πόρου. ΣΗΜΕΙΩΣΗ: Οι ομάδες επιπέδων έχουν δείκτες έναρξης και τέλους (Photoshop CS2). |
| ColorSamplersResourceCS3 | `1073` | Πηγή δειγματοληψιών χρώματος. Δείτε επίσης το ID 1038 για παλιά μορφή. |
| MeasurementScaleCS3 | `1074` | Κλίμακα μέτρησης. 4 byte (έκδοση περιγραφής = 16), Περιγραφέας. |
| TimelineInformationCS3 | `1075` | Πληροφορίες χρονολογίου. 4 byte (έκδοση περιγραφής = 16), Περιγραφέας. |
| SheetDisclosureCS3 | `1076` | Αποκάλυψη φύλλου. 4 byte (έκδοση περιγραφής = 16), Περιγραφέας. |
| PrintInformationCS5 | `1082` | Εκτύπωση πληροφοριών (Photoshop CS5). |
| PrintStyleCS5 | `1083` | Στυλ εκτύπωσης (Photoshop CS5). |
| MacintoshNSPrintInfoCS5 | `1084` | Macintosh NSPrintInfo. Πληροφορίες μεταβλητού λειτουργικού συστήματος για Macintosh. NSPrintInfo. Συνιστάται να μην ερμηνεύετε ή να χρησιμοποιείτε αυτά τα δεδομένα. (Photoshop CS5). |
| WindowsDevmodeCS5 | `1085` | DEVMODE των Windows. Πληροφορίες μεταβλητού λειτουργικού συστήματος για Windows. DEVMODE. Συνιστάται να μην ερμηνεύετε ή να χρησιμοποιείτε αυτά τα δεδομένα. (Photoshop CS5). |
| AutoSaveFilePathCS6 | `1086` | Διαδρομή αρχείου αυτόματης αποθήκευσης. Συμβολοσειρά Unicode. (Photoshop CS6). |
| AutoSaveFormatCS6 | `1087` | Μορφή αυτόματης αποθήκευσης. Συμβολοσειρά Unicode. (Photoshop CS6). |
| PathSelectionStateCC | `1088` | Κατάσταση επιλογής διαδρομής. (Photoshop CC). |
| ImageReadyVariables | `7000` | Μεταβλητές Image Ready. XML αναπαράσταση μεταβλητών ορισμός. |
| ImageReadyDatasets | `7001` | Σύνολα δεδομένων Ready Image. |
| PrintFlagsInformation | `10000` | Εκτύπωση πληροφοριών σημαιών. Έκδοση 2 byte ( = 1), 1 byte κεντρικά σημάδια περικοπής, 1 byte ( = 0), τιμή πλάτους διαρροής 4 byte, κλίμακα πλάτους εξαέρωσης 2 byte. |

### Δείτε επίσης

* χώρος ονομάτων [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
