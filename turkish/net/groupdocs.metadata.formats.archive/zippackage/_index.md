---
title: ZipPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: ZIP arşiv meta verilerini temsil eder.
type: docs
weight: 360
url: /tr/net/groupdocs.metadata.formats.archive/zippackage/
---
## ZipPackage class

ZIP arşiv meta verilerini temsil eder.

```csharp
public sealed class ZipPackage : CustomPackage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Comment](../../groupdocs.metadata.formats.archive/zippackage/comment) { get; set; } | Bir kullanıcı tarafından oluşturulan ZIP arşiv yorumunu alır veya ayarlar. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Files](../../groupdocs.metadata.formats.archive/zippackage/files) { get; } | Bir dizi alır[`ZipFile`](../zipfile) ZIP arşivi içindeki girişler. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren tanımlayıcılardan oluşan bir koleksiyon alır. |
| [TotalEntries](../../groupdocs.metadata.formats.archive/zippackage/totalentries) { get; } | ZIP arşivindeki toplam giriş sayısını alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ekler. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Paketin belirtilen ada sahip bir meta veri özelliği içerip içermediğini belirler. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini bulur. Arama özyinelemeli olduğu için iç içe geçmiş tüm paketleri de etkiler. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Koleksiyon boyunca yinelenen bir numaralandırıcı döndürür. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini kaldırır. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Paketten yazılabilir meta veri özelliklerini kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Notlar

**Daha fazla bilgi edin**

* [ZIP arşivleriyle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+ZIP+archives)

### Örnekler

Aşağıdaki kod parçacığı, bir ZIP arşivinden meta verilerin nasıl alınacağını gösterir.

```csharp
Encoding encoding = Encoding.GetEncoding(866);

using (Metadata metadata = new Metadata(Constants.InputZip))
{
    var root = metadata.GetRootPackage<ZipRootPackage>();

    Console.WriteLine(root.ZipPackage.Comment);
    Console.WriteLine(root.ZipPackage.TotalEntries);

    foreach (var file in root.ZipPackage.Files)
    {
        Console.WriteLine(file.Name);
        Console.WriteLine(file.CompressedSize);
        Console.WriteLine(file.CompressionMethod);
        Console.WriteLine(file.Flags);
        Console.WriteLine(file.ModificationDateTime);
        Console.WriteLine(file.UncompressedSize);

        // Dosya adları için belirli bir kodlama kullanın
        Console.WriteLine(encoding.GetString(file.RawName));
    }
}
```

### Ayrıca bakınız

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ad alanı [GroupDocs.Metadata.Formats.Archive](../../groupdocs.metadata.formats.archive)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
