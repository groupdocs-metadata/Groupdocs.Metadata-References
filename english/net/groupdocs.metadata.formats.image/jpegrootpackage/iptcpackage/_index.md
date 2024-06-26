---
title: IptcPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Gets or sets the IPTC metadata package.
type: docs
weight: 30
url: /net/groupdocs.metadata.formats.image/jpegrootpackage/iptcpackage/
---
## JpegRootPackage.IptcPackage property

Gets or sets the IPTC metadata package.

```csharp
public IptcRecordSet IptcPackage { get; set; }
```

### Property Value

The IPTC metadata package.

### Remarks

**Learn more**

* [Working with IPTC IIM metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Examples

This example shows how to read basic IPTC metadata properties.

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithIptc))
{
    var root = metadata.GetRootPackage<JpegRootPackage>();
    if (root.IptcPackage != null)
    {
        if (root.IptcPackage.EnvelopeRecord != null)
        {
            Console.WriteLine(root.IptcPackage.EnvelopeRecord.DateSent);
            Console.WriteLine(root.IptcPackage.EnvelopeRecord.Destination);
            Console.WriteLine(root.IptcPackage.EnvelopeRecord.FileFormat);
            Console.WriteLine(root.IptcPackage.EnvelopeRecord.FileFormatVersion);

            // ...
        }

        if (root.IptcPackage.ApplicationRecord != null)
        {
            Console.WriteLine(root.IptcPackage.ApplicationRecord.Headline);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.ByLine);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.ByLineTitle);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.CaptionAbstract);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.City);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.DateCreated);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.ReleaseDate);

            // ...
        }
    }
}
```

### See Also

* class [IptcRecordSet](../../../groupdocs.metadata.standards.iptc/iptcrecordset)
* class [JpegRootPackage](../../jpegrootpackage)
* namespace [GroupDocs.Metadata.Formats.Image](../../../groupdocs.metadata.formats.image)
* assembly [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
