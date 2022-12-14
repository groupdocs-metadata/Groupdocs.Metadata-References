---
title: Jpeg2000Package
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: JPEG2000 yerel meta veri paketini alır.
type: docs
weight: 20
url: /tr/net/groupdocs.metadata.formats.image/jpeg2000rootpackage/jpeg2000package/
---
## Jpeg2000RootPackage.Jpeg2000Package property

JPEG2000 yerel meta veri paketini alır.

```csharp
public Jpeg2000Package Jpeg2000Package { get; }
```

### Mülk değeri

JPEG2000 yerel meta veri paketi.

### Notlar

**Daha fazla bilgi edin**

* [JPEG2000 görüntülerinde meta verilerle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG2000+images)

### Örnekler

Bu kod parçacığı, JPEG2000 resim yorumlarının nasıl okunacağını gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg2000))
{
    var root = metadata.GetRootPackage<Jpeg2000RootPackage>();

    if (root.Jpeg2000Package.Comments != null)
    {
        foreach (var comment in root.Jpeg2000Package.Comments)
        {
            Console.WriteLine(comment);
        }
    }
}
```

### Ayrıca bakınız

* class [Jpeg2000Package](../../jpeg2000package)
* class [Jpeg2000RootPackage](../../jpeg2000rootpackage)
* ad alanı [GroupDocs.Metadata.Formats.Image](../../jpeg2000rootpackage)
* toplantı [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
