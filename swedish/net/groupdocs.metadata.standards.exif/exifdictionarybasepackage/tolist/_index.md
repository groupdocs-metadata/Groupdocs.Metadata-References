---
title: ToList
second_title: GroupDocs.Metadata for .NET API-referens
description: Skapar en lista från paketet.
type: docs
weight: 50
url: /sv/net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist/
---
## ExifDictionaryBasePackage.ToList method

Skapar en lista från paketet.

```csharp
public IReadOnlyList<TiffTag> ToList()
```

### Returvärde

En lista som innehåller alla TIFF-taggar från paketet.

### Exempel

Det här exemplet visar hur man läser alla EXIF-taggar som extraherats från en fil.

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithExif))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null && root.ExifPackage != null)
    {
        const string pattern = "{0} = {1}";

        foreach (TiffTag tag in root.ExifPackage.ToList())
        {
            Console.WriteLine(pattern, tag.TagID, tag.Value);
        }

        foreach (TiffTag tag in root.ExifPackage.ExifIfdPackage.ToList())
        {
            Console.WriteLine(pattern, tag.TagID, tag.Value);
        }

        foreach (TiffTag tag in root.ExifPackage.GpsPackage.ToList())
        {
            Console.WriteLine(pattern, tag.TagID, tag.Value);
        }
    }
}
```

### Se även

* interface [IReadOnlyList&lt;T&gt;](../../../groupdocs.metadata.common/ireadonlylist-1)
* class [TiffTag](../../../groupdocs.metadata.formats.image/tifftag)
* class [ExifDictionaryBasePackage](../../exifdictionarybasepackage)
* namnutrymme [GroupDocs.Metadata.Standards.Exif](../../exifdictionarybasepackage)
* hopsättning [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
