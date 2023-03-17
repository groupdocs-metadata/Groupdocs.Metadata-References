---
title: Item
second_title: GroupDocs.Metadata for .NET API Reference
description: Gets the Raw tag with the specified id.
type: docs
weight: 10
url: /net/groupdocs.metadata.formats.raw/rawdictionarybasepackage/item/
---
## RawDictionaryBasePackage indexer

Gets the Raw tag with the specified id.

```csharp
public RawTag this[uint tagId] { get; }
```

| Parameter | Description |
| --- | --- |
| tagId | The id of the tag to retrieve. |

### Return Value

The [`RawTag`](../../../groupdocs.metadata.formats.raw.tag/rawtag) with the specified tag id.

### Examples

This example demonstrates how to read a specific Raw/EXIF tag by its identifier.

```csharp
using (Metadata metadata = new Metadata(Constants.RawWithExif))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null && root.ExifPackage != null)
    {
        RawAsciiTag software = (RawAsciiTag)root.ExifPackage[uint.Software];
        if (software != null)
        {
            Console.WriteLine("Software: {0}", software.Value);
        }
    }
}
```

### See Also

* class [RawTag](../../../groupdocs.metadata.formats.raw.tag/rawtag)
* class [RawDictionaryBasePackage](../../rawdictionarybasepackage)
* namespace [GroupDocs.Metadata.Formats.Raw](../../rawdictionarybasepackage)
* assembly [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->