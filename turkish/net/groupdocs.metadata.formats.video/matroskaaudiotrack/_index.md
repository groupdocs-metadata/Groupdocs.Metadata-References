---
title: MatroskaAudioTrack
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir Matroska videosundaki ses meta verilerini temsil eder.
type: docs
weight: 2430
url: /tr/net/groupdocs.metadata.formats.video/matroskaaudiotrack/
---
## MatroskaAudioTrack class

Bir Matroska videosundaki ses meta verilerini temsil eder.

```csharp
public class MatroskaAudioTrack : MatroskaTrack
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BitDepth](../../groupdocs.metadata.formats.video/matroskaaudiotrack/bitdepth) { get; } | Çoğunlukla PCM. için kullanılan örnek başına bitleri alır |
| [Channels](../../groupdocs.metadata.formats.video/matroskaaudiotrack/channels) { get; } | Parçadaki kanalların sayısını alır. |
| [CodecID](../../groupdocs.metadata.formats.video/matroskatrack/codecid) { get; } | codec'e karşılık gelen bir kimlik alır. |
| [CodecName](../../groupdocs.metadata.formats.video/matroskatrack/codecname) { get; } | Codec. 'yi belirten insanlar tarafından okunabilir bir dize alır |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [DefaultDuration](../../groupdocs.metadata.formats.video/matroskatrack/defaultduration) { get; } | Nanosaniye sayısını alır (aracılığıyla ölçeklenmez)[`TimecodeScale`](../matroskasegment/timecodescale) ) kare başına. |
| [FlagEnabled](../../groupdocs.metadata.formats.video/matroskatrack/flagenabled) { get; } | İz kullanılabilirse doğru olan etkin bayrağını alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [Language](../../groupdocs.metadata.formats.video/matroskatrack/language) { get; } | Parçanın dilini Matroska dilleri formunda alır. Bu öğe, eğer[`LanguageIetf`](../matroskatrack/languageietf) Öğe, aynı TrackEntry. içinde kullanılıyor |
| [LanguageIetf](../../groupdocs.metadata.formats.video/matroskatrack/languageietf) { get; } | Parçanın dilini BCP 47'ye göre ve IANA Dil Alt Etiketi Kayıt Defterini kullanarak alır. Bu Öğe kullanılırsa, herhangi bir[`Language`](../matroskatrack/language) Aynı TrackEntry'de kullanılan öğeler dikkate alınmamalıdır ZORUNLU. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [Name](../../groupdocs.metadata.formats.video/matroskatrack/name) { get; } | İnsanların okuyabileceği parça adını alır. |
| [OutputSamplingFrequency](../../groupdocs.metadata.formats.video/matroskaaudiotrack/outputsamplingfrequency) { get; } | Hz cinsinden gerçek çıkış örnekleme frekansını alır (SBR teknikleri için kullanılır). |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren tanımlayıcılardan oluşan bir koleksiyon alır. |
| [SamplingFrequency](../../groupdocs.metadata.formats.video/matroskaaudiotrack/samplingfrequency) { get; } | Örnekleme frekansını Hz. olarak alır |
| [TrackNumber](../../groupdocs.metadata.formats.video/matroskatrack/tracknumber) { get; } | Blok Başlığında kullanılan parça numarasını alır. Tasarım sınırsız sayıya izin verse de 127'den fazla parça kullanılması önerilmez. |
| [TrackType](../../groupdocs.metadata.formats.video/matroskatrack/tracktype) { get; } | Parçanın türünü alır. |
| [TrackUid](../../groupdocs.metadata.formats.video/matroskatrack/trackuid) { get; } | Parçayı tanımlamak için benzersiz kimliği alır. Bu, Parçanın başka bir dosyaya doğrudan akış kopyası yapılırken aynı tutulması GEREKİR. |

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

* class [MatroskaTrack](../matroskatrack)
* ad alanı [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
