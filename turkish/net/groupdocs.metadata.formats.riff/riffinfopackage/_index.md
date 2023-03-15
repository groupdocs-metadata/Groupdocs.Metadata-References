---
title: RiffInfoPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: RIFF INFO öbeğinden çıkarılan özellikleri içeren meta veri paketini temsil eder.
type: docs
weight: 2220
url: /tr/net/groupdocs.metadata.formats.riff/riffinfopackage/
---
## RiffInfoPackage class

RIFF INFO öbeğinden çıkarılan özellikleri içeren meta veri paketini temsil eder.

```csharp
public sealed class RiffInfoPackage : CustomPackage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Artist](../../groupdocs.metadata.formats.riff/riffinfopackage/artist) { get; } | Dosyanın orijinal konusunun sanatçısını alır. |
| [Comment](../../groupdocs.metadata.formats.riff/riffinfopackage/comment) { get; } | Dosya veya dosyanın konusu hakkındaki yorumu alır. |
| [Copyright](../../groupdocs.metadata.formats.riff/riffinfopackage/copyright) { get; } | Dosyanın telif hakkı bilgilerini alır. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [CreationDate](../../groupdocs.metadata.formats.riff/riffinfopackage/creationdate) { get; } | Dosyanın konusunun oluşturulduğu tarihi alır. |
| [Engineer](../../groupdocs.metadata.formats.riff/riffinfopackage/engineer) { get; } | Dosya üzerinde çalışan mühendisin adını alır. |
| [Genre](../../groupdocs.metadata.formats.riff/riffinfopackage/genre) { get; } | Orijinal çalışmanın türünü alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [Keywords](../../groupdocs.metadata.formats.riff/riffinfopackage/keywords) { get; } | Dosyaya veya dosyanın konusuna atıfta bulunan anahtar sözcükleri alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [Name](../../groupdocs.metadata.formats.riff/riffinfopackage/name) { get; } | Dosyanın konusunun başlığını alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren tanımlayıcılardan oluşan bir koleksiyon alır. |
| [Software](../../groupdocs.metadata.formats.riff/riffinfopackage/software) { get; } | Dosyayı oluşturmak için kullanılan yazılım paketinin adını alır. |
| [Source](../../groupdocs.metadata.formats.riff/riffinfopackage/source) { get; } | Dosyanın orijinal konusunu sağlayan kişi veya kuruluşun adını alır. |
| [Subject](../../groupdocs.metadata.formats.riff/riffinfopackage/subject) { get; } | "Seattle'ın havadan görünümü" gibi dosya içeriğinin bir açıklamasını alır. |
| [Technician](../../groupdocs.metadata.formats.riff/riffinfopackage/technician) { get; } | Konu dosyasını sayısallaştıran teknisyeni alır. |

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

### Ayrıca bakınız

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ad alanı [GroupDocs.Metadata.Formats.Riff](../../groupdocs.metadata.formats.riff)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
