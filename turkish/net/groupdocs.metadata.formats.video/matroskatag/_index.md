---
title: MatroskaTag
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir Matroska videosundaki Parçaları Basımları Bölümleri Ekleri veya Segmenti bir bütün olarak açıklayan meta verileri temsil eder.
type: docs
weight: 2530
url: /tr/net/groupdocs.metadata.formats.video/matroskatag/
---
## MatroskaTag class

Bir Matroska videosundaki Parçaları, Basımları, Bölümleri, Ekleri veya Segmenti bir bütün olarak açıklayan meta verileri temsil eder.

```csharp
public class MatroskaTag : MatroskaBasePackage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren tanımlayıcılardan oluşan bir koleksiyon alır. |
| [SimpleTags](../../groupdocs.metadata.formats.video/matroskatag/simpletags) { get; } | Hedef hakkında genel bilgileri alır. |
| [TagTrackUid](../../groupdocs.metadata.formats.video/matroskatag/tagtrackuid) { get; } | Etiketlerin ait olduğu Parkurları tanımlamak için benzersiz bir kimlik alır. Bu seviyede değer 0 ise, etiketler Segmentteki tüm izlere uygulanır. |
| [TargetType](../../groupdocs.metadata.formats.video/matroskatag/targettype) { get; } | Hedefin mantıksal düzeyini görüntülemek için kullanılabilecek bir bilgi dizisi alır. "ALBUM", "PARÇA", "FİLM", "BÖLÜM" vb. gibi. |
| [TargetTypeValue](../../groupdocs.metadata.formats.video/matroskatag/targettypevalue) { get; } | Hedefin mantıksal düzeyini gösteren sayıyı alır. |

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

* [Matroska (MKV) dosyalarında meta verilerle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### Ayrıca bakınız

* class [MatroskaBasePackage](../matroskabasepackage)
* ad alanı [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
