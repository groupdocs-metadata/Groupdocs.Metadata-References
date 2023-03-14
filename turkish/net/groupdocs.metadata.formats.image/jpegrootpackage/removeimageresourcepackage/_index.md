---
title: RemoveImageResourcePackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Photoshop Image Resource meta veri paketini kaldırır.
type: docs
weight: 70
url: /tr/net/groupdocs.metadata.formats.image/jpegrootpackage/removeimageresourcepackage/
---
## JpegRootPackage.RemoveImageResourcePackage method

Photoshop Image Resource meta veri paketini kaldırır.

```csharp
public void RemoveImageResourcePackage()
```

### Notlar

**Daha fazla bilgi edin**

* [JPEG görüntülerde meta verilerle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG+images)

### Örnekler

Bu kod parçacığı, Photoshop meta verilerinin bir JPEG görüntüsünden nasıl kaldırılacağını gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithIrb))
{
    var root = metadata.GetRootPackage<JpegRootPackage>();
    root.RemoveImageResourcePackage();

    metadata.Save(Constants.OutputJpeg);
}
```

### Ayrıca bakınız

* class [JpegRootPackage](../../jpegrootpackage)
* ad alanı [GroupDocs.Metadata.Formats.Image](../../jpegrootpackage)
* toplantı [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->