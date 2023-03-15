---
title: XmpArray
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Αντιπροσωπεύει την αφαίρεση βάσης για τον πίνακα XMP.
type: docs
weight: 3250
url: /el/net/groupdocs.metadata.standards.xmp/xmparray/
---
## XmpArray class

Αντιπροσωπεύει την αφαίρεση βάσης για τον πίνακα XMP.

```csharp
public class XmpArray : XmpValueBase
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [XmpArray](xmparray#constructor)(XmpArrayType, XmpComplexType[]) | Αρχικοποιεί μια νέα παρουσία του[`XmpArray`](../xmparray) τάξη. |
| [XmpArray](xmparray#constructor_1)(XmpArrayType, XmpValueBase[]) | Αρχικοποιεί μια νέα παρουσία του[`XmpArray`](../xmparray) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [ArrayType](../../groupdocs.metadata.standards.xmp/xmparray/arraytype) { get; } | Λαμβάνει τον τύπο του πίνακα XMP. |
| [RawValue](../../groupdocs.metadata.common/propertyvalue/rawvalue) { get; } | Λαμβάνει την ακατέργαστη τιμή. |
| [Type](../../groupdocs.metadata.common/propertyvalue/type) { get; } | Λαμβάνει το[`MetadataPropertyType`](../../groupdocs.metadata.common/metadatapropertytype) . |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from_2)(DateTime[], XmpArrayType) | Δημιουργεί ένα[`XmpArray`](../xmparray) παράδειγμα από έναν πίνακα ημερομηνιών. |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from)(double[], XmpArrayType) | Δημιουργεί ένα[`XmpArray`](../xmparray) παράδειγμα σχηματίζουν έναν διπλό πίνακα. |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from_1)(int[], XmpArrayType) | Δημιουργεί ένα[`XmpArray`](../xmparray) παράδειγμα σχηματίζουν έναν ακέραιο πίνακα. |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from_3)(string[], XmpArrayType) | Δημιουργεί ένα[`XmpArray`](../xmparray) παράδειγμα σχηματίζουν έναν πίνακα συμβολοσειρών. |
| static [From&lt;T&gt;](../../groupdocs.metadata.standards.xmp/xmparray/from#from_4)(T[], XmpArrayType) | Δημιουργεί ένα[`XmpArray`](../xmparray)παράδειγμα σχηματίζουν έναν πίνακα από[`XmpComplexType`](../xmpcomplextype) . |
| [AcceptValue](../../groupdocs.metadata.common/propertyvalue/acceptvalue)(ValueAcceptor) | Εξάγει την τιμή της ιδιότητας χρησιμοποιώντας ένα προσαρμοσμένο[`ValueAcceptor`](../../groupdocs.metadata.common/valueacceptor) . |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmparray/getxmprepresentation)() | Μετατρέπει την τιμή XMP στην αναπαράσταση xml. |
| [ToArray&lt;TElement&gt;](../../groupdocs.metadata.common/propertyvalue/toarray)() | Μετατρέπει την τιμή της ιδιότητας σε έναν πίνακα του καθορισμένου τύπου. |
| [ToClass&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/toclass)() | Μετατρέπει την τιμή της ιδιότητας σε τύπο αναφοράς. |
| [ToPlatformArray&lt;T&gt;](../../groupdocs.metadata.standards.xmp/xmparray/toplatformarray)() | Μετατρέπει το[`XmpArray`](../xmparray) σε συστοιχία συγκεκριμένης πλατφόρμας. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpvaluebase/tostring)() | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει την τιμή της ιδιότητας. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)() | Μετατρέπει την τιμή της ιδιότητας σε τύπο τιμής. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)(T) | Μετατρέπει την τιμή της ιδιότητας σε τύπο τιμής. |

### Δείτε επίσης

* class [XmpValueBase](../xmpvaluebase)
* χώρος ονομάτων [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* συνέλευση [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->