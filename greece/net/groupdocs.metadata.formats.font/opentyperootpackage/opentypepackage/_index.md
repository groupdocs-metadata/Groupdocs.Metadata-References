---
title: OpenTypePackage
second_title: GroupDocs.Metadata για Αναφορά API .NET
description: Λαμβάνει το πακέτο μεταδεδομένων OpenType.
type: docs
weight: 20
url: /el/net/groupdocs.metadata.formats.font/opentyperootpackage/opentypepackage/
---
## OpenTypeRootPackage.OpenTypePackage property

Λαμβάνει το πακέτο μεταδεδομένων OpenType.

```csharp
public OpenTypePackage OpenTypePackage { get; }
```

### Αξία περιουσίας

Το πακέτο μεταδεδομένων OpenType.

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Εργασία με γραμματοσειρές OpenType](https://docs.groupdocs.com/display/metadatanet/Working+with+OpenType+fonts)

### Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να διαβάζετε τα μεταδεδομένα γραμματοσειράς OpenType.

```csharp
using (Metadata metadata = new Metadata(Constants.InputTtf))
{
    var root = metadata.GetRootPackage<OpenTypeRootPackage>();

    // Διαβάστε τα μεταδεδομένα γραμματοσειράς OpenType
    foreach (var metadataEntry in root.OpenTypePackage.Fonts)
    {
        // Εμφάνιση των τιμών ορισμένων ιδιοτήτων μεταδεδομένων
        Console.WriteLine(metadataEntry.Created);
        Console.WriteLine(metadataEntry.DirectionHint);
        Console.WriteLine(metadataEntry.EmbeddingLicensingRights);
        Console.WriteLine(metadataEntry.Flags);
        Console.WriteLine(metadataEntry.FontFamilyName);
        Console.WriteLine(metadataEntry.FontRevision);
        Console.WriteLine(metadataEntry.FontSubfamilyName);
        Console.WriteLine(metadataEntry.FullFontName);
        Console.WriteLine(metadataEntry.GlyphBounds);
        Console.WriteLine(metadataEntry.MajorVersion);
        Console.WriteLine(metadataEntry.MinorVersion);
        Console.WriteLine(metadataEntry.Modified);
        Console.WriteLine(metadataEntry.SfntVersion);
        Console.WriteLine(metadataEntry.Style);
        Console.WriteLine(metadataEntry.TypographicFamily);
        Console.WriteLine(metadataEntry.TypographicSubfamily);
        Console.WriteLine(metadataEntry.Weight);
        Console.WriteLine(metadataEntry.Width);
        foreach (OpenTypeBaseNameRecord nameRecord in metadataEntry.Names)
        {
            Console.WriteLine(nameRecord.NameID);
            Console.WriteLine(nameRecord.Platform);
            Console.WriteLine(nameRecord.Value);
            OpenTypeMacintoshNameRecord macintoshNameRecord = nameRecord as OpenTypeMacintoshNameRecord;
            if (macintoshNameRecord != null)
            {
                Console.WriteLine(macintoshNameRecord.Encoding);
                Console.WriteLine(macintoshNameRecord.Language);
            }
            else
            {
                OpenTypeUnicodeNameRecord unicodeNameRecord = nameRecord as OpenTypeUnicodeNameRecord;
                if (unicodeNameRecord != null)
                {
                    Console.WriteLine(unicodeNameRecord.Encoding);
                }
                else
                {
                    OpenTypeWindowsNameRecord windowsNameRecord = nameRecord as OpenTypeWindowsNameRecord;
                    if (windowsNameRecord != null)
                    {
                        Console.WriteLine(windowsNameRecord.Encoding);
                        Console.WriteLine(windowsNameRecord.Language);
                    }
                }
            }
        }
    }
}
```

### Δείτε επίσης

* class [OpenTypePackage](../../opentypepackage)
* class [OpenTypeRootPackage](../../opentyperootpackage)
* χώρος ονομάτων [GroupDocs.Metadata.Formats.Font](../../opentyperootpackage)
* συνέλευση [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->