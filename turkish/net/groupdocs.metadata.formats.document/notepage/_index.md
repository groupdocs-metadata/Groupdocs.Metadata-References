---
title: NotePage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: OneNote bölümündeki bir sayfayı temsil eder.
type: docs
weight: 960
url: /tr/net/groupdocs.metadata.formats.document/notepage/
---
## NotePage class

OneNote bölümündeki bir sayfayı temsil eder.

```csharp
public class NotePage : CustomPackage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/notepage/author) { get; } | Sayfa yazarını alır. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [CreationTime](../../groupdocs.metadata.formats.document/notepage/creationtime) { get; } | Oluşturma zamanını alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [LastModificationTime](../../groupdocs.metadata.formats.document/notepage/lastmodificationtime) { get; } | Son değişiklik zamanını alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [Title](../../groupdocs.metadata.formats.document/notepage/title) { get; } | Sayfa başlığını alır. |

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

* [Not biçimlerinde meta verilerle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Note+formats)

### Ayrıca bakınız

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ad alanı [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->