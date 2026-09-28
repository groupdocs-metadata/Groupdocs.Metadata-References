---
title: IIptc class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents base operations intended to work with IPTC metadata."
type: docs
url: /python-net/groupdocs.metadata.standards.iptc/iiptc/
is_root: false
weight: 10
---


## IIptc class

Represents base operations intended to work with IPTC metadata.

Learn more
- https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata

The IIptc type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [iptc_package](/metadata/python-net/groupdocs.metadata.standards.iptc/iiptc/iptc_package/) | The IPTC metadata package associated with the file. |

### Example

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithIptc))
{
    IIptc root = metadata.GetRootPackage() as IIptc;
    if (root != null && root.IptcPackage != null)
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
* module [`groupdocs.metadata.standards.iptc`](/metadata/python-net/groupdocs.metadata.standards.iptc/)
