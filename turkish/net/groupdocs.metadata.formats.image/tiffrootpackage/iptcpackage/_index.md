---
title: IptcPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: IPTC meta veri paketini alır veya ayarlar.
type: docs
weight: 20
url: /tr/net/groupdocs.metadata.formats.image/tiffrootpackage/iptcpackage/
---
## TiffRootPackage.IptcPackage property

IPTC meta veri paketini alır veya ayarlar.

```csharp
public IptcRecordSet IptcPackage { get; set; }
```

### Mülk değeri

IPTC meta veri paketi.

### Notlar

**Daha fazla bilgi edin**

* [IPTC IIM meta verileriyle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Örnekler

Bu örnek, temel IPTC meta veri özelliklerinin bir TIFF görüntüsünden nasıl çıkarılacağını gösterir.

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

### Ayrıca bakınız

* class [IptcRecordSet](../../../groupdocs.metadata.standards.iptc/iptcrecordset)
* class [TiffRootPackage](../../tiffrootpackage)
* ad alanı [GroupDocs.Metadata.Formats.Image](../../tiffrootpackage)
* toplantı [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->