---
title: LyricsTag
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει μεταδεδομένα Lyrics3 v2.00. Βρείτε περισσότερες πληροφορίες στοhttp//id3.org/Lyrics3v2 .
type: docs
weight: 570
url: /el/net/groupdocs.metadata.formats.audio/lyricstag/
---
## LyricsTag class

Αντιπροσωπεύει μεταδεδομένα Lyrics3 v2.00. Βρείτε περισσότερες πληροφορίες στοhttp://id3.org/Lyrics3v2 .

```csharp
public sealed class LyricsTag : CustomPackage
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [LyricsTag](lyricstag)() | Αρχικοποιεί μια νέα παρουσία του[`LyricsTag`](../lyricstag) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AdditionalInfo](../../groupdocs.metadata.formats.audio/lyricstag/additionalinfo) { get; set; } | Λαμβάνει ή ορίζει τις πρόσθετες πληροφορίες. Αυτή η τιμή αντιπροσωπεύεται από το πεδίο INF. |
| [Album](../../groupdocs.metadata.formats.audio/lyricstag/album) { get; set; } | Λαμβάνει ή ορίζει το όνομα του άλμπουμ. Αυτή η τιμή αντιπροσωπεύεται από το πεδίο EAL. |
| [Artist](../../groupdocs.metadata.formats.audio/lyricstag/artist) { get; set; } | Λαμβάνει ή ορίζει το όνομα καλλιτέχνη. Αυτή η τιμή αντιπροσωπεύεται από το πεδίο EAR. |
| [Author](../../groupdocs.metadata.formats.audio/lyricstag/author) { get; set; } | Λαμβάνει ή ορίζει τον συγγραφέα. Αυτή η τιμή αντιπροσωπεύεται από το πεδίο AUT. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Λαμβάνει τον αριθμό των ιδιοτήτων μεταδεδομένων. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Λαμβάνει το[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) με το καθορισμένο όνομα. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Λαμβάνει μια συλλογή από ονόματα ιδιοτήτων μεταδεδομένων. |
| [Lyrics](../../groupdocs.metadata.formats.audio/lyricstag/lyrics) { get; set; } | Λαμβάνει ή ορίζει τους στίχους. Αυτή η τιμή αντιπροσωπεύεται από το πεδίο LYR. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Λαμβάνει τον τύπο μεταδεδομένων. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Λαμβάνει μια συλλογή περιγραφών που περιέχουν πληροφορίες σχετικά με ιδιότητες προσβάσιμες μέσω της μηχανής αναζήτησης GroupDocs.Metadata. |
| [Track](../../groupdocs.metadata.formats.audio/lyricstag/track) { get; set; } | Λαμβάνει ή ορίζει τον τίτλο του κομματιού. Αυτή η τιμή αντιπροσωπεύεται από το πεδίο ETT. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Προσθέτει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Καθορίζει εάν το πακέτο περιέχει μια ιδιότητα μεταδεδομένων με το καθορισμένο όνομα. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Βρίσκει τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η αναζήτηση είναι αναδρομική, επομένως επηρεάζει όλα τα ένθετα πακέτα επίσης. |
| [Get](../../groupdocs.metadata.formats.audio/lyricstag/get)(string) | Λαμβάνει την τιμή του πεδίου με το καθορισμένο αναγνωριστικό. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Επιστρέφει έναν απαριθμητή που επαναλαμβάνει τη συλλογή. |
| [Remove](../../groupdocs.metadata.formats.audio/lyricstag/remove)(string) | Καταργεί το πεδίο με το καθορισμένο αναγνωριστικό. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Καταργεί τις ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Αφαιρεί τις ιδιότητες μεταδεδομένων με δυνατότητα εγγραφής από το πακέτο. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |
| [Set](../../groupdocs.metadata.formats.audio/lyricstag/set)(LyricsField) | Προσθέτει ή αντικαθιστά το καθορισμένο πεδίο Lyrics3. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ορίζει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. Αυτή η μέθοδος είναι ένας συνδυασμός[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) και[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Εάν μια υπάρχουσα ιδιότητα ικανοποιεί το κατηγόρημα, η τιμή της ενημερώνεται. Εάν λείπει μια γνωστή ιδιότητα στο πακέτο που ικανοποιεί το κατηγόρημα, προστίθεται στο πακέτο. |
| [ToList](../../groupdocs.metadata.formats.audio/lyricstag/tolist)() | Δημιουργεί μια λίστα από το πακέτο. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ενημερώνει γνωστές ιδιότητες μεταδεδομένων που ικανοποιούν το καθορισμένο κατηγόρημα. Η λειτουργία είναι αναδρομική, επομένως επηρεάζει επίσης όλα τα ένθετα πακέτα. |

### Παρατηρήσεις

Το Lyrics3 v2.00 χρησιμοποιεί πεδία για την αναπαράσταση πληροφοριών. Τα δεδομένα σε ένα πεδίο μπορεί να αποτελούνται από χαρακτήρες ASCII στην περιοχή 01 έως 254 σύμφωνα με το πρότυπο. Καθώς ο χάρτης χαρακτήρων ASCII ορίζεται μόνο από 00 έως 128 ISO-8859- 1 μπορεί να υποτεθεί. Τα αριθμητικά πεδία έχουν μήκος 5 ή 6 χαρακτήρες, ανάλογα με την τοποθεσία, και συμπληρώνονται με μηδενικά.

**Μάθε περισσότερα**

* [Χειρισμός της ετικέτας Lyrics](https://docs.groupdocs.com/display/metadatanet/Handling+the+Lyrics+tag)

### Παραδείγματα

Αυτό το δείγμα κώδικα δείχνει πώς να διαβάζετε την ετικέτα Lyrics από ένα αρχείο MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithLyrics))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.Lyrics3V2 != null)
    {
        Console.WriteLine(root.Lyrics3V2.Lyrics);
        Console.WriteLine(root.Lyrics3V2.Album);
        Console.WriteLine(root.Lyrics3V2.Artist);
        Console.WriteLine(root.Lyrics3V2.Track);

        //...

        // Εναλλακτικά, μπορείτε να κάνετε βρόχο μέσω μιας πλήρους λίστας πεδίων ετικετών
        foreach (var field in root.Lyrics3V2.ToList())
        {
            Console.WriteLine("{0} = {1}", field.ID, field.Data);
        }
    }
}
```

### Δείτε επίσης

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
