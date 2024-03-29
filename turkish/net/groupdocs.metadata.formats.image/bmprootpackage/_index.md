---
title: BmpRootPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir BMP görüntüsünde meta verilerle çalışması amaçlanan kök paketi temsil eder.
type: docs
weight: 1660
url: /tr/net/groupdocs.metadata.formats.image/bmprootpackage/
---
## BmpRootPackage class

Bir BMP görüntüsünde meta verilerle çalışması amaçlanan kök paketi temsil eder.

```csharp
public class BmpRootPackage : ImageRootPackage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BmpHeader](../../groupdocs.metadata.formats.image/bmprootpackage/bmpheader) { get; } | BMP başlık meta veri paketini alır. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [FileType](../../groupdocs.metadata.formats.image/imagerootpackage/filetype) { get; } | Meta veri paketi dosya türünü alır. (2 properties) |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren tanımlayıcılardan oluşan bir koleksiyon alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ekler. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Paketin belirtilen ada sahip bir meta veri özelliği içerip içermediğini belirler. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini bulur. Arama özyinelemeli olduğu için iç içe geçmiş tüm paketleri de etkiler. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Koleksiyon boyunca yinelenen bir numaralandırıcı döndürür. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini kaldırır. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Paketten yazılabilir meta veri özelliklerini kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Notlar

**Daha fazla bilgi edin**

* [BMP meta verileriyle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+BMP+metadata)

### Örnekler

Bu kod örneği, bir BMP dosyasının başlığının nasıl okunacağını gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.InputBmp))
{
    var root = metadata.GetRootPackage<BmpRootPackage>();

    Console.WriteLine(root.BmpHeader.BitsPerPixel);
    Console.WriteLine(root.BmpHeader.ColorsImportant);
    Console.WriteLine(root.BmpHeader.HeaderSize);
    Console.WriteLine(root.BmpHeader.ImageSize);
    Console.WriteLine(root.BmpHeader.Planes);
}
```

### Ayrıca bakınız

* class [ImageRootPackage](../imagerootpackage)
* ad alanı [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
