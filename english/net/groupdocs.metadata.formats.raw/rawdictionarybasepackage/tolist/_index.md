---
title: ToList
second_title: GroupDocs.Metadata for .NET API Reference
description: Creates a list from the package.
type: docs
weight: 50
url: /net/groupdocs.metadata.formats.raw/rawdictionarybasepackage/tolist/
---
## RawDictionaryBasePackage.ToList method

Creates a list from the package.

```csharp
public IReadOnlyList<RawTag> ToList()
```

### Return Value

A list that contains all Raw tags from the package.

### Examples

This example demonstrates how to read all EXIF tags extracted from a file.

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithExif))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null && root.ExifPackage != null)
    {
        const string pattern = "{0} = {1}";

        foreach (RawTag tag in root.ExifPackage.ToList())
        {
            Console.WriteLine(pattern, tag.TagID, tag.Value);
        }

        foreach (RawTag tag in root.ExifPackage.ExifIfdPackage.ToList())
        {
            Console.WriteLine(pattern, tag.TagID, tag.Value);
        }

        foreach (RawTag tag in root.ExifPackage.GpsPackage.ToList())
        {
            Console.WriteLine(pattern, tag.TagID, tag.Value);
        }
    }
}
```

### See Also

* interface [IReadOnlyList&lt;T&gt;](../../../groupdocs.metadata.common/ireadonlylist-1)
* class [RawTag](../../../groupdocs.metadata.formats.raw.tag/rawtag)
* class [RawDictionaryBasePackage](../../rawdictionarybasepackage)
* namespace [GroupDocs.Metadata.Formats.Raw](../../rawdictionarybasepackage)
* assembly [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->