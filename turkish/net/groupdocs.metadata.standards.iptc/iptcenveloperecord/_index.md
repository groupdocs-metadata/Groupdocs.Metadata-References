---
title: IptcEnvelopeRecord
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir IPTC Zarf Kaydını Temsil Eder.
type: docs
weight: 2910
url: /tr/net/groupdocs.metadata.standards.iptc/iptcenveloperecord/
---
## IptcEnvelopeRecord class

Bir IPTC Zarf Kaydını Temsil Eder.

```csharp
public sealed class IptcEnvelopeRecord : IptcRecord
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [IptcEnvelopeRecord](iptcenveloperecord)() | Yeni bir örneğini başlatır.[`IptcEnvelopeRecord`](../iptcenveloperecord) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [DateSent](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/datesent) { get; set; } | Hizmetin materyali gönderdiği tarihi alır veya ayarlar. |
| [Destination](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/destination) { get; set; } | Hedefi alır veya ayarlar. |
| [Destinations](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/destinations) { get; set; } | Bir dizi hedef alır veya ayarlar. |
| [FileFormat](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/fileformat) { get; set; } | Dosya biçimini alır veya ayarlar. |
| [FileFormatVersion](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/fileformatversion) { get; set; } | Dosya biçimi sürümünü alır veya ayarlar. İçinde belirtilen Dosya Biçiminin belirli sürümünü temsil eden bir sayı[`FileFormat`](./fileformat) . |
| [Item](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/item) { get; } | Şunu alır:[`IptcDataSet`](../iptcdataset) belirtilen sayı ile. (3 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [ModelVersion](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/modelversion) { get; set; } | Bilginin sürümünü tanımlayan bir sayı alır veya ayarlar. |
| [ProductID](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/productid) { get; set; } | Ürün tanımlayıcısını alır veya ayarlar. |
| [ProductIds](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/productids) { get; set; } | Ürün tanımlayıcılarını alır veya ayarlar. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren tanımlayıcılardan oluşan bir koleksiyon alır. |
| [RecordNumber](../../groupdocs.metadata.standards.iptc/iptcrecord/recordnumber) { get; } | Kayıt numarasını alır. |
| [ServiceIdentifier](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/serviceidentifier) { get; set; } | Hizmet tanımlayıcısını alır veya ayarlar. |

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
| [ToList](../../groupdocs.metadata.standards.iptc/iptcrecord/tolist)() | Paketten bir liste oluşturur. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Notlar

**Daha fazla bilgi edin**

* [IPTC IIM meta verileriyle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Ayrıca bakınız

* class [IptcRecord](../iptcrecord)
* ad alanı [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
