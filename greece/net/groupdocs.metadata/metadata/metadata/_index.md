---
title: Metadata
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αρχικοποιεί μια νέα παρουσία τουMetadatagroupdocs.metadata/metadata τάξη.
type: docs
weight: 10
url: /el/net/groupdocs.metadata/metadata/metadata/
---
## Metadata(string) {#constructor_2}

Αρχικοποιεί μια νέα παρουσία του[`Metadata`](../../metadata) τάξη.

```csharp
public Metadata(string filePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Μια συμβολοσειρά που περιέχει το πλήρες όνομα του αρχείου από το οποίο θα δημιουργηθεί ένα[`Metadata`](../../metadata) παράδειγμα. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Φόρτωση από τοπικό δίσκο](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Φόρτωση από ροή](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Φορτώστε ένα αρχείο συγκεκριμένης μορφής](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Φορτώστε ένα έγγραφο που προστατεύεται με κωδικό πρόσβασης](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να φορτώσετε ένα αρχείο από έναν τοπικό δίσκο.

```csharp
using (Metadata metadata = new Metadata(Constants.InputOne))
{
    // Εξαγωγή, επεξεργασία ή κατάργηση μεταδεδομένων εδώ
}
```

### Δείτε επίσης

* class [Metadata](../../metadata)
* χώρος ονομάτων [GroupDocs.Metadata](../../metadata)
* συνέλευση [GroupDocs.Metadata](../../../)

---

## Metadata(Stream) {#constructor}

Αρχικοποιεί μια νέα παρουσία του[`Metadata`](../../metadata) τάξη.

```csharp
public Metadata(Stream document)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Μια ροή που περιέχει το έγγραφο προς φόρτωση. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Φόρτωση από τοπικό δίσκο](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Φόρτωση από ροή](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Φορτώστε ένα αρχείο συγκεκριμένης μορφής](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Φορτώστε ένα έγγραφο που προστατεύεται με κωδικό πρόσβασης](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να φορτώσετε ένα αρχείο από μια ροή.

```csharp
using (Stream stream = File.Open(Constants.InputDoc, FileMode.Open, FileAccess.ReadWrite))
using (Metadata metadata = new Metadata(stream))
{
   // Εξαγωγή, επεξεργασία ή κατάργηση μεταδεδομένων εδώ
}
```

### Δείτε επίσης

* class [Metadata](../../metadata)
* χώρος ονομάτων [GroupDocs.Metadata](../../metadata)
* συνέλευση [GroupDocs.Metadata](../../../)

---

## Metadata(string, LoadOptions) {#constructor_3}

Αρχικοποιεί μια νέα παρουσία του[`Metadata`](../../metadata) τάξη.

```csharp
public Metadata(string filePath, LoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Μια συμβολοσειρά που περιέχει το πλήρες όνομα του αρχείου από το οποίο θα δημιουργηθεί ένα[`Metadata`](../../metadata) παράδειγμα. |
| loadOptions | LoadOptions | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Φόρτωση από τοπικό δίσκο](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Φόρτωση από ροή](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Φορτώστε ένα αρχείο συγκεκριμένης μορφής](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Φορτώστε ένα έγγραφο που προστατεύεται με κωδικό πρόσβασης](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να φορτώσετε ένα έγγραφο που προστατεύεται με κωδικό πρόσβασης.

```csharp
// Καθορίστε τον κωδικό πρόσβασης
var loadOptions = new LoadOptions
{
    Password = "123"
};

using (var metadata = new Metadata(Constants.ProtectedDocx, loadOptions))
{
    // Εξαγωγή, επεξεργασία ή κατάργηση μεταδεδομένων εδώ
}
```

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* χώρος ονομάτων [GroupDocs.Metadata](../../metadata)
* συνέλευση [GroupDocs.Metadata](../../../)

---

## Metadata(Stream, LoadOptions) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία του[`Metadata`](../../metadata) τάξη.

```csharp
public Metadata(Stream document, LoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Μια ροή που περιέχει το έγγραφο προς φόρτωση. |
| loadOptions | LoadOptions | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Φόρτωση από τοπικό δίσκο](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Φόρτωση από ροή](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Φορτώστε ένα αρχείο συγκεκριμένης μορφής](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Φορτώστε ένα έγγραφο που προστατεύεται με κωδικό πρόσβασης](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* χώρος ονομάτων [GroupDocs.Metadata](../../metadata)
* συνέλευση [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
