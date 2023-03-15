---
title: PsdCompressionMethod
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Καθορίζει τη μέθοδο συμπίεσης που χρησιμοποιείται για δεδομένα εικόνας.
type: docs
weight: 1890
url: /el/net/groupdocs.metadata.formats.image/psdcompressionmethod/
---
## PsdCompressionMethod enumeration

Καθορίζει τη μέθοδο συμπίεσης που χρησιμοποιείται για δεδομένα εικόνας.

```csharp
public enum PsdCompressionMethod
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| Raw | `0` | Χωρίς συμπίεση. Τα δεδομένα εικόνας αποθηκεύονται ως ακατέργαστα byte σε επίπεδη σειρά RGBA. Αυτό σημαίνει ότι πρώτα γράφονται όλα τα δεδομένα R, μετά γράφονται όλα τα G, μετά όλα τα B και τέλος όλα τα δεδομένα A. |
| Rle | `1` | RLE συμπιεσμένο. Τα δεδομένα εικόνας ξεκινούν με τις μετρήσεις byte για όλες τις γραμμές σάρωσης (γραμμές * κανάλια), με κάθε μέτρηση να αποθηκεύεται ως τιμή δύο byte. Ακολουθούν τα συμπιεσμένα δεδομένα RLE, με κάθε γραμμή σάρωσης συμπιεσμένη χωριστά. Η συμπίεση RLE είναι ο ίδιος αλγόριθμος συμπίεσης που χρησιμοποιείται από το Macintosh ROM ρουτίνας PackBits και το πρότυπο TIFF. |
| ZipWithoutPrediction | `2` | ZIP χωρίς πρόβλεψη. |
| ZipWithPrediction | `3` | ZIP με πρόβλεψη. |

### Δείτε επίσης

* χώρος ονομάτων [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->