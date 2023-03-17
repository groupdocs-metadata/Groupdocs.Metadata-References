---
title: ID3V2Tag
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει μια ετικέτα ID3v2. Βρείτε περισσότερες πληροφορίες στοhttps//en.wikipedia.org/wiki/ID3ID3v2https//en.wikipedia.org/wiki/ID3ID3v2 .
type: docs
weight: 490
url: /el/net/groupdocs.metadata.formats.audio/id3v2tag/
---
## ID3V2Tag class

Αντιπροσωπεύει μια ετικέτα ID3v2. Βρείτε περισσότερες πληροφορίες στο[https://en.wikipedia.org/wiki/ID3#ID3v2](https://en.wikipedia.org/wiki/ID3#ID3v2) .

```csharp
public sealed class ID3V2Tag : ID3Tag
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [ID3V2Tag](id3v2tag)() | Αρχικοποιεί μια νέα παρουσία του[`ID3V2Tag`](../id3v2tag) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v2tag/album) { get; set; } | Λαμβάνει ή ορίζει τον τίτλο του Άλμπουμ/Ταινίας/Εμφάνισης. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TALB. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v2tag/artist) { get; set; } | Λαμβάνει ή ορίζει τους Κύριους καλλιτέχνες/Κορυφαίους καλλιτέχνες/Σολίστ/Σολίστ/Ερμηνευτική ομάδα. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TPE1. |
| [AttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/attachedpictures) { get; set; } | Λαμβάνει ή ορίζει τις συνημμένες εικόνες που σχετίζονται άμεσα με το αρχείο ήχου. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο APIC. |
| [Band](../../groupdocs.metadata.formats.audio/id3v2tag/band) { get; set; } | Λαμβάνει ή ορίζει το Band/Orchestra/Accompaniment. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TPE2. |
| [BitsPerMinute](../../groupdocs.metadata.formats.audio/id3v2tag/bitsperminute) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό των παλμών ανά λεπτό στο κύριο μέρος του ήχου. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TBPM. |
| [Comments](../../groupdocs.metadata.formats.audio/id3v2tag/comments) { get; set; } | Λαμβάνει ή ορίζει τα σχόλια του χρήστη. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο COMM. Το πλαίσιο προορίζεται για κάθε είδους πληροφορίες πλήρους κειμένου που δεν χωρούν σε κανένα άλλο πλαίσιο. |
| [Composers](../../groupdocs.metadata.formats.audio/id3v2tag/composers) { get; set; } | Παίρνει ή ορίζει τους συνθέτες. Τα ονόματα διαχωρίζονται με τον χαρακτήρα "/". Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TCOM. |
| [ContentType](../../groupdocs.metadata.formats.audio/id3v2tag/contenttype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο περιεχομένου. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TCON. |
| [Copyright](../../groupdocs.metadata.formats.audio/id3v2tag/copyright) { get; set; } | Λαμβάνει ή ορίζει το μήνυμα πνευματικών δικαιωμάτων. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TCOP. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [Date](../../groupdocs.metadata.formats.audio/id3v2tag/date) { get; set; } | Λαμβάνει ή ορίζει μια αριθμητική συμβολοσειρά σε μορφή DDMM που περιέχει την ημερομηνία για την εγγραφή. Αυτό το πεδίο έχει πάντα τέσσερις χαρακτήρες. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TDAT. |
| [EncodedBy](../../groupdocs.metadata.formats.audio/id3v2tag/encodedby) { get; set; } | Λαμβάνει ή ορίζει το όνομα του ατόμου ή του οργανισμού που κωδικοποίησε το αρχείο ήχου. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TENC. |
| [Isrc](../../groupdocs.metadata.formats.audio/id3v2tag/isrc) { get; set; } | Λαμβάνει ή ορίζει τον διεθνή τυπικό κώδικα εγγραφής (ISRC) (12 χαρακτήρες). Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TSRC. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [LengthInMilliseconds](../../groupdocs.metadata.formats.audio/id3v2tag/lengthinmilliseconds) { get; set; } | Λαμβάνει ή ορίζει το μήκος του αρχείου ήχου σε χιλιοστά του δευτερολέπτου, που αναπαρίσταται ως αριθμητική συμβολοσειρά. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TLEN. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [MusicalKey](../../groupdocs.metadata.formats.audio/id3v2tag/musicalkey) { get; set; } | Λαμβάνει ή ρυθμίζει το μουσικό πλήκτρο από το οποίο ξεκινά ο ήχος. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TKEY. |
| [OriginalAlbum](../../groupdocs.metadata.formats.audio/id3v2tag/originalalbum) { get; set; } | Λαμβάνει ή ορίζει τον αρχικό τίτλο του άλμπουμ/της ταινίας/της εκπομπής. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TOAL. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [Publisher](../../groupdocs.metadata.formats.audio/id3v2tag/publisher) { get; set; } | Λαμβάνει ή ορίζει το όνομα της ετικέτας ή του εκδότη. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TPUB. |
| [SizeInBytes](../../groupdocs.metadata.formats.audio/id3v2tag/sizeinbytes) { get; set; } | Λαμβάνει ή ορίζει το μέγεθος του αρχείου ήχου σε byte, εξαιρουμένης της ετικέτας ID3v2, που αναπαρίσταται ως αριθμητική συμβολοσειρά. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TSIZ. |
| [SoftwareHardware](../../groupdocs.metadata.formats.audio/id3v2tag/softwarehardware) { get; set; } | Λαμβάνει ή ορίζει τον χρησιμοποιημένο κωδικοποιητή ήχου και τις ρυθμίσεις του όταν το αρχείο κωδικοποιήθηκε. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TSSE. |
| [Subtitle](../../groupdocs.metadata.formats.audio/id3v2tag/subtitle) { get; set; } | Λαμβάνει ή ορίζει τη βελτίωση Υπότιτλου/Περιγραφής. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TIT3. |
| [TagSize](../../groupdocs.metadata.formats.audio/id3v2tag/tagsize) { get; } | Παίρνει το μέγεθος της ετικέτας. |
| [Time](../../groupdocs.metadata.formats.audio/id3v2tag/time) { get; set; } | Λαμβάνει ή ορίζει μια αριθμητική συμβολοσειρά σε μορφή HHMM που περιέχει την ώρα για την εγγραφή. Αυτό το πεδίο έχει πάντα τέσσερις χαρακτήρες. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TIME. |
| [Title](../../groupdocs.metadata.formats.audio/id3v2tag/title) { get; set; } | Λαμβάνει ή ορίζει τον τίτλο/όνομα τραγουδιού/περιγραφή περιεχομένου. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TIT2. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v2tag/tracknumber) { get; set; } | Λαμβάνει ή ορίζει μια αριθμητική συμβολοσειρά που περιέχει τον αριθμό παραγγελίας του αρχείου ήχου στην αρχική του εγγραφή. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TRCK. |
| [TrackPlayCounter](../../groupdocs.metadata.formats.audio/id3v2tag/trackplaycounter) { get; } | Λαμβάνει τον αριθμό των φορών που έχει αναπαραχθεί το αρχείο. Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο PCNT. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v2tag/version) { get; } | Αποκτά την έκδοση ID3. |
| [Year](../../groupdocs.metadata.formats.audio/id3v2tag/year) { get; set; } | Λαμβάνει ή ορίζει μια αριθμητική συμβολοσειρά με ένα έτος εγγραφής. Αυτό το πλαίσιο έχει πάντα τέσσερις χαρακτήρες (μέχρι το έτος 10000). Αυτή η τιμή αντιπροσωπεύεται από το πλαίσιο TYER. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Add](../../groupdocs.metadata.formats.audio/id3v2tag/add)(ID3V2TagFrame) | Προσθέτει ένα πλαίσιο στην ετικέτα. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Προσθέτει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Clear](../../groupdocs.metadata.formats.audio/id3v2tag/clear)(string) | Αφαιρεί όλα τα καρέ με το καθορισμένο αναγνωριστικό. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Καθορίζει εάν το πακέτο περιέχει μια ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Βρίσκει τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η αναζήτηση είναι αναδρομική, επομένως επηρεάζει όλα τα ένθετα πακέτα επίσης. |
| [Get](../../groupdocs.metadata.formats.audio/id3v2tag/get)(string) | Λαμβάνει έναν πίνακα πλαισίων με το καθορισμένο αναγνωριστικό. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Επιστρέφει έναν απαριθμητή που επαναλαμβάνει τη συλλογή. |
| [Remove](../../groupdocs.metadata.formats.audio/id3v2tag/remove)(ID3V2TagFrame) | Αφαιρεί το καθορισμένο πλαίσιο από την ετικέτα. |
| [RemoveAttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/removeattachedpictures)() | Αφαιρεί όλες τις συνημμένες εικόνες που είναι αποθηκευμένες σε πλαίσια APIC. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Καταργεί τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Αφαιρεί τις ιδιότητες μεταδεδομένων με δυνατότητα εγγραφής από το πακέτο. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Set](../../groupdocs.metadata.formats.audio/id3v2tag/set)(ID3V2TagFrame) | Καταργεί όλα τα πλαίσια που έχουν το ίδιο αναγνωριστικό με το καθορισμένο και προσθέτει το νέο πλαίσιο στην ετικέτα. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ορίζει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. Αυτή η μέθοδος είναι ένας συνδυασμός[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) και[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Εάν μια υπάρχουσα ιδιότητα ικανοποιεί το κατηγόρημα, η τιμή της ενημερώνεται. Εάν λείπει μια γνωστή ιδιότητα στο πακέτο που ικανοποιεί το κατηγόρημα, προστίθεται στο πακέτο. |
| [ToList](../../groupdocs.metadata.formats.audio/id3v2tag/tolist)() | Δημιουργεί μια λίστα από το πακέτο. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ενημερώνει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Χειρισμός της ετικέτας ID3v2](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να διαβάζετε την ετικέτα ID3v2 σε ένα αρχείο MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V2 != null)
    {
        Console.WriteLine(root.ID3V2.Album);
        Console.WriteLine(root.ID3V2.Artist);
        Console.WriteLine(root.ID3V2.Band);
        Console.WriteLine(root.ID3V2.Title);
        Console.WriteLine(root.ID3V2.Composers);
        Console.WriteLine(root.ID3V2.Copyright);
        Console.WriteLine(root.ID3V2.Publisher);
        Console.WriteLine(root.ID3V2.OriginalAlbum);
        Console.WriteLine(root.ID3V2.MusicalKey);

        if (root.ID3V2.AttachedPictures != null)
        {
            foreach (var attachedPicture in root.ID3V2.AttachedPictures)
            {
                Console.WriteLine(attachedPicture.AttachedPictureType);
                Console.WriteLine(attachedPicture.MimeType);
                Console.WriteLine(attachedPicture.Description);

                //...
            }
        }

        //...
    }
}
```

### Δείτε επίσης

* class [ID3Tag](../id3tag)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
