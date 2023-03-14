---
title: Sanitize
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Yazılabilir meta veri özelliklerini algılanan tüm paketlerden veya mümkünse tüm paketlerden kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler.
type: docs
weight: 100
url: /tr/net/groupdocs.metadata/metadata/sanitize/
---
## Metadata.Sanitize method

Yazılabilir meta veri özelliklerini algılanan tüm paketlerden veya mümkünse tüm paketlerden kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler.

```csharp
public int Sanitize()
```

### Geri dönüş değeri

Etkilenen özelliklerin sayısı.

### Notlar

**Daha fazla bilgi edin**

* [Meta verileri temizle](https://docs.groupdocs.com/display/metadatanet/Clean+metadata)

### Örnekler

Bu örnek, algılanan tüm meta veri paketlerinin/özelliklerinin bir dosyadan nasıl kaldırılacağını gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPdf))
{
    // Algılanan meta veri paketlerini kaldır
    var affected = metadata.Sanitize();
    Console.WriteLine("Properties removed: {0}", affected);

    metadata.Save(Constants.OutputPdf);
}
```

### Ayrıca bakınız

* class [Metadata](../../metadata)
* ad alanı [GroupDocs.Metadata](../../metadata)
* toplantı [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->