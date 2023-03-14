---
title: ImageResourceBlock
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir Photoshop Görüntü Kaynağı bloğunu temsil eder.  Görüntü kaynak blokları Photoshopun yerel dosya biçimi JPEG ve TIFF dahil olmak üzere çeşitli dosya biçimlerinin temel yapı birimidir. Görüntü kaynakları kalem aracı yolları gibi görüntülerle ilişkili piksel olmayan verileri depolamak için kullanılır.
type: docs
weight: 1740
url: /tr/net/groupdocs.metadata.formats.image/imageresourceblock/
---
## ImageResourceBlock class

Bir Photoshop Görüntü Kaynağı bloğunu temsil eder.  Görüntü kaynak blokları, Photoshop'un yerel dosya biçimi, JPEG ve TIFF dahil olmak üzere çeşitli dosya biçimlerinin temel yapı birimidir. Görüntü kaynakları, kalem aracı yolları gibi görüntülerle ilişkili piksel olmayan verileri depolamak için kullanılır.

```csharp
public sealed class ImageResourceBlock : CustomPackage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Data](../../groupdocs.metadata.formats.image/imageresourceblock/data) { get; } | Kaynak verilerini alır. |
| [ID](../../groupdocs.metadata.formats.image/imageresourceblock/id) { get; } | Kaynak için benzersiz tanımlayıcıyı alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [Name](../../groupdocs.metadata.formats.image/imageresourceblock/name) { get; } | Görüntü kaynak bloğu adını alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [Signature](../../groupdocs.metadata.formats.image/imageresourceblock/signature) { get; } | Görüntü kaynak bloğu imzasını alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ekler. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Paketin belirtilen ada sahip bir meta veri özelliği içerip içermediğini belirler. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini bulur. Arama özyinelemeli olduğu için iç içe geçmiş tüm paketleri de etkiler. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Koleksiyon boyunca yinelenen bir numaralandırıcı döndürür. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini kaldırır. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Paketten yazılabilir meta veri özelliklerini kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Notlar

**Daha fazla bilgi edin**

* [PSD görüntülerinde meta verilerle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PSD+images)

### Ayrıca bakınız

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ad alanı [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->