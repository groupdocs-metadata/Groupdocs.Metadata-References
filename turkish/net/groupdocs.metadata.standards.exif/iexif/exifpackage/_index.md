---
title: ExifPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Dosyayla ilişkili EXIF meta veri paketini alır veya ayarlar.
type: docs
weight: 10
url: /tr/net/groupdocs.metadata.standards.exif/iexif/exifpackage/
---
## IExif.ExifPackage property

Dosyayla ilişkili EXIF meta veri paketini alır veya ayarlar.

```csharp
public ExifPackage ExifPackage { get; set; }
```

### Mülk değeri

Dosyayla ilişkili EXIF meta veri paketi.

### Notlar

**Daha fazla bilgi edin**

* [EXIF meta verileriyle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Örnekler

Bu kod örneği, EXIF meta verilerinin bir dosyadan nasıl kaldırılacağını gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithExif))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        root.ExifPackage = null;

        metadata.Save(Constants.OutputJpeg);
     }
}
```

### Ayrıca bakınız

* class [ExifPackage](../../exifpackage)
* interface [IExif](../../iexif)
* ad alanı [GroupDocs.Metadata.Standards.Exif](../../iexif)
* toplantı [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
