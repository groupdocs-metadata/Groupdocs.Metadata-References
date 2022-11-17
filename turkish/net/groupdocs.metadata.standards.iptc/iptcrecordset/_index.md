---
title: IptcRecordSet
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir IPTC kayıtları koleksiyonunu temsil eder.
type: docs
weight: 2940
url: /tr/net/groupdocs.metadata.standards.iptc/iptcrecordset/
---
## IptcRecordSet class

Bir IPTC kayıtları koleksiyonunu temsil eder.

```csharp
public sealed class IptcRecordSet : CustomPackage
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [IptcRecordSet](iptcrecordset#constructor)() | Yeni bir örneğini başlatır.[`IptcRecordSet`](../iptcrecordset) sınıf. |
| [IptcRecordSet](iptcrecordset#constructor_1)(IptcDataSet[]) | Yeni bir örneğini başlatır.[`IptcRecordSet`](../iptcrecordset) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ApplicationRecord](../../groupdocs.metadata.standards.iptc/iptcrecordset/applicationrecord) { get; set; } | Uygulama Kaydını alır veya ayarlar. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [EnvelopeRecord](../../groupdocs.metadata.standards.iptc/iptcrecordset/enveloperecord) { get; set; } | Zarf Kaydını alır veya ayarlar. |
| [Item](../../groupdocs.metadata.standards.iptc/iptcrecordset/item) { get; } | Şunu alır:[`IptcRecord`](../iptcrecord) belirtilen sayı ile. (3 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Add](../../groupdocs.metadata.standards.iptc/iptcrecordset/add)(IptcDataSet) | Belirtilen dataSet'i uygun kayda ekler. Belirtilen sayıya sahip bir dataSet zaten mevcutsa, dataSet tekrarlanabilir olarak kabul edilir. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ekler. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |
| [Clear](../../groupdocs.metadata.standards.iptc/iptcrecordset/clear)() | Koleksiyondaki tüm kayıtları kaldırır. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Paketin belirtilen ada sahip bir meta veri özelliği içerip içermediğini belirler. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini bulur. Arama özyinelemeli olduğu için iç içe geçmiş tüm paketleri de etkiler. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Koleksiyon boyunca yinelenen bir numaralandırıcı döndürür. |
| [Remove](../../groupdocs.metadata.standards.iptc/iptcrecordset/remove#remove)(byte) | Belirtilen kayıt numaralı kaydı kaldırır. |
| [Remove](../../groupdocs.metadata.standards.iptc/iptcrecordset/remove#remove_1)(byte, byte) | Belirtilen kayıt ve dataSet numarasına sahip dataSet'i kaldırır. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini kaldırır. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Paketten yazılabilir meta veri özelliklerini kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler. |
| [Set](../../groupdocs.metadata.standards.iptc/iptcrecordset/set)(IptcDataSet) | Belirtilen dataSet'i uygun kayda ekler veya günceller. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [ToDataSetList](../../groupdocs.metadata.standards.iptc/iptcrecordset/todatasetlist)() | Paketten veri Kümelerinin bir listesini oluşturur. |
| [ToList](../../groupdocs.metadata.standards.iptc/iptcrecordset/tolist)() | Paketten bir liste oluşturur. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Notlar

**Daha fazla bilgi edin**

* [IPTC IIM meta verileriyle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Örnekler

Bu kod örneği, temel IPTC meta veri özelliklerini güncellemek için etkin olduğunu gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IIptc root = metadata.GetRootPackage() as IIptc;
    if (root != null)
    {
        // IPTC paketi yoksa ayarlayın
        if (root.IptcPackage == null)
        {
            root.IptcPackage = new IptcRecordSet();
        }

        if (root.IptcPackage.EnvelopeRecord == null)
        {
            root.IptcPackage.EnvelopeRecord = new IptcEnvelopeRecord();
        }

        root.IptcPackage.EnvelopeRecord.DateSent = DateTime.Now;
        root.IptcPackage.EnvelopeRecord.ProductID = Guid.NewGuid().ToString();

        // ...

        if (root.IptcPackage.ApplicationRecord == null)
        {
            root.IptcPackage.ApplicationRecord = new IptcApplicationRecord();
        }

        root.IptcPackage.ApplicationRecord.ByLine = "GroupDocs";
        root.IptcPackage.ApplicationRecord.Headline = "test";
        root.IptcPackage.ApplicationRecord.ByLineTitle = "code sample";
        root.IptcPackage.ApplicationRecord.ReleaseDate = DateTime.Today;

        // ...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Ayrıca bakınız

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ad alanı [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
