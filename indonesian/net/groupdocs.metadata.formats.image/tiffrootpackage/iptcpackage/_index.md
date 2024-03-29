---
title: IptcPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mendapat atau menyetel paket metadata IPTC.
type: docs
weight: 20
url: /id/net/groupdocs.metadata.formats.image/tiffrootpackage/iptcpackage/
---
## TiffRootPackage.IptcPackage property

Mendapat atau menyetel paket metadata IPTC.

```csharp
public IptcRecordSet IptcPackage { get; set; }
```

### Nilai properti

Paket metadata IPTC.

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata IIM IPTC](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Contoh

Contoh ini menunjukkan cara mengekstrak properti metadata IPTC dasar dari gambar TIFF.

```csharp
using (Metadata metadata = new Metadata(Constants.TiffWithIptc))
{
    var root = metadata.GetRootPackage<TiffRootPackage>();
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

### Lihat juga

* class [IptcRecordSet](../../../groupdocs.metadata.standards.iptc/iptcrecordset)
* class [TiffRootPackage](../../tiffrootpackage)
* ruang nama [GroupDocs.Metadata.Formats.Image](../../tiffrootpackage)
* perakitan [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
