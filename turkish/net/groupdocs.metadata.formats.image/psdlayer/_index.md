---
title: PsdLayer
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: PSD dosyasındaki bir katmanı temsil eder.
type: docs
weight: 1900
url: /tr/net/groupdocs.metadata.formats.image/psdlayer/
---
## PsdLayer class

PSD dosyasındaki bir katmanı temsil eder.

```csharp
public sealed class PsdLayer : CustomPackage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BitsPerPixel](../../groupdocs.metadata.formats.image/psdlayer/bitsperpixel) { get; } | Piksel başına bit değerini alır. |
| [Bottom](../../groupdocs.metadata.formats.image/psdlayer/bottom) { get; } | Alt katman konumunu alır. |
| [ChannelCount](../../groupdocs.metadata.formats.image/psdlayer/channelcount) { get; } | Kanal sayısını alır. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Flags](../../groupdocs.metadata.formats.image/psdlayer/flags) { get; } | Katman işaretlerini alır. |
| [Height](../../groupdocs.metadata.formats.image/psdlayer/height) { get; } | Yüksekliği alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [Left](../../groupdocs.metadata.formats.image/psdlayer/left) { get; } | Sol katman konumunu alır. |
| [Length](../../groupdocs.metadata.formats.image/psdlayer/length) { get; } | Bayt cinsinden toplam katman uzunluğunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [Name](../../groupdocs.metadata.formats.image/psdlayer/name) { get; } | Katman adını alır. |
| [Opacity](../../groupdocs.metadata.formats.image/psdlayer/opacity) { get; } | Katman opaklığını alır. 0 = saydam, 255 = opak. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [Right](../../groupdocs.metadata.formats.image/psdlayer/right) { get; } | Doğru katman konumunu alır. |
| [Top](../../groupdocs.metadata.formats.image/psdlayer/top) { get; } | Üst katman konumunu alır. |
| [Width](../../groupdocs.metadata.formats.image/psdlayer/width) { get; } | Genişliği alır. |

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
