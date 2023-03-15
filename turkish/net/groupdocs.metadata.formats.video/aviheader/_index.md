---
title: AviHeader
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir AVI videosundaki AVIMAINHEADER yapısını temsil eder.
type: docs
weight: 2380
url: /tr/net/groupdocs.metadata.formats.video/aviheader/
---
## AviHeader class

Bir AVI videosundaki AVIMAINHEADER yapısını temsil eder.

```csharp
public sealed class AviHeader : CustomPackage
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [AviHeader](aviheader)() | Yeni bir örneğini başlatır.[`AviHeader`](../aviheader) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AviHeaderFlags](../../groupdocs.metadata.formats.video/aviheader/aviheaderflags) { get; } | AVI işaretlerinin sıfır veya daha fazlasının bit düzeyinde bir kombinasyonunu alır. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Height](../../groupdocs.metadata.formats.video/aviheader/height) { get; } | AVI dosyasının yüksekliğini piksel olarak alır. |
| [InitialFrames](../../groupdocs.metadata.formats.video/aviheader/initialframes) { get; } | Araya eklenmiş dosyalar için başlangıç çerçevesini alır.  Aralıksız dosyalar sıfır belirtmelidir. Aralıklı dosyalar oluşturuyorsanız, bu üyedeki AVI dizisinin ilk karesinden önceki dosyadaki kare sayısını belirtin. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MaxBytesPerSec](../../groupdocs.metadata.formats.video/aviheader/maxbytespersec) { get; } | Dosyanın yaklaşık maksimum veri hızını alır.  Bu değer, sistemin bir AVI dizisini ana başlıkta ve akış başlık parçalarında bulunan diğer parametreler tarafından belirtilen olarak sunmak için işlemesi gereken saniye başına bayt sayısını gösterir. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [MicroSecPerFrame](../../groupdocs.metadata.formats.video/aviheader/microsecperframe) { get; } | Çerçeveler arasındaki mikrosaniye sayısını alır. Bu değer, dosya için genel zamanlamayı gösterir. |
| [PaddingGranularity](../../groupdocs.metadata.formats.video/aviheader/paddinggranularity) { get; } | Veriler için bayt cinsinden hizalamayı alır. Verileri bu değerin katlarına doldurun. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren tanımlayıcılardan oluşan bir koleksiyon alır. |
| [Streams](../../groupdocs.metadata.formats.video/aviheader/streams) { get; } | Dosyadaki akış sayısını alır. Örneğin, ses ve video içeren bir dosyanın iki akışı vardır. |
| [SuggestedBufferSize](../../groupdocs.metadata.formats.video/aviheader/suggestedbuffersize) { get; } | Dosyayı okumak için önerilen arabellek boyutunu alır.  Genel olarak, bu boyutun dosyadaki en büyük öbeği içerecek kadar büyük olması gerekir. Sıfıra ayarlanırsa veya çok küçükse, oynatma yazılımının oynatma sırasında belleği yeniden ayırması gerekir, bu da performansı düşürür. Araya eklenmiş bir dosya için, arabellek boyutu, yalnızca bir parçayı değil tüm kaydı okuyabilecek kadar büyük olmalıdır. |
| [TotalFrames](../../groupdocs.metadata.formats.video/aviheader/totalframes) { get; } | Dosyadaki toplam veri çerçevesi sayısını alır. |
| [Width](../../groupdocs.metadata.formats.video/aviheader/width) { get; } | AVI dosyasının genişliğini piksel olarak alır. |

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

* [AVI dosyalarında meta verilerle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+AVI+files)

### Ayrıca bakınız

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ad alanı [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
